# Notes
* [Alex's Caves](https://modrinth.com/mod/alexs-caves) breaks [Distant Horizons](https://modrinth.com/mod/distanthorizons) LOD rendering.
* [Neruina](https://modrinth.com/mod/neruina) breaks server performance (100% CPU on idle).
* [Distant Horizons](https://modrinth.com/mod/distanthorizons) breaks server performance when generating LOD on server. Only Client side recommended.

# Todo
* Crafting is very laggy (maybe visual workbench)
* ```
  [main/WARN] [Every Compat/]: Chipped is installed. The mod on its own adds a ludicrous amount of blocks. With Every Compat this can easily explode. You have been warned
  [main/WARN] [Every Compat/]: Registered 19082 compat blocks making up 38.31% of total blocks registered
  [main/INFO] [Every Compat/]: Registered 19082 compat blocks making up 38.31% of total blocks registered
  [main/ERROR] [Every Compat/]: Every Compat registered blocks make up more than one third of your registered blocks, taking up memory and load time.
  [main/ERROR] [Every Compat/]: You might want to uninstall some mods, biggest offender was CHIPPED (3526 blocks)
  ```