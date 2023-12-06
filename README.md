# wotlk-heirlooms-v1
More heirlooms for wotlk private servers 3.3.5 - Azerothcore - Cmangos

This project adds heirlooms for all slots and classes.
The project is only using existing dbc files so there are currently limitations.


How to install
-Simply download the SQLs.
-Use Heidi > File > run sql select the downloaded files.
-Close the game server and re launch.
-Close the game client, Delete the cache file in the client and re launch game.
-as a gm use .additem 90001 to add item refer to spread sheet for item list.

Use Kiera3 to modify as desired, refer to spreadsheet.

How to un-install
-Simply delete all items above 90001 in the item template or delete the item template and rebuild it.


Bugs
- Q mark shows up on newly spawned item however once the item is equipped the icon changes.
-  Shields have no Block value.
-  No defence rating on any gear as there in nothing in the existing dbc's.
