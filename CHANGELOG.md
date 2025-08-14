## [Major.Minor.Patch] - DD/MM/YY

## [Unreleased]

## [1.0.0] - 17/08/24

- Initial release

## [1.0.1] - 20/08/24

- Reorganized some syntax to take priority over others
- Removed some redundant syntax
- Optimized country tag syntax matching
- Added event ID syntax coloring
- Added Rainbow CSV compatibility

## [1.0.2] - 21/08/24

- More example images
- Coloring for State/Province IDs
- Additional syntax highlighting for missing triggers, scopes, and effects
- Reorganized some other syntax stuff again
- Renamed 'redtheme's file to be consistant with Dark and Light theme file names, even though it will probably be deleted
- Added some more coloring to Dark theme that was missing

## [1.0.3] - 21/09/24

- Additional highlighting syntax
- Additional coloring for said highlighting syntax

## [1.1.0] - 12/04/25

- Replaced `keyword.control.equipment.hoi4` with `keyword.control.items.hoi4`, now including resources and buildings as well
- A few more random highlighting syntax
- Removed redundant and incorrect syntax
- Added `user.tmLanguage.json` which allows the user to more simply add their own syntax to existing syntax
- Changed `keyword.control.tag.hoi4` and `constant.rhs.tag.hoi4` to include `letter-letter/number-letter/number` tags instead of just `letter-letter-letter`
- Added `!` and `;` to `comment.hoi4` as they also can be used for comments according to Blue from the HoI4 Modding Den
- Remove redtheme because I have completely forgot what that was all about and it seems completely unfinished
- *Finally* finished light theme!

## [1.2.0] - 12/04/25

- Add (theoretically) all effects, modifiers, and triggers from the base game documentation files
- Added `keyword.control.modifiers.hoi4` to separate modifiers from effects, however shares the same color still
- Remove a bunch of other erronous syntax

## [1.2.1] - 12/04/25

- Added back a handful of missing stuff I accidently removed
- Fixed comments not working

## [1.3.0] - 19/04/25

- Added an assortment of missing strings for coloring
- Added coloring to `.yml` localization files, including special highlighting for line breaks, escaped quotes, and `§` for colored loc
- Attempted changes on light mode to make it better (?), still would not recommended

## [1.3.1] - 20/04/25

- Fixed a bug where highlighting in `.yml` files would break if you included a colon after the loc string
    - Exception: If the colon is the last charcter in the line it treats it like the lang def (e.x. `l_english:`)

## [1.3.2] - 20/05/25

- Adjusted the way tags are highlighted to stop 3 number states being highlighted with the color of tags
- Added `bypass`, `bypass_effect`, `visible`, and a few other things to highlighting as I managed to miss those somehow

## [1.3.3] - 03/07/25

- Missed from change log some how, `keyword.control.other.hoi4` and `keyword.control.definition_tokens.hoi4` updated.

## [1.3.4] - 14/08/25 | Marketplace Update

- Updated `package.json` to point to new repo location at https://github.com/STupidProductions/HoI4-Syntax.
- Updated [How to add custom syntax?](#how-to-add-custom-syntax) to actually point to the correct version location insetad of `stupidlord.stupid-hoi4-syntax-1.1.0`.