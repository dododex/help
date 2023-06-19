---
layout: faq
title: Configuring ARK Multipliers on Dododex
category: using-dododex
---

This guide will show you how to configure your ARK multipliers for various types of servers and game modes. This guide only covers multipliers that affect taming, breeding, and XP rates on Dododex. 

ARK Multipliers
---------------

PERMANENT 2X TAMING (AUGUST 2020)

In August 2020, ARK's base taming speed on PC, PS4, and Xbox is now doubled, meaning 1× is as fast as what 2× was previously. Dododex has been updated to reflect this. Like ARK, Dododex implemented this as part of the base speed (1x) -- so keep your multipliers at 1x on Official Servers.

Official Server
---------------

| **Multiplier** | **Value** |
| --- | --- |
| **Taming Speed** | 1   |
| **Egg Hatch Speed** | 1   |
| **Breeding Multiplier** | 1   |
| **XP Multiplier** | 1   |
| **Use Single Player Settings** | Off _(default)_ |

Official Server (Evolution Event Weekends)
------------------------------------------

On both the app and [Dododex.com](https://www.dododex.com/), you must manually update your multipliers during Evolution Event weekends. In the Dododex app, you can use the "Evolution Event" preset (or create your own) to easily switch back and forth.
 

Small Tribes, Conquest, and Arkpocalypse servers are all affected by Evolution event rates ([confirmed by developers](https://twitter.com/Jatheish/status/1332108397576138753)), however, the multiplier is not always the same as "2x (or 3x) the normal rate." See ARK's official announcement for each event's multipliers on these server types.

> **IMPORTANT:** ARK's Evolution Events don't always the same multipliers. Be sure to check Dododex's live-updating [**Official ARK Server Rates**](https://www.dododex.com/rates)  to confirm the current multipliers on official servers.

| **Multiplier** | **Value** |
| --- | --- |
| **Taming Speed** | Typically 2 on most weekend events |
| **Egg Hatch Speed** | Typically 2 |
| **Baby Mature Speed** | Typically 2 |
| **XP Multiplier** | Typically 2 |
| **Use Single Player Settings** | Off _(default)_ |

Single Player
-------------

By default, single player on PC and console has "Use Single Player Settings" on. See below for details about Use Single Player Settings. 

| **Multiplier** | **Value** |
| --- | --- |
| **Taming Speed** | 1   |
| **Egg Hatch Speed** | 1   |
| **Baby Mature Speed** | 1   |
| **XP Multiplier** | 1   |
| **Use Single Player Settings** | **On** _(default)_ |

Small Tribes Servers
--------------------

| **Multiplier** | **Value** |
| --- | --- |
| **Taming Speed** | 2.5 |
| **Egg Hatch Speed** | 2   |
| **Baby Mature Speed** | 2   |
| **XP Multiplier** | 2.5 |
| **Use Single Player Settings** | Off _(default)_ |

ARKpocalypse
------------

| **Multiplier** | **Value** |
| --- | --- |
| **Taming Speed** | 3   |
| **Egg Hatch Speed** | 3   |
| **Baby Mature Speed** | 3   |
| **XP Multiplier** | 3   |
| **Use Single Player Settings** | Off _(default)_ |

ARK: Mobile
-----------

| **Multiplier** | **Value** |
| --- | --- |
| **Taming Speed** | Normal: **0.875**<br><br>With 3x Minor Soothing Balm: **2.625**<br><br>With 10x Minor Soothing Balm: **8.75**<br><br>With 15x Minor Soothing Balm: **13.125** |
| **Egg Hatch Speed** | **1** |
| **Baby Mature Speed** | **1** |
| **XP Multiplier** | **0.5**<br><br>With Primal Pass Upgrade: **1** |
| **Use Single Player Settings** | Off _(default)_ |

Explanation of ARK Multipliers
------------------------------

| Multiplier | What increasing it does | Where to find it in ARK Settings | Property name in GameUserSettings.ini |
| --- | --- | --- | --- |
| **Taming Speed** | **Reduces food** required for taming dinos. This will in turn **reduce time and narcotics**, and **increase effectiveness.** | General Tab | TamingSpeedMultiplier |
| **Dino Character Food Drain** _(Originally labeled on Dododex as "Consumption Speed")_ | Creatures get **hungry faster**, meaning they **tame faster** with the same quantity of food. Does not affect taming effectiveness. | General Tab | DinoCharacterFoodDrainMultiplier |
| **Egg Hatch Speed** | Increases speed of hatching / gestation. | Advanced Tab | EggHatchSpeedMultiplier |
| **Baby Mature Speed** | Increases speed of a baby's maturation (after hatching/birth) | Advanced Tab | BabyMatureSpeedMultiplier |
| **XP Multiplier** | Increases XP gained | General Tab | XPMultiplier |
| **Use Single Player Settings** | A checkbox that increases several multiplier. See below. | General Tab | `bUseSingleplayerSettings` |

_More details on other ARK Multipliers:_ [_ark.gamepedia.com/Server_Configuration_](https://ark.gamepedia.com/Server_Configuration)

Notes
-----

* **Egg Hatch Speed, Baby Mature Speed, and XP Multiplier** are only available on the Dododex App (not yet available on dododex.com) 
* **Dino Character Food Drain** should always be set to 1 unless you're on an Unofficial Server with custom settings (this is uncommon), or single player with this setting changed.
* **Harvesting Speed** multipliers do not apply to Dododex.

If all of Dododex's calculations seem wrong...
----------------------------------------------

If all of Dododex's calculations are too low or too high, your multipliers are most likely set up incorrectly. Another common error is if you have "**Use Single Player Settings**" enabled in the app when it's not enabled in the game (or vice versa). This setting will increase all of your multipliers. See below:

What is "Use Single Player Settings"?
-------------------------------------

The "Use Single Player Settings" option in the Dododex app should be enabled if you have this setting enabled in your ARK settings (under "General"). This setting is defaulted _**on**_ in single player in ARK and it increases all of your multipliers:  

* Taming Speed: **2.5×**
* XP Multiplier: **2×**
* Egg Hatch Speed: **10×**
* Baby Mature Speed: **36.799×**

  
(This multiplier is _on top of_ your existing multiplier. For example, if you have your taming multiplier in ARK set to "2" and you have "Use Single Player Settings" on, your multiplier will actually be 5.)   
 
ARK Mobile players should keep this setting off, as it is not available in ARK Mobile.

