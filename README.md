[![](https://discordapp.com/api/guilds/410828272679518241/widget.png?style=banner2)](https://discord.gg/Mvk7W7gjE4)
[![](https://raidcore.gg/Resources/Images/Patreon.png)](https://www.patreon.com/bePatron?u=46163080)

![](https://img.shields.io/github/license/RaidcoreGG/GW2-FastLoadingScreen-Releases?style=for-the-badge&labelColor=%23131519&color=%230F79AA)
![](https://img.shields.io/github/v/release/RaidcoreGG/GW2-FastLoadingScreen-Releases?style=for-the-badge&labelColor=%23131519&color=%230F79AA)
![](https://img.shields.io/github/downloads/RaidcoreGG/GW2-FastLoadingScreen-Releases/total?style=for-the-badge&labelColor=%23131519&color=%230F79AA)

# DISCLAIMER
# Modifying Guild Wars 2 through any third party software is not supported by ArenaNet nor by any of its partners.
# You are using this addon at your own risk.

# GW2-FastLoadingScreen-Releases
Public repository for releases of loading screen skip.
The actual source code is kept private in compliance with directives by ArenaNet for implementations based on reverse engineering.

## Installation
Install via the [Nexus](https://raidcore.gg/Nexus) Addon Library or download the latest `fastloadingscreen.dll` from the [Releases](https://github.com/RaidcoreGG/GW2-FastLoadingScreen-Releases/releases) and place in `<Guild Wars 2>/addons`.

## How it works
This addon makes runtime modifications to patch the timeout of loading models &amp; players from 60 seconds down to 100 milliseconds.
The same functionality used to exist within ArcDPS but was removed - as far as we know - due to the potential for abuse in competitive gamemodes.

## Limitations
- Loading screens aren't skipped entirely but on average take 2 seconds.
- Disabled in PvP and WvW gamemodes. Exceptions are Armistice Bastion and Obsidian Sanctum.
- Spamming lots of loading screens will result in longer ones, as you will spam the server with requests and you will be limited by the server, way before any skipping takes place.

## Is it safe to use?
*Probably.*  
As mentioned before, ArcDPS had the same functionality but removed it for other reasons.
The Guild Wars 2 Terms of Service state that any reverse engineering or memory reading/writing are explicitly forbidden.  
This makes addons like ArcDPS, DRF or Unofficial Extras illegal by default.
However since those are widely spread and even used by ArenaNet developers the statement should be taken with a grain of salt.  
What is actually important is the fact that it does not give any advantage. Refer to [https://help.guildwars2.com/hc/en-us/articles/360013625034-Policy-Third-Party-Programs](https://help.guildwars2.com/hc/en-us/articles/360013625034-Policy-Third-Party-Programs).
As a matter of fact, you can achieve similar load times by buying very good hardware, therefore giving lower-end machines the ability to be "on par" does not constitute an advantage in our eyes.
If you believe this addon should be removed, we'd be happy to hear your reasons as the perception of the community arguably matters most.

# To ArenaNet
## Please direct any concerns or takedown requests to [contact@raidcore.gg](mailto:contact@raidcore.gg). Any ArenaNet employee who wants to review the implementation may also contact us at the aforementioned email address to gain access.
