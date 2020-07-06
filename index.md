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
| Discord  | `com.hnc.Discord`  |
| League of Legends | `com.riotgames.leagueoflegends` |
| Logic Pro X  | `com.apple.logic10`  |


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