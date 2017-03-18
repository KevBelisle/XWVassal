# HWpopup

## Distance and geometry specs:

* Small base ship: 113 px ^2 
* Large base ship: 226 px ^2
* GR-75 / Gozanti / C-ROC Huge ship:  226 px by 551 px
* CR90 / Raider / ? Huge ship: 226 px by 635 px

* Range 1 =  282.5 px
* Range 2 =  565.0 px
* Range 3 = 847.5 px
* Range 4 = 1130.0 px
* Range 5 = 1412.5 px

* Small ship forward arc: 80.90 degrees
* Large ship forward arc: 84.05 degrees
* Large ship stardboard/port mobile turret arc: 95.95 degrees


##Updating the module

# Adding pilot and upgrade cards
1. Vassal editor
2. gradlew unpackVmod
3. gradlew downloadXwingData
4. push

# Adding new ships with dials
-Vassal editor, create a ship-specific Protytpe for its actions, await Radarman5's ship art and combine it in a deep-layered photoshop file  (save as png), create a new ship-specific tab in the Pieces window, create its dial
1. create ordered, open dial+strip for the new ship here: http://s93768914.onlinehome.us/xwing/dialgen/dialgen.html
2. gradlew unpackVmod
3. gradlew downloadXwingData
4. push

# Adding code
1. Your IDE of choice
2. gradlew downloadXwingData
3. gradlew buildVmod
4. push