# Don't Starve mods
This repo contains home made mods for Don't Starve Together written in Lua.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To follow the instructions, you need to have git installed.

You can install the mods without git, but then you are on your own. 

Check if you have git by running

```
git --version
```

The output should look like

```
git version x.yy.z
```


### Installing

In order to install the mods, you need to clone this repository in your DST mod folder.

First move to your mod folder. Select your OS accordingly, then proceed.

#### For MacOS

```
cd ~/Library/Application\ Support/Steam/steamapps/common/Don\'t\ Starve/dont_starve.app/Contents/mods/
```

#### For Linux

```
cd ~/.steam/steam/steamapps/common/Don\'t\ Starve\ Together/mods
```

After moving to your folder, initialise it as a repository

```
git init
```

Then set the remote repository

```
git remote add origin https://github.com/erictornqvist/dont-starve-mods.git
```

Then download the mod folders 

```
git pull origin master
```

And download the actual content

```
git submodule update --init --recursive
```

Try it out by typing 

```
ls homebrew* -ld
```

Expected output should be something like

```
drwxr-xr-x 2 xxx yyy 4096 apr  5 13:22 homebrew-1337
drwxr-xr-x 2 xxx yyy 4096 apr  6 18:20 homebrew-1338

```


If you see the mods: 

Congratulations, the mods should now be installed. You can try them out by starting your own server. Remember that every one on your server using these mods must have them too.


## Authors

Written by the original starvation team, never surviving one night

* **Eric "No, I won't die this time" T** - *Trashy coder* 
* **Victoria "Do you want some poop" P** - *Windows guru* 
* **Viktor "I will smack them" M H** - *Creative mind* 
* **Julia "Does anyone have some food" A** - *Unwilling test subject* 
* **Emelie "I HATE BATS" A** - *Pre-alpha tester* 



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



