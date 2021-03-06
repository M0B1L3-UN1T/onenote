[//]: #@corifeus-header

  [![Build Status](https://travis-ci.org/patrikx3/onenote.svg?branch=master)](https://travis-ci.org/patrikx3/onenote)  [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/patrikx3/onenote/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/patrikx3/onenote/?branch=master)  [![Code Coverage](https://scrutinizer-ci.com/g/patrikx3/onenote/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/patrikx3/onenote/?branch=master) 

  
[![NPM](https://nodei.co/npm/p3x-onenote.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/p3x-onenote/)
---

 
# P3X Onenote Linux v1.2.273-382  

This is an open source project. Just code. If you like this code, please add a star in GitHub and if you really like, you can donate as well. Thanks you so much!

Given, I have my own server, with dynamic IP address, it could happen that the server for about max 5 minutes can not be reachable for the dynamic DNS or very rarely I backup with Clonzilla the SSD or something with the electricity (too much hoovering or cleaning - but I worked on it, so should not happen again), but for some reason, it is not reachable please hang on for 5-30 minutes and it will be back for sure. 

All my domains (patrikx3.com and corifeus.com) could have errors right now, since I am developing in my free time and you can catch glitches, but usually it is stable (imagine updating everything always, which is weird).

### Node Version Requirement 
``` 
>=8.9.0 
```  
   
### Built on Node 
``` 
v9.8.0
```   
   
The ```async``` and ```await``` keywords are required.

Install NodeJs:    
https://nodejs.org/en/download/package-manager/    



# Description  

                        
[//]: #@corifeus-header:end

This is a Linux OneNote. 

**Actually, the preferred installation is the ```AppImage``` and you do not even need to install ```NodeJs``` at all.**

Issues are on the bottom of this ```README```.

![Screenshot 1](https://cdn.corifeus.com/git/onenote/artifacts/screenshot/1.png)


# Downloadable installer

https://github.com/patrikx3/onenote/releases

After you downloaded the ```AppImage```, you still want to make it executable:
```bash
chmod +x p3x-onenote-a.b.c-d-x86_64.AppImage
# then
./p3x-onenote-a.b.c-d-x86_64.AppImage
```

Then it works as expected.

# You can find it in Atom Apps as well

https://electron.atom.io/apps/?q=onenote


# CLI Install

## The CLI Install is DEPRECATED entirely!

Please, do not use anymore.

## The old method is problematic

The ```CLI``` install is not always working because of some Linux distros are different by time to time, so it is possible then, the ```configstore``` is only working with ```sudo```, so the preferred way is to use the ```released``` ```AppImage``` as above! 

Besides, you do not even need to install ```NodeJs```, the ```AppImage``` includes everything all you need.

```bash
# this is some weird NPM error, you need like this:
node -v
# make sure it is above 8.9.0!!!
sudo npm install -g p3x-onenote --unsafe-perm=true --allow-root
p3x-onenote
```

After last startup and you logout and login again, you will have a menu.

# Features

* GNOME menu (`````~/.local/share/applications/p3x-onenote.desktop`````)
* Icon
* Tray
* Restart button (empty your cache, you can login again if there is an error)
* Remember last notebook
* Show / hide
* Quit
* Loads last visibility state

## Corporate

* Now, there is a menu ```Corporate home```

# Some info about P3X Onenote vs VirtualBox

If you have enough RAM or buffy workstation and you can install VirtualBox inside Windows and use the Marketplace based OneNote or install Office. I think, you do not need  ```p3x-onenote``` at all.  

For my workstation, with a 4.8Ghz CPU, 4 cores, 32 GB-ram, I use VirtualBox on Windows with Office Onenote (I use 6 GB RAM, 4 cores), but unfortunately my Laptop is old and has only 16GB RAM. Given, I develop a lot (NodeJs), I need the RAM, so for my Laptop, I use ```p3x-onenote``` and it's enough. Once the pages are loaded. It is fast, since it's own process without a browser and is in the tray, you don't have to re-load everything again. So it is very usable and after all pages are loaded, quick.

**You can try, you loose nothing.**

# Issues

## You cannot log in

I think it only happens, if you kill the ```P3X OneNote Linux``` and you then login again a lot. So, if you test and/or ```kill``` the program often, to be safe ,  ```sign out```, it is on the top right (inside the Electron browser frame itself). 

### BUT! 

**If you properly ```quit``` from ```p3x-onenote``` with the menu or the tray, then this problem will never happen.**

## Latest Gnome with dash-to-panel

Right now, for some weird, the new latest ```Gnome```, with ```dash-to-panel``` they removed the ```legacy tray``` icons or changed so that with ```Electron``` (as well many programs, including ```Skype``` ) is not working with the ```real original tray```. This is not an ```Electron``` or ```p3x-onenote``` issue, but the ```Gnome``` ```dash-to-panel``` problem.   
Probably it is too new, they will fix it, I think.
  
## Fedora

https://github.com/patrikx3/onenote/issues/3#issuecomment-312711801
  
## Change language

Right now, with online, it reverts even though on the main page I changed, but once it goes to do the actual pages - it reverts.
There is an investigation.

https://github.com/patrikx3/onenote/issues/14


[//]: #@corifeus-footer

---

[**P3X-ONENOTE**](https://pages.corifeus.com/onenote) Build v1.2.273-382 

[![Like Corifeus @ Facebook](https://img.shields.io/badge/LIKE-Corifeus-3b5998.svg)](https://www.facebook.com/corifeus.software) [![Donate for Corifeus / P3X](https://img.shields.io/badge/Donate-Corifeus-003087.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QZVM4V6HVZJW6)  [![Contact Corifeus / P3X](https://img.shields.io/badge/Contact-P3X-ff9900.svg)](https://www.patrikx3.com/en/front/contact) 


## Sponsor

[![JetBrains](https://www.patrikx3.com/images/jetbrains-logo.svg)](https://www.jetbrains.com/)
  
 

[//]: #@corifeus-footer:end