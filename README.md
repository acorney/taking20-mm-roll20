## SUMMARY
These updated macros are based on the work done by Taking20 and their GM Cody to build a "monster manual" using NPCs and templates into Roll20. This speeds up gameplay and makes running NPCs much smoother for GMs. 

## BACKGROUND
These macros were originally published in 2016 on YouTube: https://youtu.be/rrbqdkGIa00

In the years since, Roll20 has updated their systems and some variables have been updated or depricated, so the original macros have a few syntax errors. 

I absolutely adored the idea of a drag & drop monster manual as soon as I saw the video. I couldn't find a revised set of macros, so I spent a day researching and updated them for 2019.

## PATCH LIST
- Fully replaced the "Saves" macro to create a simplified dropdown. Reference: https://app.roll20.net/forum/post/5591512/5e-ogl-universal-saving-throw-macro-updated-for-v2-dot-0 
- Fully replaced the "Spells" macros since spells are no longer stored in repeating tables (which was how the macro originally worked). The new macro matches the spirit of Cody's work (a macro per spell level). It utilises the new variables to properly call each spell per level, and allow for higher level casting. Reference: https://app.roll20.net/forum/post/5615072/5e-ogl-spell-list-macro/?pageforid=5615072#post-5615072
- Put commentary to "innate" spells. Some monsters may need you to tweak the character sheet to enable their spellbook.
- Updated Perception to use more straightforward math (Perception + 10 for passive). Doesn't take into account ADV/DIS. Reference: https://app.roll20.net/forum/post/4658021/npc-perception-slash-passive-perception-macro
- Updated "Stats" to remove a depricated npcd* duplicate variable reference
- Macros that have been updated have a ^ next to their header. If there's no ^, there's no update needed.

## ORIGINAL VIDEO WITH INSTRUCTIONS AND DEMONSTRATION 
https://youtu.be/rrbqdkGIa00
The instructions are 100% still accurate, just replace the use of those macros with this updated version.

## TAKING20
You can find Taking20 at [taking20.net](https://taking20.net "Taking20"), and all credit for the original idea & macros goes to them.

## ME
I hang out on Twitter mostly as [@corney](https://twitter.com/corney/ "@corney").
