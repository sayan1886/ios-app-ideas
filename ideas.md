# Ideas

1. Personal Github Reminder App
  - uses Github api to expose your personal repos and the ones that are stale
  - makes "to-do" out of Github repos and their open issues
2. Super MYOA
  - is a dungeon grid crawler
    - Make series of numbers in rectangular grid
    - 0-F represents the door configs
      - 0 all closed
      - 1 n
      - 2 e
      - 3 s
      - 4 w
      - 5 n e
      - 6 n s 
      - 7 n w 
      - 8 e s
      - 9 e w
      - A s w
      - B n e s
      - C n e w
      - D n s w 
      - E e s w
      - F all open
    - easy for others to make/share their own adventures
    - daily feed of new adventures
    - rooms addition
      - The couple connections from there joining event and then you can have a class that wraps A.R. has a event and then Maria connections and that's your typical of it like I have any can have another class called room that has a event and then four possible N S E W connections. 2d array of rooms is the level or map
          - Rooms have an item pointer
          - Rooms have a monster pointer 
          - Rooms have array of text based on conditions
          - Rooms have conditions
          - Rooms have visited Boolean 
      - Custom view for your normal movement which is generated by taking a CYOARoom object. In a room, the ui alert actions should be Move -- Interact with something (if possible) -- View Inventory.
      - For move it is Move North, Move South, ... (if available), and then finally   (Do Not Move) -- show room title only?
      - Dungeon has a key in one room
      - Dungeon has a spell tome
      - Dungeon has treasure at the end
      - Dungeon has pits and traps that do damage each time when entering room -- do enough damage and you must restart
      - Dungeon has rooms with conversations that can do damage if you say the wrong things
          - Need key for locked door
          - Need tome to open pass way 
          - Then get the treasure
          - Inventory is shown
          - Health is shown
    - Improve choose adventure by adding a daily feed
    - Daily feed has new adventures that you can complete
    - By completing the adventures you gain exp or something for your avatar on the app
3. Recipe maker
  - rated by family member
  - generated grocery list
4. Personal inventory management
5. Bracket builder for tournaments
6. random spinner to decide restaurants or make any choice
7. Makecraft (MineItMakeIt)
  - ability to post new recipes that goes to non public table that can be reviewed by admin in a web App!l
  - user login with parse/facebook so that they can up vote recipes
  - social sharing of recipes
  - can have a favorites list
  - will have to consider multiple Minecraft versions, not all blocks supported per version and will need to show supported versions for recipes
  - users can post an image and video url (YouTube)
  - send weekly push notification of this week's favorite recipe
  - specify bounding box in blocks
  - App idea number seven make a Minecraft app that gives instructions for how to create inventions and the resources required and also links to videos showing how to build them
8. Quizy Images
  - users can take/use a photo and record/type their question about their photo
  - then they can send these photo/questions to their friends to answer
  - it's like a personalized trivia crack mod
9. Familia
  - add recipe maker idea
  - add other things that keep the family together
  - you can have multiple families (promotes togetherness?)
  - has some chat features of group-me?
  - sharing family creations (food, music, photos)
10. Walk it Off
  - simple calorie tracker
  - daily burn (overburn) progress
  - focuses on Daily Recommended Nutritional values
11. Wheel Loader
  - add puzzle element to the wheel-loader (truck) game made for small children
12. ESDice
  - build dice game for Falco's ES project
  - OR build a generic dice game that doesn't incorporate ES
  - uses regionality/location to decide your default dice
  - and you can battle/play others to get new dice
  - dice could also be decided based on monsters collected in ES (kinda like Pokemon)