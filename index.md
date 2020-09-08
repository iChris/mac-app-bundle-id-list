---
layout: layouts/home.njk
eleventyNavigation:
  key: Home
  order: 1
---


## Bundle Identifier List

| App Name  | Bundle ID |
|---| ---|
| Audacity  |  `org.audacityteam.audacity` |
| [Audio Hijack](https://rogueamoeba.com/audiohijack/) | `com.rogueamoeba.audiohijack3` |
| Auphonic Multitrack | `com.auphonic.mac.multitrack` |
| [Discord](https://discord.com/)  | `com.hnc.Discord`  |
| [Ecamm Live](https://www.ecamm.com/mac/ecammlive/?fp_ref=ichris) | `com.ecamm.EcammLive` |
| Farrago | `com.rogueamoeba.farrago` |
| [Forecast](https://overcast.fm/forecast) | `fm.overcast.forecast-encoder`|
| League of Legends | `com.riotgames.leagueoflegends` |
| Logic Pro X  | `com.apple.logic10`  |
| Minecraft | `com.mojang.minecraftlauncher` |
| Steam (Valve) | `com.valvesoftware.steam` |

### How to Find an App's Bundle Identifier

I figured this out based on [this post from Rob Griffiths in 2018](https://robservatory.com/easily-see-any-apps-bundle-identifier/):

Open up Terminal.app

Type the following command:

`osascript -e 'id of app "Name of App"'`

The "Name of App" is replaced with the name of the app as it appears when hovering over its Dock icon.

So for example,

* Chrome is `Google Chrome`.
* Plugging that into the code above you get: `osascript -e 'id of app "Google Chrome"'`
* Which will provide you with a bundle identifier of `com.google.Chrome`.

### Tutorial Video

Here's how to fix macOS audio mic permissions using Discord as an example:

<iframe width="560" height="315" src="https://www.youtube.com/embed/p4Q4WDgwVgg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[Direct link to YouTube video](https://youtu.be/p4Q4WDgwVgg)