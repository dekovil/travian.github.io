======
TravianZ Version **v.8.3.5**
======

***Test server for latest fixed 8.3.5 version available at [travian.martinambrus.com](https://travian.martinambrus.com)***

**Note:** this game is still in a pre-release state, although at this point it is very playable, tested and found to be fairly stable

**WARNING:** please note that ***this is in no way an upgrade*** from the old 8.3.2 version, so please ***do not try to just copy your files over***, 
since the installer logic has changed and you would just crash your old version

**Quick links:**
* [Download and Updates](https://github.com/martinambrus/TravianZ) &raquo;&raquo; https://github.com/martinambrus/TravianZ
* [Wiki](https://github.com/martinambrus/TravianZ/wiki)
* [Game Mechanics](http://travian.wikia.com/wiki/Travian_Wiki)

**Minimum requirements:**
* [PHP](http://php.net/) 7.0.0+
* [MySQL Community Server](https://dev.mysql.com/downloads/mysql/) 5.5+
  * or alternatively, [MariaDB](https://downloads.mariadb.org/) 5.5+

**Dedicated or shared hosting?**

We *strongly* recommend using a ***dedicated hosting*** for this game. Big Travian servers used to host 
thousands of players and the original servers still had about 300ms page display time. The legacy code 
in this clone (which was created in 2013) is right now doing about **400 MySQL queries** (questions 
to the database) per single page refresh - which is usually well beyond what most shared hostings can support 
with a big enough player base.

**Support & Bug reports**

Please use the [Issues tab](https://github.com/martinambrus/TravianZ/issues) and create new issue, whether it's an error in game or you have a feature request to be included in the play.

**The team**
* [martinambrus](https://github.com/martinambrus) - Project Resurrector & Lead Developer

**Thanks**

A big thanks to [Kirilloid](https://github.com/kirilloid) who helped us a lot with the Battle System formulas.
Many thanks to all those who recently played around with the project and tested it both, locally and on their 
own servers. This includes [ZZJHONS](https://github.com/ZZJHONS), [DracoMilesX](https://github.com/DracoMilesX), 
[phaze1G](https://github.com/phaze1G) and many others who were too shy to let us know that they use and enjoy 
running this game :)

Also, our thanks go to all both, the original and occasional developers, especially [Shadowss](https://github.com/Shadowss), [yi12345](https://github.com/yi12345/), [advocaite](https://github.com/advocaite/), [brainiacX](https://github.com/brainiacX/), [ronix](https://github.com/ronix/), 
[MisterX](https://github.com/MisterX/), [Elio](https://github.com/eliopinho/), [Vladyslav](https://github.com/velhbxtyrj), [martinambrus](https://github.com/martinambrus), [AL-Kateb](https://github.com/AL-Kateb), [Dzoki](https://github.com/idzoki), [iopietro](https://github.com/iopietro) and many others who were part of this 
project's history.
