---
layout: faq
title: Configuring ARK Multipliers on Dododex
category: using-dododex
---

This guide will show you how to configure your ARK multipliers for various types of servers and game modes. This guide only covers multipliers that affect taming, breeding, and XP rates on Dododex. 

<h2>Official Servers</h2>
<table class="small">
  <thead>
    <tr>
      <th>Multiplier</th>
      <th>Official Server</th>
      <th>Official Server (Evolution Event Weekends)</th>
      <th>Small Tribes Servers</th>
      <th>ARKpocalypse</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="avg">Taming Speed</td>
      <td>1</td>
      <td>Typically 2 on most weekend events</td>
      <td>2.5</td>
      <td>3</td>
    </tr>
    <tr>
      <td class="avg">Egg Hatch Speed</td>
      <td>1</td>
      <td>Typically 2</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <td class="avg">Baby Mature Speed</td>
      <td>1</td>
      <td>Typically 2</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <td class="avg">XP Multiplier</td>
      <td>1</td>
      <td>Typically 2</td>
      <td>2.5</td>
      <td>3</td>
    </tr>
    <tr>
      <td class="avg">Use Single Player Settings</td>
      <td colspan="4">Off</td>
    </tr>
  </tbody>
</table>

### Official Server Evolution Event Weekends

On both the app and [Dododex.com](https://www.dododex.com/), you must manually update your multipliers during Evolution Event weekends. In the Dododex app, you can use the "Evolution Event" preset (or create your own) to easily switch back and forth. Small Tribes, Conquest, and Arkpocalypse servers are all affected by Evolution event rates ([confirmed by developers](https://twitter.com/Jatheish/status/1332108397576138753)), however, the multiplier is not always the same as "2x (or 3x) the normal rate." See ARK's official announcement for each event's multipliers on these server types.

**IMPORTANT:** ARK's Evolution Events don't always the same multipliers. Be sure to check Dododex's live-updating [**Official ARK Server Rates**](https://www.dododex.com/rates)  to confirm the current multipliers on official servers.


## Single Player

_By default, single player on PC and console has "Use Single Player Settings" on. See below for details about Use Single Player Settings._

<table class="small">
  <thead>
    <tr>
      <th rowspan="2">Multiplier</th>
      <th rowspan="2">ARK: Survival Evolved</th>
      <th colspan="3">ARK: Survival Ascended</th>
    </tr>
    <tr>
      <th>Difficulty: Easy</th>
      <th>Difficulty: Medium</th>
      <th>Difficulty: Hard</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="avg">Taming Speed</td>
      <td>5</td>
      <td>3</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <td class="avg">Egg Hatch Speed</td>
      <td>20</td>
      <td>10</td>
      <td>5</td>
      <td>1</td>
    </tr>
    <tr>
      <td class="avg">Baby Mature Speed</td>
      <td>40</td>
      <td>20</td>
      <td>10</td>
      <td>1</td>
    </tr>
    <tr>
      <td class="avg">XP Multiplier</td>
      <td>3</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <td class="avg">Use Single Player Settings</td>
      <td colspan="4">On</td>
    </tr>
  </tbody>
</table>



## ARK: Mobile

<table class="small">
  <thead>
    <tr>
      <th>Multiplier</th>
      <th>ARK: Mobile</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="avg" rowspan="4">Taming Speed</td>
      <td>Normal: 0.875</td>
    </tr>
    <tr>
      <td>With 3x Minor Soothing Balm: 2.625</td>
    </tr>
    <tr>
      <td>With 10x Minor Soothing Balm: 8.75</td>
    </tr>
    <tr>
      <td>With 15x Minor Soothing Balm: 13.125</td>
    </tr>
    <tr>
      <td class="avg">Egg Hatch Speed</td>
      <td>1</td>
    </tr>
    <tr>
      <td class="avg">Baby Mature Speed</td>
      <td>1</td>
    </tr>
    <tr>
      <td class="avg">XP Multiplier</td>
      <td>0.5<br>With Primal Pass Upgrade: 1</td>
    </tr>
    <tr>
      <td class="avg">Use Single Player Settings</td>
      <td>Off</td>
    </tr>
  </tbody>
</table>

---


## Explanation of ARK Multipliers

<table class="small">
  <thead>
    <tr>
      <th>Multiplier</th>
      <th>What increasing it does</th>
      <th>Where to find in ASE Settings</th>
      <th>Where to find in ASA Settings</th>
      <th>Property name in GameUserSettings.ini</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="avg"><strong>Taming Speed</strong></td>
      <td><strong>Reduces food</strong> required for taming dinos. This will in turn <strong>reduce time and narcotics</strong>, and <strong>increase effectiveness.</strong></td>
      <td>General Tab</td>
      <td>Game Rules &gt; World</td>
      <td><code class="language-plaintext highlighter-rouge">TamingSpeedMultiplier</code></td>
    </tr>
    <tr>
      <td class="avg"><strong>Dino Character Food Drain</strong></td>
      <td>Creatures get <strong>hungry faster</strong>, meaning they <strong>tame faster</strong> with the same quantity of food. Does not affect taming effectiveness.</td>
      <td>General Tab</td>
      <td>Game Rules &gt; Creature (“Food Drain”)</td>
      <td><code class="language-plaintext highlighter-rouge">DinoCharacterFoodDrainMultiplier</code></td>
    </tr>
    <tr>
      <td class="avg"><strong>Egg Hatch Speed</strong></td>
      <td>Increases speed of hatching / gestation.</td>
      <td>Advanced Tab</td>
      <td>Advanced &gt; World</td>
      <td><code class="language-plaintext highlighter-rouge">EggHatchSpeedMultiplier</code></td>
    </tr>
    <tr>
      <td class="avg"><strong>Baby Mature Speed</strong></td>
      <td>Increases speed of a baby’s maturation (after hatching/birth)</td>
      <td>Advanced Tab</td>
      <td>Advanced &gt; World</td>
      <td><code class="language-plaintext highlighter-rouge">BabyMatureSpeedMultiplier</code></td>
    </tr>
    <tr>
      <td class="avg"><strong>XP Multiplier</strong></td>
      <td>Increases XP gained</td>
      <td>General Tab</td>
      <td>Game Rules &gt; World</td>
      <td><code class="language-plaintext highlighter-rouge">XPMultiplier</code></td>
    </tr>
    <tr>
      <td class="avg"><strong>Use Single Player Settings</strong></td>
      <td>A checkbox that increases several multiplier. See below.</td>
      <td>General Tab</td>
      <td>Game Rules &gt; Rules</td>
      <td><code class="language-plaintext highlighter-rouge">bUseSingleplayerSettings</code></td>
    </tr>
  </tbody>
</table>


_More details on other ARK Multipliers:_ [_ark.gamepedia.com/Server_Configuration_](https://ark.gamepedia.com/Server_Configuration)

### What is "Use Single Player Settings"?

The "Use Single Player Settings" option in the Dododex app should be enabled if you have this setting enabled in your ARK settings (under "General"). This setting is defaulted _**on**_ in single player in ARK and it increases all of your multipliers:  

* Taming Speed: **2.5×**
* XP Multiplier: **2×**
* Egg Hatch Speed: **10×**
* Baby Mature Speed: **36.799×**
  
(This multiplier is _on top of_ your existing multiplier. For example, if you have your taming multiplier in ARK set to "2" and you have "Use Single Player Settings" on, your multiplier will actually be 5.)   
 
ARK Mobile players should keep this setting off, as it is not available in ARK Mobile.


## Notes

* **Egg Hatch Speed, Baby Mature Speed, and XP Multiplier** are only available on the Dododex App (not yet available on dododex.com) 
* **Dino Character Food Drain** should always be set to 1 unless you're on an Unofficial Server with custom settings (this is uncommon), or single player with this setting changed.
* **Harvesting Speed** multipliers do not apply to Dododex.
* **Permanent 2x Taming (August 2020)**: In August 2020, ARK's base taming speed on PC, PS4, and Xbox was doubled, meaning 1× is as fast as what 2× was previously. Dododex has been updated to reflect this. Like ARK, Dododex implemented this as part of the base speed (1x) -- so keep your multipliers at 1x on Official Servers.


## If all of Dododex's calculations seem wrong...

If all of Dododex's calculations are too low or too high, your multipliers are most likely set up incorrectly. Another common error is if you have "**Use Single Player Settings**" enabled in the app when it's not enabled in the game (or vice versa). This setting will increase all of your multipliers. See below:

