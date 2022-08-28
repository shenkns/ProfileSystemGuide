# Profile System Guide

```Profile System Plugin```
![Gallery-1-Logo.png](/Gallery-1-Logo.png)

```Profile System has Managers: three default(Stats, Data, Shop) and custom user managers. Manager - autonomous Profile object with easy using Profile System.```
![Gallery-2-Managers.png](/Gallery-2-Managers.png)

```Data manager help to work with DataAssets, you can get them using Class or Tag, in Profile System DataAssets added Custom Data array to handle any information in DataAssets of one class.```
![Gallery-3-Data.png](/Gallery-3-Data.png)

```Stats Manager controls Stat objects: three default(Info - for simple variables, Currency, Inventory) and custom user Stats. Stat - serializable object for easy Save-Loads, in Stat class implemented Pre-Save and Post-Load events to add custom logic.```
![Gallery-4-Stats.png](/Gallery-4-Stats.png)

```Info Stat can handle any amount of Int, Float and String variables, Currency Stat has functions to manage user currencies and dispatchers, as currency it uses Currency DataAsset. Inventory handle user items, add/remove them and has event dispatchers to bind.```
![Gallery-5-InfoStat.png](/Gallery-5-InfoStat.png)
![Gallery-6-CurrencyStat.png](/Gallery-6-CurrencyStat.png)
```Inventory```
![Gallery-7-Inventory.png](/Gallery-7-Inventory.png)
![Gallery-8-InventoryFunctions.png](/Gallery-8-InventoryFunctions.png)
![Gallery-9-InventoryDelegates.png](/Gallery-9-InventoryDelegates.png)

```Shop Manager handle Shop Items, there implemented functions to get Item using Class, Category, Tag, ID. You can manage Shop Categories and bind to Purchase dispatchers(for Shop and for every Item). In Item DataAssets you can configure item price(Currency and amount). In Shop Item class implemented Apply and Refund functions.```
![Gallery-10-Shop.png](/Gallery-10-Shop.png)
![Gallery-11-ShopGetters.png](/Gallery-11-ShopGetters.png)
![Gallery-12-ShopCategories.png](/Gallery-12-ShopCategories.png)
![Gallery-13-ShopDelegates.png](/Gallery-13-ShopDelegates.png)

```Profile System contains two libraries. For easy access to Managers, Stats and Data. And for advanced object/objects Serialization.```
![Gallery-14-Serialization.png](/Gallery-14-Serialization.png)

```You can easily configure Profile System in Project Settings```
