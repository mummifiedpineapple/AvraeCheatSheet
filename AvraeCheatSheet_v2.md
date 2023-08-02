# Avrae Cheat Sheet

## Setup & Character Management

| Command             | Description                                                     | Notes             |
| ------------------- | --------------------------------------------------------------- | ----------------- |
| `!ddb`              | Displays information about your D&D Beyond account link.        |                   |
| `!beyond <url>`     | Loads a character sheet from D&D Beyond, resetting all settings |                   |
| `!character [name]` | Switch active character                                         | `/character list` |
| `!update`           | Update the current character sheet, preserving all settings     |                   |
| `!portrait`         | Shows the image of your currently active character              |                   |

## HP and Spell Slots

| Command              | Description                         | Notes                                               |
| -------------------- | ----------------------------------- | --------------------------------------------------- |
| `!g hp [args] [hp]`  | Modify HP of current character      | Common args: `max`, `modify`, `set`                 |
| `!g thp [hp]`        | Modify Temp-HP of current character | If positive, assumes set; if negative, assumes mod. |
| `!g lr`              | Long Rest                           |                                                     |
| `!g sr`              | Short Rest                          |                                                     |
| `!g ss`              | Show Remaining spell slots          |                                                     |
| `!g deathsave reset` | Reset death saving throws           |                                                     |

## Attacks, Checks, Saves and Spells

| Command                     | Description                                              | Notes                                                      |
| --------------------------- | -------------------------------------------------------- | ---------------------------------------------------------- |
| `!cast <spell_name> [args]` | Displays information about your D&D Beyond account link. | Common args: `adv`, `dis`                                  |
| `!attack [name] [args]`     | Roll an attack for the current character                 | If you can't remember the attack name use `/attack list`   |
| `!check <check> [args]`     | Roll a check for your current character                  | Common args: `adv`/`dis`                                   |
| `!save <skill>`             | Roll a saving throw for your current character           | Common skills: `str`,`dex`,`con`,`int`,`wis`,`cha`,`death` |

Examples:

- Roll to attack an enemy with your scimitar: `!attack scimitar`
- Roll to persuade with disadvantage: `!check persuasion dis`
- Make a Death Saving throw: `!save death`

## Lookup

| Command                       | Description        |
| ----------------------------- | ------------------ |
| `!spell <name>`               | Spell              |
| `![condition\|status] <name>` | Condition / Status |
| `!rule <name>`                | Rule               |
| `!feat <name>`                | Feat               |
| `!background <name>`          | Background         |
| `!class <name> [level]`       | Class              |
| `!classfeat <name>`           | Class Feat         |
| `!race <name>`                | Race               |
| `!racefeat <name>`            | Racial Feat        |
| `!subclass <name>`            | Subclass           |
