# AvraeCheatSheet
__**Condensed Avrae Combat Cheatsheet**__

*For a full list of possible commands, use:*

`!help init`

**The DM begins combat by using**

`!init begin`

And at anytime, the DM may add 5e monsters to the intiative order by using:

`!init madd <monster name>`

Use !ma <monster name> to see the types of attacks the monster can do.

*Don't want to use a 5e monster? No problem!*

Have a look at https://critterdb.com/

*(you can use one someone else made, or make your own!)*

*Then use the following command to import a bestiary:*

`!bestiary import <url>`

*If you add a new monster to the bestiary, you can update Avrae by using:*

`!bestiary update`

**Players add themselves to combat by using:**

`!init join`

Yes, it's that easy!

*If for whatever reason you have advantage for initiative rolls, use:*

`!init join adv`

At __any time__ both players and the GM may use:

`!init list`

to see the initative order and status, such as:

Current initiative: 0 (round 0)

===============================

19: <player> <10/10 HP> (AC 13)

13: <monster> <Healthy> ()

12: <monster> <Healthy> ()

*And after a few seconds, the initiative summary will automatically disappear*

*To show the condition of only one player/monster, use:*

`!init status <name>`

Notes may be attached to a player/monster in the list by using:

`!init note <name> <note>`

Conditions may be attached in a similar way by using:

`!init effect <name> <effect name>`

__**To begin combat, either the GM or the highest-order initiative player uses**__

`!init next`

On *YOUR* turn you may:

__**1. Attack by using:**__

`!init attack <target name> <attack name> [optional commands]`

A common optional command is to roll with advantage:

`!init attack <target name> <attack name> adv`

Note that attacks can be shortened to:

`!init a <target name> <attack name>`

Avrae automatically rolls your attack die, compares it to the target's AC, and deducts the relevant damage from the target.

**To add a custom attack to YOUR character, use:**

`!attack create <attack name> -b <attack bonus> -d <damage dice>`

__**2. Cast a spell by using:**__

`!init cast <spell name>`

You can see a list of your spells by using:

`!spellbook`

or

`!sb`

Attack spells **DO NOT** automatically deduct HP from target. If, and only if, the spell lands (The GM may need to roll saving throws), either the player or the GM can deduct health from the monster by using:

`!init hp <monster/character name> mod +/- #`

*Avrae automatically knows all standard 5e spells. To add custom spells:*

Visit https://avrae.io/dashboard/homebrew/spells and make a spell tome for your character.

Add spells, and BE SURE TO SAVE using the save icon.

Add the spells, spelled exactly, to your character sheet in gSheet page 2, or D&D Beyond.

Use !update in Discord

Use !spellbook to confirm spell is listed.

__**3. Roleplay**__

No help text needed.

__**4. End Your Turn**__

On YOUR turn, you may use:

`!init next`

The GM may use this at any time. The GM may also go to a specific point in the initiative order by:

`!init goto <target>`

__**To End Combat**__

The GM uses:

`!init end`

then: yes
