# GameplayModsCollection
 Für die deutsche Version des readmes, bitte [hier](readme_german.md) klicken.

 This is a collection of my standalone gameplay mods for Anno 1800, bringing new features to the game or modifying existing ones.

 If you like this mod and want to support me, feel free to share it with your friends. You can also buy me a coffee at Ko-Fi (yes, I want to raise my coffee consume to Investor's height!)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W8L558T)

## How to use

- Automatic install using the Anno Mod Browser, available from the main menu of your Anno 1800 game.
- Either use [iModYourAnno](https://github.com/anno-mods/iModYourAnno/releases) mod manager or know [how to install mods manually](https://github.com/jakobharder/anno1800-mod-loader#mods).
- If you download the mod manually, use the archieve from [GitHub releases](https://github.com/Taludas/GameplayModsCollection/releases). Don't download the whole repo!
- Select the relevant mods and drag them to your 1800 Mod Folder or use the iModYourAnno Anno Mod Manager to install.

***These Mods are savegame-compatible. Please use the iModYourAnno Anno Mod Manager for individual mod customization. Several mods have multiple versions which can be toggled on and off with iMYA as well.***

## Mod Images
You can find a gallery of images from my mod [here](docs/).

## Changelog
<details>
    <summary>Patch Notes Version 1.7.0</summary>

* Updates:
  * rework Taludas Shared Products mods into individual sub-mods

</details>

<details>
    <summary>Patch Notes Version 1.6.2</summary>

* Fixes:

  * [Coffee and Tobacco in Enbesa]:
    * Fix error with wrong mod dependency in modinfo.json file

</details>

<details>
    <summary>Patch Notes Version 1.6.1</summary>

* Updates:

  * [Coffee and Tobacco in Enbesa]:
    * Add shared production amount infotip overhaul by Serp.
    * Remove shared infotips by Kurila.
    * Adjust Coffee Roasters consumption and production according to the new possibilities of Serp's mod.

  * [True Jam Experience]:
    * Update shared production amount infotip overhaul by Serp.
</details>

<details>
    <summary>Patch Notes Version 1.6.0</summary>

* Updates:
  * All updates suggested and coded by @Qurila THX for your work on keeping these mods up to date!

  * [Museum, Zoo and Botanical Garden in Enbesa]:
    * Zoo, Museum, Botanical Garden in Enbesa are now moved to the "Culture" Build Menu!
    * Reduced need of new GUIDs by using TextOverride where applicable.
    * Fluff Texts for Buffs are now always showing both possible effects in the other two regions.
    * Enhanced compatibility with "Alkaloid Collection" and "Fam's Enbesan Flora"
    * Coffee and Tobacco fertilities will only be used as a buff, if my "Coffee and Tobacco in Enbesa" mod is active, otherwise it will be Teff and Indigo.

  * [Alkaloid Collection]:
    * Enhanced compatibility with "Museum, Zoo and Botanical Garden in Enbesa" and "Fam's Enbesan Flora"

  * [True Jam Experience]:
    * Updated shared products to newest version.
    * Add shared production amount infotip overhaul by Serp.
    * Remove shared infotips by Kurila.
    * Adjust Jam Factory consumption and production according to the new possibilities of Serp's mod.
    * Enhanced compatibility with Jakob's New World Cities Jam production and Lion's OW chocolate production.
</details>

<details>
    <summary>Patch Notes Version 1.5.0</summary>

* Additions:
  * [Glasshouses for Orchid Farms]: change moduleowner property to work like animal farms with freely buildable farm modules instead of required adjacency.
  * [Glasshouses for Orchid Farms]: add polish translation

* Fixes:
  * [Museum, Zoo and Botanical Garden in Enbesa]: fix an issue where the Botanical Garden in the OW would show four sets from various other cultural buildings on empty pages of the second page when using together with Enbesan Flora from Fam.
  * [Burrito Boom]: fix an issue with the production buildings of this mod being attackable by ships from the coast.
  * [Coffee and Tobacco in Enbesa]: fix missing Infotext-Description for Demand/Production of the Enbesan Coffee Roaster.
  * [Coffee and Tobacco in Enbesa]: fix issue where default mode of the mod is set to "farms only", you now get the "light version" as default, as intended from the beginning.
  * [Coffee and Tobacco in Enbesa]: fix wrong "IncompatibleID" modinfo.json entry

</details>

<details>
    <summary>Patch Notes Version 1.4.0</summary>

* Additions:
  * New Mod "Glasshouses for Orchid Farms", replacing the usual Orchid fields with actual glasshouses!
  * Russian Translations and a new skin for Lady Marmelade (True Jam Experience), thanks to @DrD_AVEL
  * Adjustments for all mods to the new features of iModYourAnno v0.5 (new images, default options are toggled automatically in the tweaking tab). ***WARNING***: Adjust your Tweaking options in iMYA before you continue playing, because those will be lost after update to v0.5!

* Fixes:
  * True Jam Experience: Fixed issue with unlock triggers in Sandbox gamemode

</details>

<details>
    <summary>Patch Notes Version 1.3.1</summary>

* Fixes:
  * Burrito Boom: Guacamole Kitchen and Tortila Mill can be improved by Electricity if you have the New World Rising DLC.

</details>

<details>
    <summary>Patch Notes Version 1.3.0</summary>

* Additions:
  * Free Farm Fields Placement was moved over from The Wholesome Hacienda Overhaul mod. Fixed load order issues by using LoadAfterIds, so it always loads at the bottom of the loadorder and considers most mods from other mod authors.

</details>

<details>
    <summary>Patch Notes Version 1.2.2</summary>

* Fixes:
  * Coffee and Tobacco in Enbesa: Fixed Japanese localization file name
  * Forest Glass: fix default production buff to be active on the Glass Hut

</details>

<details>
    <summary>Patch Notes Version 1.2.1</summary>

* Fixes:
  * High Life Souvenirs: Hot fix for accidentally default skip options in assets, leading to problems with iMYA tweaking and not active mod when used without customization
  * Burrito Boom/Forest Glass: fix ActionBuffs to be triggered on Session Enter to include Cape and possible new NW session
  * Coffee and Tobacco in Enbesa/Arctic Zoo/True Jam Experience: fix accidently included iMYA tweak files leading to problems with iMYA tweaking
  * Coffee and Tobacco in Enbesa: fix issue with multiple coffee build menu entries when using all of the sub mods together (without iMYA tweaking f.e.)
  * Coffee and Tobacco in Enbesa: fix coffee production chain not showing cotton cloth in OW/Arktis chain if using full version of the mod

If you already used iMYA to tweak the mods, you have to remove the stored settings .json files for the respective mods form iMYA storage location: Go to .../Anno 1800/.imya/tweaks/... and remove the .json files for the mods in description: '[Gameplay] Coffee and Tobacco in Enbesa (Taludas).json', '[Gameplay] High Life Souvenirs (Taludas).json', '[Gameplay] The True Jam Experience (TaludasKurilaLordys).json', '[Gameplay] The Alkaloid Collection (Taludas).json' and '[Gameplay] The Arctic Zoo (Taludas).json' while iMYA is closed. Otherwise the changes by these fixes might be overwritten by the stored iMYA settings.
</details>

<details>
    <summary>Patch Notes Version 1.2.0</summary>

* Added Support for new modloader features and iMYA customization after GU17 to all mods:
  * Coffee and Tobacco in Enbesa is now reduced to one mod, which needs customization with iMYA. There you have the option to choose your desired version of the mod (using cotton cloth in NW, using Linen in NW, not use any packaging, only farms)
  * HighLife Souvenirs (Gold in a manufactory)/LowLife Souvenirs (using Brass in a assembly line): Choose which version you want to use (even both are possible!)
  * Arctic Zoo: Choose the strength of the buffs for arctic animal sets.
  * The Alkaloid Collection: Choose the strength of the buffs for the alkaloid set.
* Additions:
  * Burrito Boom (Production Chain Overhaul Tortillas)
  * Forest Glass (Production Chain Overhaul Glass)
  * High Life Souvenirs (Production Chain Overhaul Souvenirs)
  * Slippery Soap (Production Chain Overhaul Soap)
  * True Jam Experience (Production Chain Overhaul Jam)
* Fixed minor bugs with Coffee and Tobacco in Enbesa, Arctic Zoo
</details>

<details>
    <summary>Patch Notes Version 1.1</summary>

* Added Support for GU16 to all mods.
* Fixed minor bugs with Coffee and Tobacco in Enbesa
* Fixed File missplacment with Alkaloid Collection and Museum, Zoo and Botanical Garden in Enbesa, where the mods had the assets file of the opposite one.
</details>

<details>
    <summary>Patch Notes Version 1.0</summary>

* Added Support for GU15 to all mods.
* Fixed minor bugs with Coffee and Tobacco in Enbesa, where the tobacco plantation couldn't be build due to missing build menu entry as well as farms and production buildings not being buffed by influence buff Captain of Industries.
* Fixed minor bugs with Arctic Zoo, where sometimes artic skinned enclosures would be visable in the Old World and empty normal enclosures in the Arctic.
</details>

## Mod Description with main feature overview
**Please remember to always check the Changelog to see the new or changed features.**


![Banner](https://user-images.githubusercontent.com/64583643/191513547-7a34b7d2-1353-4298-9828-e12335bc20f9.png)
### Arctic Captains
This mod adds 6 new Captains to command your Airships and one new specialist for the Salvager. The Items are only available in the Arctic, but can fit your new and shiny aluminium ariships from the New World as well!

For more Details see below and the attached pictures.

<details>
    <summary>Item stats and sources</summary>

**Legendary**
* Sir John Faithful, Reinstated Admiral of the Lost Expedition: +50% Speed, -100% Cargo Slowdown, +100% Loading Speed, -75% Maintainance, +25% LoS -> Reward for completing the Quest around the Lost Arctic Expedition and Lady Faithful. Tier 3 Rescue Mission in the Arctic, North America, Northern Europe
* Ming Shu, Sharp tongue of the eastern capital: +25% Speed, -40% Maintainance, -50% Trade Prices -> Trader Arctic
* Jürgen Vogel, Lifter of flying crates: -100% Cargo Slowdown, +75% Loading Speed -> Trader Arctic
* El Presidente, Globetrotter par excellence: +25% Speed, +100% Salvage Scrap Amount, Increased chance of finding epic and legendary machinery -> Trader Arctic
**Epic**
* Francis Crozier, Aerial Trade Specialist: +10% Speed, -25% Maintainance, -25% Trade Prices -> Trader Arctic
* Franca d'Artois, Believer of Speed: +25% Speed -> Trader Arctic
* James Fitzjames, Expert on the pulley:  -60% Cargo Slowdown, +40% Loading Speed -> Trader Arctic
</details>

-----

![banner](https://user-images.githubusercontent.com/64583643/191513574-0dab9ff9-2be5-4141-a64b-489fbd6c25c9.png)
### Coffee and Tobacco in Enbesa
This mod enables you to plant Coffee and Tobacco in Enbesa and modifies the Coffee Production chain.
Coffee and Tobacco fertility are distributed on Enbesan Islands at the Game Start. So if you want the fertility on the whole island, you have to start a new game.

**If you don't want to start a new game**, you can use items to provide fertilities on your island. Those items can be bought at Ketemas harbour.
**OR** you use the Research Institute to change the fertilities of the Islands.
**OR** you can use the Anden Set from my botanical garden in Enbesa mod to get the Tobacco fertility and the Enchanted Set to get the coffee fertility.

I modified the Coffee Production chain to use Cotton Fabric for NW and Linen Cloth for Enbesa as a way to show that the coffee is packed up in sacks before export to make it a little bit more difficult to spam Coffee.

There are four versions:
* Normal version with Coffee Roaster requiring linen or cotton cloth respectively.
* Light version where the Coffee Roasters in Enbesa use linen cloth only.
* Super Light version where Coffee Roasters are not altered at all.
* Farms Only. Does what it says on the label.

-----

![banner](https://user-images.githubusercontent.com/64583643/191513621-2578593d-1aa8-4e19-8b14-8a04278f3f0c.png)
### Museum, Zoo and Botanical Garden in Enbesa
Bring some culture to your colony! Build zoo, museum and botanical garden in the Land of Lions to get some nice bonus effects from it and beautify your settlement!

HIGHLY RECOMMENDED:
* Fam's Enbesan Flora from Fam's Enbesan Flora
* Culture Modules as Ornaments from Cultur Modules as Ornaments
* Coffee and Tobacco in Enbesa from Coffee and Tobacco in Enbesa
* Culture Module placement by Radius from Spice it up
* No cultural Module Limits from Spice it up
* Unlimited Botanic Ornaments from Spice it up
* World Fair Items from Spice it up

THANKS: To Fam and Taubenangriff for letting me include their features in my mod and general support.

FEATURES:
* Build Zoo, Museum and Botanical Garden in Enbesa
* All sets are equippable, some even have unique buffs in Enbesa.
* All ornaments are buildable to decorate your Enbesan city.

If you already collected the items and build the buildings the new buffs influence, it is likely that you'll have to move those buildings by a few tiles to get the buffs working properly and/or reequip the set items.

<details>
    <summary>Unique Enbesa set buffs</summary>

**Museum Sets:**
* Aegean Cultures: Affects Musicians' Court
* Bronze Age: Affects Wanza Woodcutter and Clay Collector
* Lost Tribes: -5% Clay Pipe Consumption
* Roots of Enbesa: Affects Elder Residences as well

**Zoo Sets:**
* Cordillera Set: Affects Shepherd Residences as well
* Taiga Forest: -5% Dried Meat Consumption
* Proud Savannah: Effects Goat and Sanga Farms
* Great Coral Reef: Affects Elder Residences as well
* Luminaries: Affects Musicians' Court
* Miombo Woodlands: Affects Wanza Woodcutter
* Polar Circle: Affects Embroiderer and Tapestry Maker as well

**Botanical Garden Sets:**
* Amazonas Garden: Adds Hibiscus fertility
* Anden Garden: Adds Tobacco fertility
* Spiritual Garden: Adds Coffee fertility
* Orient Garden: Adds Spices fertility
* Subalpine Garden: Adds Bees fertility
* (Enbesa Plateau Garden: All crop farms: Additional Output Cotton 1/5 and Cocoa 1/10)
* (Beautiful Branches: Pipe maker and Pottery: Replace input goods: Wanza Wood instead of Clay, Additional Output Wood Veniers 1/10)
</details>

-----

![banner](https://user-images.githubusercontent.com/64583643/191513654-564f0dcb-ef41-4271-a3ca-6385a25d7443.png)
### The Alkaloid Collection
Been missing the typical plant based consumption goods of the 19th century? Look no further, at least I got you the plants!

HIGHLY RECOMMENDED:
* Fam's Enbesan Flora from Fam's Enbesan Flora -> Get the plants easier through buying them at Ketemas harbour!
* Museum, Zoo and Botanical Garden in Enbesa from Zoo Museum and Botanical Garden in Enbesa

THANKS:
To Fam for permission to make this mod compatible with his Enbesan Flora mod.

FEATURES:
* 6 new and very special Plants to display at your Botanical Garden.
* One new Set with a unique bonus Buff.
* Finally some Opium xD

<details>
    <summary>Set Items, sources, buffs</summary>

Set consists of
* Kola Tree
* Betel Palm
* Cath
* Yohimbe Tree
* Coca
* Opium Poppy

Unique Set Buff:
* OW: All residences -5% Schnaps, Beer, Rum, Champagne, Cigars, Coffee, Clay Pipes, Hibiscus Tea, Cognac, Mezcal +10 happiness, -50% effect from extra work time, +50% illness risk, +25% riot chance
* NW: All residences -5% Schnaps, -10% Beer, -5% Rum, -15% Cigars, -10% Coffee, -10% Mezcal +10 happiness, -50% effect from extra work time, +50% illness risk, +25% riot chance
* Enbesa: All residences -10% Goat Milk, -10% Hibsicus Tea, -20% Clay Pipes,  +10 happiness, -50% effect from extra work time, +50% illness risk, +25% riot chance

How to get the Plants:
* Betel Palm: Ketemas Habour, Kahina habour, Qing/Bente Drops, World Fair, Shephard Quest, Expedition
* Cath: Ketemas Habour, Kahina habour, Qing/Bente Drops, World Fair, Elder Quest, Expedition
* Kola:  Ketemas Habour, Kahina habour, Qing/Bente Drops, World Fair, Shephard Quest, Expedition
* Yohimbe: Ketemas Habour, Kahina habour, Qing/Bente Drops, World Fair, Elder Quest, Expedition
* Coca: Samento Habour, Jornalero Quest, Qing/bente Drop, World Fair, Expedition
* Papaver: Elder Quest, Bente/Qing Drop, World Fair, Expedition
</details>

-----

![banner](https://user-images.githubusercontent.com/64583643/191513677-1c0dc202-70f0-486b-8b46-e2eb5b012991.png)
### The Arctic Zoo

Build a Zoo in the Arctic. Display local animals that are suited for the rough climate. Get unique bonuses from these sets.

HIGHLY RECOMMENDED:
* Museum, Zoo and Botanical Garden in Enbesa from Zoo Museum and Botanical Garden in Enbesa

THANKS:
To Jakob and Taubenangriff for helping me out with Nates airship's Props positioning and animations! You are the best!

FEATURES:
* Build a snowy Zoo in the Arctic Region.
* Display 9 different animals, adopted to the cold in unique enclosures.
* Get unique buffs and a special new airship from completing the 2 available sets.
* Extra filter for cultural items at Arctic kontors.

If you already collected the animal items and build the Hangar monument, it is likely that you'll have to move the hangar by a few tiles to get the buffs working properly and/or reequip the set items.

P.S.: Please don't bring other animals to the arctic, they will suffer a very horrible cold death :P

<details>
    <summary>Buff spoilers</summary>

* Arctic Tundra:
    - Arctic Buff: Reduces the Build Cost and Build Time of all airships -50%
    - OW/NW/Enbesa Buff: +15% productivity and Additional Output Parkas 1/15 for Framework Knitters, Fur Dealer, Poncho Darner, Bombin Weaver, Tailor's Shop, Bootsmaker and Embroiderer
* Polar Circle:
    - Arctic Buff: Build Nate's Air Freight Ship: Customized Model, 6 slots at 50t each, 3 item sockets, little bit slower than normal airship and slightly more expansive.
    - OW/NW Buff: Oil refineries Additional Output 1/50 Arctic Gas.
</details>

-----

![banner](https://github.com/Taludas/GameplayModsCollection/assets/64583643/4e523da2-01ab-42de-8146-4c75e0a6e991)
### Burrito Boom

Craving a flavor-packed fiesta for your taste buds? Look no further than our sizzling, mouthwatering burritos!

Picture this: tender, marinated meat, grilled to perfection and paired with creamy, vibrant guacamole, all nestled together in the blanket of a warm, soft tortilla.

Your citizens have stumbled upon an old family recipe, using regional ingredients, which together taste so good, that people from all over the globe come to your colony to taste this flavor paradise. The new ingredients are:
- Meat (uses 'Cattles need to be butcherd' Mod if present)
- Guacamole made from fresh Avocado and fine-tuned with hot spices (requires LoL or Seeds of Change/Hacienda).
- Tortillas made from corn, extracted using an old technique called Nixtamalization, which requires pot ash.

In return for your increased efforts, more people will come to your town due to the enormous popularity of the new recipe (+5 inhabitants for Obrero and Artista residences from Burritos, standard plus 50% Productivity for Burrito Maker).

Needs either the Land of Lions or Seeds of Change DLC for acquisition of spices.

-----

![banner](https://github.com/Taludas/GameplayModsCollection/assets/64583643/5f6533e3-3baf-47cb-9024-f8e6679ef628)
### Forest Glass

Also known as Waldglas in German, refers to a type of glass that was produced during the late medieval and early modern periods in Europe, particularly in the regions of Germany and Bohemia. It is characterized by its distinct green color and often exhibits a slightly crude or uneven texture.

Forest glass was primarily used for making drinking vessels, bottles, and window panes. Its production was a significant industry in the forested areas where it thrived, hence the name 'forest glass'.

Ingredients:
- Quartz sand
- wood ash to provide potash (K2CO3) as flux.

The green color of forest glass is attributed to impurities present in the raw materials, particularly iron oxide from the sand and plant ashes used. These impurities, combined with the specific firing conditions in the forest glass production, resulted in the distinctive green hue.

To compensate the increased resource input, there are several buffs in place:
- a standard 10% production boost on the glasshouse.
- a near field buff coming from the glasshouses and boosting potash and woodcutter buildings in its vicinity (+50% Productivity).
- a return buff from potash and woodcutter buildings to increase productivity of the glasshouse (+10% Productivity per building).

This ensures a good synergy effect, if the buildings are built in close range, as it is historically correct.

This mod will automatically modify other mods using the vanilla glassworks/adding new production chains using the glass chain.

-----

![banner](https://github.com/Taludas/GameplayModsCollection/assets/64583643/07f6de00-0ab6-451b-af05-3ad77238aa42)
### High Life Souvenirs / Low Life Souvenirs

After the introduction of the first form of modern era Plastics in the DLC 'High Life', the Production Chain for Souvenirs felt a little lackluster. Obviously the use of Campher Wax and Cotton resembled the ingredients of celluloid plastic. But why use this anymore after the introduction of the celluloid ware with High Life?

To spice things up a little, I reimagened the Souvenirs to be made of Celluloid for the stand, Gold for the snowflakes and model inside and Glass for the bulb.

You can now also sell the Souvenirs to your Tourists not only in the Hotels directly but also in little Souvenir Stands around the place. This reduces overall sells in the Hotels (-50% Need reduction), gives extra money and attracts a lot of new tourists (+50 Tourists from Souvenirs, +5% visit chance on the Tourist Peer)!

If you use iMYA you can choose between two variants of the mod. One with expansive souvenirs made form gold in a artisan workshop (High Life Souvenirs) and the other with cheap ones made in an assembly line out of brass (Low Life Souvenirs). You can also activate both sub-mods to get the full experience.

-----

![banner](https://github.com/Taludas/GameplayModsCollection/assets/64583643/9e2dd08e-0606-4473-93c0-f8797fbf5ceb)
### Slippery Soap

Historically soap was the first modern product used for cleaning of body and cloths. It was made by boiling animal fat in an alkaline solution over several hours. In Anno this process is poorly represented.

Therefore I included Potash into the production chain as a early version of the alkaline additive. Potash can be obtained by burning wood and extracting the remains with water.

Hope this new soap recipe makes it a little bit more realistic for you!

-----

![banner](https://github.com/Taludas/GameplayModsCollection/assets/64583643/7cfce94a-9444-46e6-8682-6d8d18220e4e)
### The True Jam Experience

Ever wondered why Jam grows directly on trees in Anno 1800?

Because they chose the simple way. But I don't like it the simple way. So I took the idea and assets from Lrds42 and made a separat mod that only adds a new Jam Production Chain based on Cherries, Sugar and Glas.

You'll need 1t of Cherries/min, 0.5t of Sugar and Glass/min to produce 1t Jam/min.

The Jam manufactory is now a Multifactory so we can expand it in the future with different Jam flavours.

To get a nice boost on the new production facility there is a special item: 'Marlene - Mother of Marmelades'. She is buyable at Eli.

Compatibility between Lordys, Kurilas and my mod is provided by [Kurila](https://github.com/Qurila)! Big Thank you for that!

-----

![banner](https://user-images.githubusercontent.com/64583643/170326213-2c3aafcc-ed65-4fd2-82ce-a21f3b67d23d.png)
### Free Farmfield Placement

(Moved over from Wholesome Hacienda Haul)

This mod is an update of the mod "[Free Farmfield Placement](https://www.nexusmods.com/anno1800/mods/26)" by Finnem. The fields of all farms and animal farms incl. Hacienda farms, as well as all modded farms (e.g. farms from 'The Wholesome Hacienda Overhaul' or Jakob's mods) can now be placed freely in their radius. The original mod is no longer required. The radius of plant, animal and Hacienda Farms can be adjusted with the iModYourAnno Modmanager to fit your own playstyle.

-----

![image](https://github.com/Taludas/GameplayModsCollection/assets/64583643/1e306203-8d36-4316-a197-15aa37d923e8)
### Glasshouses for Orchid Farms

This little mod changes the not very accurate farm fields of the Orchid Farm to one that actually could make sense. Orchids are usually parasitic plants, growing on trees. So them growing in plain farming soil is not really close to reality. Also the usage of a Tractor to harvest the Orchids is as sensitive as the use of a chainsaw on those precious plants.

Therefore, this mod changes the one tile fields to actual Greenhouses, reducing the number of field module needed, but also getting rid of the tractor boost.

***Warning***: Before installing, make sure your Orchid Farms (or at least their fields) have been deleted. Otherwise you might get funny clipping issues and non removable fences which previously sourrounded your fields!

If you use the Hacienda Overhaul Mod, note that the Orchid Fields for the Hacienda Farm will not change, due to the mechanic behind the recipe building.