# CrusadeApp
Crusade App design doc

Crusade is a sort of meta-game surrounding the standard Warhammer 40,000 tabletop wargame. It provides a progression system for individual units as well as providing meta-mechanics for your army, such as requisitioning new units and so on. This app will have several main features:

- Viewing a roster
- Viewing a unit
- adding/updating units to a roster

## Roster information

Each player will have specific stats that need to tracked on the roster. Here are the necessary fields:

     - Army Name
     - Faction
     - Unspent requisiont
     - Battles played
     - Battles won
     - Investigation points
     - Supply limit (power level)
     - Supply limit (points)
 
Derived fields:

    - Deployed power level

The roster will also need to display a stub for each of the units in the roster. These fields will be:
    
    - Unit Name -> Derived from the unit
    - Power LEvel/Points -> derived from teh unit
    - DEployed (T/F)

## Units

Each unit in the force will also have specific stats. The fields required are:

    - Name
    - Power Level
    - Battles fought
    - Battles Survived
    - Enemy Units destroyed
        - 3 subcategories (Psychic, ranged, melee)
    - Number of times marked for greatness
    - Rank (derived from XP)
    - Experience
    - Battle Honours
    - Battle Scars