![0_banner_charsheet](https://github.com/user-attachments/assets/58d854ae-5cba-4b1a-8bff-c86800f75896)

### Auto-Character Sheet that tracks, calculates, and auto-fills character stats for DnD 5E.

A fully-local character sheet and database styled as a parchment journal to record the tale of your character.

**FEATURES**::
- **Character Sheet**: - dashboard for a complete view of essential gameplay info.
- **Inventory**: - keep track of all the items you carry, wear, and are attuned to.
- **Spellbook**: - spellcasting stats, prepared & known spells, & available spells from your class's spell list.
- **Statistics**: - calculations for attributes, proficiencies, HP, AC, Speed, Attack & Damage rolls.
- **Database**: - pull game data from a separate spreadsheet containing 500+ Spells, Class Abilities, Races, Weapons/Armours, Backgrounds, and more.
- Allows creation of multiples characters where data is only required to be updated in the database from which all character sheets access.

I have tried a few different digital character sheets but none of them had everything I was looking for.
I wanted a character sheet that:
- Auto-calculates functional gameplay stats and displays it all nicely accessible.
- Has any character info I need readily available so I don't have to check the wiki as much.
- Fits the medieval fantasy aesthetic of DnD. (Like my tea-stained custom physical character sheets ^.^)
  
So here is my attempt at a character sheet that fulfills them all.


**INSTRUCTIONS**::
1. Keep both the CharacterSheet and Database spreadsheets together.
2. Open the 'Auto_Character_Sheet.ods' (you can rename it to your character's name)
3. The four main sheets are 'Character', 'Inventory', 'Spells' and 'Calculations'. The last three sheets are the database which you can consult for class abilities, or spell effects. (might make this more easily accessible..)
4. In 'Character', the stats you can edit are selectable, auto-calculating stats are not.
5. Fill in the all you can for a new (or existing) character. Eg. Name, Background, Alignment, Class, Subclass, Experience. Level is determined by EXP, so if your class is level 3, enter min 900 EXP.
6. To change portrait, unlock 'Character' at bottom left by right-click -> Protect Sheet -> right-click Portrait -> Replace. Select your image. (edit it first to be square, eg. 800 x 800 px). Relock 'Character' so no formulae are accidently editted. Protect Sheet -> Ok.
7. There are some extra tables around that you can edit and use for what you need. Eg. Feats, Invocations, Piety.
8. Class Abilities cells might be cut off for different abilities. To fix, unlock sheet -> highlight abilties cell rows (click-drag on row 48 down) -> double-click on line between rows (inbetween '48' & '49' -> cells should widen to show all ability description. Repeat for 'Racial Traits'.
9. In 'Inventory', you have your list of items carried - ITEM, QTY, VALUE. Your character's worn equipment for each body part. Your gold. Your attuned items.
10. In 'Spells', enter your known/prepared spells from your class spell list below. (Some spells might not show, like subclass extended spell list)
11. In 'Calculations', you can enter/edit values in the pale tan cells as per your character.
12. To make a new character, just copy 'Auto_Character_Sheet.ods' and rename it to your new character.

Note:
- This is still a WIP
- DnD has so many aspects that including everything would be unlikely.
- Some data may be missing from the database such as certain races, their abilities, spells from class spell list, etc..
- If you want a specific race, class, background, etc. let me know and I may add it in.


**REQUIREMENTS**::
- LibreOffice 7.3


**ISSUES**::
- I found that sometimes the array formulae bug out when the spreadsheet is opened. They can be fixed/refreshed by highlighting the array formula cell area -> edit the formula slightly (put "error" inside last "") -> CTRL+SHIFT+ENTER -> change formula back to what it was -> CTRL+SHIFT+ENTER. Now all values should display properly.
- The portrait can't perfectly align to the cell consistently, at every zoom percent, it's alignment changes :/


**PLANNED FEATURES**::
- Weapon & spell attacks -- & calcs
- Spells prepared checkbox & data validation dropdown.
- Equipment proficiency checkbox
- Saving throw proficiency - add additional in calcs

- Avg dmg of attack calc
- Combat combo section
- Playstyle bonus action & reaction options section
- Ability tables prettify

- Components pouch inventory
- Character lore section


**CREDITS**::
- A large part of the data was borrowed from other DnD digital character sheet projects. Credit to them for getting so much of the DnD5e wiki data into a useable form.
- Character portrait by Zumstein on DeviantArt.


Made with ❤️ by foxton_
