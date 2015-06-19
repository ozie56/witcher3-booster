# witcher3-booster

Various tweaks for Witcher 3

* Enables debug console (Ingame toggle: `~` or `F2`)
* Enables free camera (Ingame toggle: `F1`)

### Console functions

Command dump with arguments: https://github.com/gamebooster/witcher3-booster/blob/master/global_functions_log.txt

Enum dump: https://github.com/gamebooster/witcher3-booster/blob/master/global_enums_log.txt

With the help by multiple people from this thread: http://forums.nexusmods.com/index.php?showtopic=2885919

* [`spawn('katakan', 3, 10, true)`](https://github.com/gamebooster/witcher3-booster/blob/d0f0c1e028cee21cefed096b6b56624485ef38a6/global_functions_log.txt#L464)
  * entity names in `patch0\bundles\gameplay\globals\resources\gameplay.xml` (decompress patch0.bundle via quickbms http://aluigi.altervista.org/papers/bms/others/witcher3.bms)
* `replaceplayer('Ciri')` - play with Ciri
* `addmoney(11)`
* `removemoney(11)`
* `additem('gwint_card_eredin_gold', 1)`
  *  item names in `patch0\bundles\gameplay\items` (decompress patch0.bundle via quickbms http://aluigi.altervista.org/papers/bms/others/witcher3.bms)
*  `eatapple()`
*  `god()`
*  `god2()`
*  `god3()`
*  `learnskill('sword_s10')`
  * names in `patch0\bundles\gameplay\abilities` (decompress patch0.bundle via quickbms http://aluigi.altervista.org/papers/bms/others/witcher3.bms)
*  `testpause()`
*  `testunpause()`
*  `likeaboss()`
*  `spawnenemy()`
*  `buffme(EET_KillerWhale, 60)` enum `EEffectType`
*  `addexp (1000)`
*  `winGwint(true)`
*  `setlevel(5)`
*  `addskillpoints(2)`
*  `killall(50)` range
*  `makeitrain`
* `stoprain`
* Usage: `xy(posX,posY)`
posX and posY are the coordinates you want to teleport to.
I found some coordinates in the startup.bundle file (game/fast_travel.csv)
Tip: active godmode to avoid falldamage after teleportation (god())

* `shave()`
* `settime(TIME)`
* `changeweather(WT_Heavy_Clouds)` - you can find a list of the available weather in startup.bundle file (/engine/environments/weather_YOURREGION.csv) e.g. snow in novigrad: `WT_Snow`
* `healme()` - you get full health
* `secretgwint()` - starts gwint game
* addbolts
* addcraft
* addsteelswords
* addsteelswords2
* addwolfdlc
* addsilverswords
* addsilverswords2
* addcrossbows
* addarmor
* addarmor2
* addpants
* addboots
* addgloves
* addsets
* addbooks
* addlore
* addlore2
* addfood
* adddrinks
* addtrophies
* addmiscaddhorseitems
* addupgrades
* addcraftingingre
* addCraftingItem
* learnallschematics
* addcraftedsteel
* addcraftedsilver
* addcraftedsteelrelic
* addcraftedsilverrelic
* addcraftedranged
* addcraftedboots
* addschematicsboots
* addschematicspants
* addschematicsgloves
* addschematicsarmor
* addschematicscomponents
* addschematicsupgrades
* addschematicsbolts
* addmutagens
* addmutageningredients
* addmutagenrecipes
* addrecipesoils
* addrecipesbombs
* addrecipespotions
* addrecipespotions2
* addherbs
* addkeys
* addvaluables
* additemfood
* additemalchemy
* additemcrafting
* additemleather
* additemmetals
* additemrunesupgrades
* additemmonstrous
* additemsprecious
* addjunk
* addjunk2
* addquestitems
* addquestitems2
* addquestitems3
* addtreasurehuntitems
* addcharacterdecorations
*  and many more... (You can find more in `cooked.redscripts` or `cookedfinal.redscripts`)
spawnt(*) for the following
01-09 (Witcher Hunters) 
61, 63, 65  (Bandits)
64, 68, 70, 73, 75, 80  (Novigrad Guards)
67, 77 (Thugs)
83, 85-90, 92-99 (Redanian Soldiers)
100-104, 106-126, 128-133 (Skellige Bandits)
134-135, 137-140  (Wild Hunt Warriors)
