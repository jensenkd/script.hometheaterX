Home Theater Experience library sync
==============================================

###Table of Contents
* [What is Home Theater Experience?](#what-is-home-theater-experience)
* [What can this addon do?](#what-can-this-addon-do)
* [Installation](#installation)
* [Problems?](#problems)
  * ["I found something that doesn't work"](#i-found-something-that-doesnt-work)
  * [Creating logfiles](#creating-logfiles)
* [Contribute](#contribute)
  * [Pull requests](#pull-requests)
  * [Translations](#translations)
* [Thanks](#thanks)

###What is Home Theater Experience?
Automatically sync your Kodi database to the web.  This will allow you to view your entire library from anywhere in the world.  It will also allow you to bounce your collection up against other members, IMDB lists, etc.. 

Sign up for a free account at [hometheaterX.com](http://hometheaterX.com) and get a ton of features:

* Track your media collections and compare with friends
* Track your progress against industry lists such as the IMDb Top 250
* Create custom lists around any topics you choose

Coming Soon:
* Automatically scrobble what you're watching
* Use watchlists so you don't forget what to watch
* Easily track your TV show progress across all seasons and episodes

###What can this addon do?
* Sync your TV episode and movie collections to HomeTheaterX (manually or triggered by a library update)
* Keep watched statuses synced between Kodi and HomeTheaterX

Remote streaming content will scrobble assuming the metadata is correctly set in Kodi. Add-ons that stream content need to correctly identify TV episodes and movies with as much metadata as possible for HomeTheaterX to know what you're watching.

###Installation
If your not a developer, you should only install this from the official Kodi repo via Kodi itself. If you are a dev, here is how you install the dev version:

1. Download the zip ([download it here](../../zipball/master))
2. Install script.hometheaterX by zip. Go to *Settings* > *Add-ons* > *Install from zip file* > Choose the just downloaded zip
3. Navigate to *Settings* > *Add-ons* > *Enabled add-ons* > *Services* > **MovieLib**
4. Select *Trakt* and go to **Configure**
5. Get your **PIN** [here](http://www.hometheaterx.com/apikey) and enter it, change any other settings as needed
6. Select **OK** to save your settings
7. Watch *something* and see it show up on HomeTheaterX.com!

###Problems?
####"I found something that doesn't work"
* Search the issues on github to see if it has already been reported, if so add your information there.
* If not, create a new issue and provide as much data about your system as possible, a logfile will also be needed.

####Creating logfiles
* To create a logfile, enable the debug setting in Kodi AND script.hometheaterX, otherwise the logfile won't show any data from script.hometheaterX. Check the [Kodi documentation] (http://kodi.wiki/view/Log_file) if you don't know where your logfile can be found.

###Contribute

####Pull requests
* Please make your pull requests on the branch named "dev" only. 
* Please don't add pull requests for translation updates these have to go work their way through the translation workflow (see [Translations](#translations))

####Translations
* Translations are done via the Transifex project of Kodi. If you want to support translation efforts, read [this] (http://kodi.wiki/view/Translation_System) and look for script-hometheaterX under the XBMC Addons project in Transifex.

###Thanks
* Special thanks to all who contribute to this plugin! Check the commit history and changelog to see these talented developers.

