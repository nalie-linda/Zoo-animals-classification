# Zoo-animals-classification

1. Title: Zoo database

2. Source Information
   -- Creator: Richard Forsyth
   -- Donor: Richard S. Forsyth 
             8 Grosvenor Avenue
             Mapperley Park
             Nottingham NG3 5DX
             0602-621676
   -- Date: 5/15/1990
 
3. Past Usage:
   -- None known other than what is shown in Forsyth's PC/BEAGLE User's Guide.

4. Relevant Information:
   -- A simple database containing 17 Boolean-valued attributes.  The "type"
      attribute appears to be the class attribute.  Here is a breakdown of
      which animals are in which type: (I find it unusual that there are
      2 instances of "frog" and one of "girl"!)

Set of animals:  Mammal, Bird, Reptile, Fish, Amphibian, Bug and Invertebrate
      ------- ===============================================================

     | Class| Number_Of_Animal_Species_In_Class|                   Animal_Names                                           |    Set Animals          |
     | -----| ---------------------------------|------------------------------------------------------------------------- | ------------------------|
     |    1 |  41    | aardvark, antelope, bear, boar, buffalo, calf, cavy, cheetah, deer, dolphin, elephant,             |      Mammals            |
                        fruitbat, giraffe, girl, goat, gorilla, hamster, hare, leopard, lion, lynx, mink, mole, mongoose,    
                        opossum, oryx, platypus, polecat, pony, porpoise, puma, pussycat, raccoon, reindeer,
                         seal, sealion, squirrel, vampire, vole, wallaby,wolf  
     |  2   |   20   |  chicken, crow, dove, duck, flamingo, gull, hawk, kiwi, lark, ostrich, parakeet, penguin, pheasant,|      Bird               |
                       rhea, skimmer, skua, sparrow, swan, vulture, wren                
     |  3   |  5     |    pitviper, seasnake, slowworm, tortoise, tuatara                                                  |     Reptile            |
      
   
     |  4   |    13  | bass, carp, catfish, chub, dogfish, haddock, herring, pike, piranha, seahorse, sole, stingray, tuna  |    Fish              |
                  
      | 5    |   4   |               frog, frog, newt, toad                                                                 |    Amphibian          |
      
      |  6   |    8  |       flea, gnat, honeybee, housefly, ladybird, moth, termite, wasp                                  |    Bug                |
      
      | 7    | 10    |      clam, crab, crayfish, lobster, octopus,   scorpion, seawasp, slug, starfish, worm               |     Invertebrate      |
                

6. Number of Instances: 101

7. Number of Attributes: 18 (animal name, 15 Boolean attributes, 2 numerics)

8. Attribute Information: (name of attribute and type of value domain)
   1. animal name:      Unique for each instance
   2. hair		Boolean
   3. feathers		Boolean
   4. eggs		Boolean
   5. milk		Boolean
   6. airborne		Boolean
   7. aquatic		Boolean
   8. predator		Boolean
   9. toothed		Boolean
  10. backbone		Boolean
  11. breathes		Boolean
  12. venomous		Boolean
  13. fins		Boolean
  14. legs		Numeric (set of values: {0,2,4,5,6,8})
  15. tail		Boolean
  16. domestic		Boolean
  17. catsize		Boolean
  18. type		Numeric (integer values in range [1,7])

8. Missing Attribute Values: None

9. Class Distribution: Given above
   
