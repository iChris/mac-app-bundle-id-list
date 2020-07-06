# What Is This?

A repo for a site listing the bundle ID of various Mac apps that people have trouble giving mic and screen control permission to under macOS.

See [this video](https://youtu.be/p4Q4WDgwVgg) for details.

# How to Find an App's Bundle Identifier

I figured this out based on [this post from Rob Griffiths in 2018](https://robservatory.com/easily-see-any-apps-bundle-identifier/):

Open up Terminal.app

Type the following command:

`osascript -e 'id of app "Name of App"'`

The "Name of App" is replaced with the name of the app as it appears when hovering over its Dock icon.