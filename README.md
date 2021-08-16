# Same stuff as the original server template, but more!
### Table of Contents
1. Starting Guide
2. File Directory
3. What We Changed
4. Passwords

## Starting Guide

1. Click the top right or locate Project Options where it says **"Remix to Edit 🎤"**
2. Give your new project a name.
3. Your private server name will be at <http://arras.io/#host=arras-template.glitch.me> (replace `arras-template` with its new name)
4. You may add a gamemode code in the link to specify its gamemode (see below.)

## File Directory
Stuff you'll likely be editing:
* `lib/definitions.js` - Tank, bullet, and all entity data.
* `config.json` - Map data and other options.
* `server.js` - Everything else, like movement, AI, firing, stats, damage, spawning, etc.! 

Stuff that you probably won't touch:
* `lib/fasttalk.js` - Data compression. No need to change it.
* `lib/hshg.js` - Deals with updating the game grid.
* `lib/random.js` - Contains all the random functions. Also contains the randomized Bot and Boss names, if you want to change them.
* `lib/util.js` - Miscellaneous functions.
* `package.json` - Nothing to edit here, just stuff the client uses to run the game.


## What We Changed
* All of the more recent tanks have been added. No need to re-add them.
* Along with these recent tanks, are their functionalities like invisibility!

## Passwords

1. Open the file at the left named `🔑 .env`
2. Fill it in with
```
SECRET=aSecretPasswordHere
```
3. Open the private server with <http://arras.io/#host=arras-template.glitch.me&key=aSecretPasswordHere> (replace `aSecretPasswordHere` with the password)
