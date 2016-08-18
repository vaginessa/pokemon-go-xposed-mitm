#Pokemon Go (c) Man-in-the-middle attack
##Brief
Uses XPosed framework to intercept web communications of app and modify out- and inbound packages.<br>
Internally uses POGOProtos compiled to Java. See root build.gradle for instructions and build tasks.<br>
##What it can do now
Intercept packages going from client to server, parse them with protobuf; all without breaking actual communications.<br>
Intercept packages going from server to client, and parse them too, with remembered request types.<br>
Branch simple - does simple hack to put IVs into pokemon nickname.<br>
Branch simple - does simple hack to set driving warning speed to one mach, however app freezes when it sees it.<br>
##What is planned
###Branch simple
Integrate settings between screen and app.<br>
###Branch master
Merge from simple.<br>
Clean up class composition.<br>
(Maybe) hack outbound with streams too.<br>
Grandeur plan - use some embedded scripting to allow different data modifications without recompilation. For this POGOProtos will be compiled to scripting language.<br>
##Resources and projects used
* [POGOProtos](https://github.com/AeonLucid/POGOProtos) by [Mike](https://github.com/AeonLucid)
* [Launcher icon generator](https://romannurik.github.io/AndroidAssetStudio/index.html) by [Roman Nurik](https://github.com/romannurik)
* [Pokeball icon set](http://tamarinfrog.deviantart.com/art/All-Poke-Balls-Free-Icons-368996730) by [TamarinFrog](http://tamarinfrog.deviantart.com/)
