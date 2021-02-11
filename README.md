# JurassicPark
##PEDAC##

P- Create an application that manages dinos in our zoo.

E-  |  Name       |  DietType  |  WhenAcquired  |  Weight  |  EnclosureNumber  |
    |-------------|------------|----------------|----------|-------------------|
    | Brontosaurus| Herbivore  |  Current Time  |77,162 LBS|       1           |
    | Ankylosaurus| Herbivore  |  Current Time  |13,200 LBS|       2           |
    |Dilophosaurus| Carnivore  |  Current Time  |  880 LBS |       3           |
    | Velociraptor| Carnivore  |  Current Time  |   28 LBS |       4           |

D- 
      - Class called 'Dinosaur'
          - Name (string)
          - DietType (string)
          - WhenAcquired (DateTime.Now)
          - Weight (int)
          - EnclosureNumber (int)
        
      - Method called 'Description' that prints a description that includes all the properties.

      - List<Dinosaur>

      - A menu that lets the user choose:
              - View:
                  Show all dinos in the list ordered by WhenAcquired. If none, print a message.
              - Add:
                  Lets user type in info for the dino and add it to the list. Prompt for all properties except WhenAcquired, which must be supplied by code.
              - Remove:
                  Prompt user for dino name and then finds it, and deletes the dino from the list.
              - Transfer:
                  Prompt the user for dino name and new EnclosureNumber and update that dino's info.
              - Summary:
                  Display the number of Carnivores and Herbivores.
              - Quit:
                  Stop the program.

            