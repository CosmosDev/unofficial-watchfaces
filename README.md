This repository tries to keep track of AsteroidOS unofficial watchfaces.
Feel free to pull request your work here and if it suits the graphic guidelines
of AsteroidOS, it can eventually be merged into the default set of asteroid-launcher.


### Install selected or all watchfaces using scripted SCP/ADB ###

- Open a terminal and clone this unofficial-watchfaces repo to a new subfolder from your current location.\
`git clone https://github.com/AsteroidOS/unofficial-watchfaces`
- Cd into unofficial-watchfaces folder.\
`cd unofficial-watchfaces/`
- Connect your AsteroidOS Watch, configured to either ADB Mode (ADB transfer) or Developer Mode (SCP transfer) in Settings -> USB.
- Start `./deploy.sh` to use SCP commands or `./deploy.sh -a` for ADB commands.
- Select a single watchface to deploy to the watch with its given number or copy all available watchfaces at once with option 1.
- You then can restart the ceres session and apply a single selected watchface with pressing 'y'.

Note that restarting the ceres session might be necessary when new fonts were installed along with the new watchfaces.
Restarting the ceres session might break things like Always On Mode or the battery display for the remaining uptime. Reboot the watch in that case.
You may [restart the session or reboot the watch](https://asteroidos.org/wiki/useful-commands/#restart) manually.


### Test watchfaces in qmlscene ###

- After cloning the repo and changing into its local directory like described above, execute test-in-qmlscene.sh without flag to use 24H display.\
`./test-in-qmlscene.sh`
- Or with the -use12h flag for 12H display.\
`./test-in-qmlscene.sh -use12h`

Note that some community watchfaces use features that are not available in qmlscene, like the battery display.


### Following great community contributions are available ###

Watchface creation in QtQuick is really easy!
You can learn how to make your own by following the [Watchface Creation](https://asteroidos.org/wiki/watchfaces-creation/) Guide.
The creators of the below listed watchfaces are happy to answer your questions and you are free to use their contributions as base for your own work.


| Round Display | Square Display | Watchface Title | Creator |
|---|---|---|---|
| ![thumbnail](.thumbnails/analog-modern-steel-round.jpg) | ![thumbnail](.thumbnails/analog-modern-steel.jpg) | [analog-modern-steel](analog-modern-steel/usr/share/asteroid-launcher/watchfaces/analog-modern-steel.qml) | [CosmosDev](https://github.com/CosmosDev) |
| ![thumbnail](.thumbnails/analog-words-round.jpg) | ![thumbnail](.thumbnails/analog-words.jpg) | [analog-words](analog-words/usr/share/asteroid-launcher/watchfaces/analog-words.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/analog-silly-walks-round.jpg) | ![thumbnail](.thumbnails/analog-silly-walks.jpg) | [analog-silly-walks](analog-silly-walks/usr/share/asteroid-launcher/watchfaces/analog-silly-walks.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/analog-red-handed-round.jpg) | ![thumbnail](.thumbnails/analog-red-handed.jpg) | [analog-red-handed](analog-red-handed/usr/share/asteroid-launcher/watchfaces/analog-red-handed.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/pulsedot-round.jpg) | ![thumbnail](.thumbnails/pulsedot.jpg) | [pulsedot](pulsedot/usr/share/asteroid-launcher/watchfaces/pulsedot.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/analog-precision-round.jpg) |![thumbnail](.thumbnails/analog-precision.jpg) | [analog-precision](analog-precision/usr/share/asteroid-launcher/watchfaces/analog-precision.qml) | [Mario Kicherer](mailto:dev@kicherer.org) |
| ![thumbnail](.thumbnails/retro-lcd-round.jpg) |![thumbnail](.thumbnails/retro-lcd.jpg) | [retro-lcd](retro-lcd/usr/share/asteroid-launcher/watchfaces/retro-lcd.qml) | [Huntereb](mailto:Huntereb@lewd.pics), [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/kitt-round.jpg) |![thumbnail](.thumbnails/kitt.jpg) | [kitt](kitt/usr/share/asteroid-launcher/watchfaces/kitt.qml) | [jgibbon](https://github.com/jgibbon) |
| ![thumbnail](.thumbnails/arc-round.jpg) |![thumbnail](.thumbnails/arc.jpg) | [arc (multiple)](arc/usr/share/asteroid-launcher/watchfaces/) | [jgibbon](https://github.com/jgibbon) |
| ![thumbnail](.thumbnails/alternative-default-digital-mosen-round.jpg) |![thumbnail](.thumbnails/alternative-default-digital-mosen.jpg) | [alternative-default-digital-mosen](alternative-default-digital-mosen/usr/share/asteroid-launcher/watchfaces/alternative-default-digital-mosen.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/alternative-digital-mosen-round.jpg) |![thumbnail](.thumbnails/alternative-digital-mosen.jpg) | [alternative-digital-mosen](alternative-digital-mosen/usr/share/asteroid-launcher/watchfaces/alternative-digital-mosen.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/analog-asteroid-logo-round.jpg) |![thumbnail](.thumbnails/analog-asteroid-logo.jpg) | [analog-asteroid-logo](analog-asteroid-logo/usr/share/asteroid-launcher/watchfaces/analog-asteroid-logo.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/analog-railway-round.jpg) |![thumbnail](.thumbnails/analog-railway.jpg) | [analog-railway](analog-railway/usr/share/asteroid-launcher/watchfaces/analog-railway.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/analog-rings-round.jpg) |![thumbnail](.thumbnails/analog-rings.jpg) | [analog-rings](analog-rings/usr/share/asteroid-launcher/watchfaces/analog-rings.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/analog-scientific-round.jpg) |![thumbnail](.thumbnails/analog-scientific.jpg) | [analog-scientific](analog-scientific/usr/share/asteroid-launcher/watchfaces/analog-scientific.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/analog-tactical-round.jpg) |![thumbnail](.thumbnails/analog-tactical.jpg) | [analog-tactical](analog-tactical/usr/share/asteroid-launcher/watchfaces/analog-tactical.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/binary-digital-round.jpg) |![thumbnail](.thumbnails/binary-digital.jpg) | [binary-digital](binary-digital/usr/share/asteroid-launcher/watchfaces/binary-digital.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/binary-lcd-round.jpg) |![thumbnail](.thumbnails/binary-lcd.jpg) | [binary-lcd](binary-lcd/usr/share/asteroid-launcher/watchfaces/binary-lcd.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/bold-hour-bebas-v2-round.jpg) |![thumbnail](.thumbnails/bold-hour-bebas-v2.jpg) | [bold-hour-bebas-v2](bold-hour-bebas-v2/usr/share/asteroid-launcher/watchfaces/bold-hour-bebas-v2.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/clean-bars-round.jpg) |![thumbnail](.thumbnails/clean-bars.jpg) | [clean-bars](clean-bars/usr/share/asteroid-launcher/watchfaces/clean-bars.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/day-clock-24h-round.jpg) |![thumbnail](.thumbnails/day-clock-24h.jpg) | [day-clock-24h](day-clock-24h/usr/share/asteroid-launcher/watchfaces/day-clock-24h.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/greenium-round.jpg) |![thumbnail](.thumbnails/greenium.jpg) | [greenium](greenium/usr/share/asteroid-launcher/watchfaces/greenium.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/humongous-round.jpg) |![thumbnail](.thumbnails/humongous.jpg) | [humongous](humongous/usr/share/asteroid-launcher/watchfaces/humongous.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/karlos-matrix-round.jpg) |![thumbnail](.thumbnails/karlos-matrix.jpg) | [karlos-matrix](karlos-matrix/usr/share/asteroid-launcher/watchfaces/karlos-matrix.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/logo-45degree-round.jpg) |![thumbnail](.thumbnails/logo-45degree.jpg) | [logo-45degree](logo-45degree/usr/share/asteroid-launcher/watchfaces/logo-45degree.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/motivational-quotes-round.jpg) |![thumbnail](.thumbnails/motivational-quotes.jpg) | [motivational-quotes](motivational-quotes/usr/share/asteroid-launcher/watchfaces/motivational-quotes.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/orbiting-asteroids-round.jpg) |![thumbnail](.thumbnails/orbiting-asteroids.jpg) | [orbiting-asteroids](orbiting-asteroids/usr/share/asteroid-launcher/watchfaces/orbiting-asteroids.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/prominent-seconds-round.jpg) |![thumbnail](.thumbnails/prominent-seconds.jpg) | [prominent-seconds](prominent-seconds/usr/share/asteroid-launcher/watchfaces/prominent-seconds.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/rainbow-uprising-round.jpg) |![thumbnail](.thumbnails/rainbow-uprising.jpg) | [rainbow-uprising](rainbow-uprising/usr/share/asteroid-launcher/watchfaces/rainbow-uprising.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/sporty-round-round.jpg) |![thumbnail](.thumbnails/sporty-round.jpg) | [sporty-round](sporty-round/usr/share/asteroid-launcher/watchfaces/sporty-round.qml) | [eLtMosen](https://github.com/eLtMosen) |
| ![thumbnail](.thumbnails/sporty-round-v2-round.jpg) |![thumbnail](.thumbnails/sporty-round-v2.jpg) | [sporty-round-v2](sporty-round-v2/usr/share/asteroid-launcher/watchfaces/sporty-round-v2.qml) | [eLtMosen](https://github.com/eLtMosen) |

### Licenses ###

| Watchface - File | License |
| --- | --- |
| analog-modern-steel - [Michroma - Regular](analog-modern-steel/usr/share/fonts/Michroma.ttf) | The font "Michroma" is licensed under SIL Open Font License and was created by [Vernon Adams](https://github.com/vernnobile). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| analog-words - [Montserrat - Regular](analog-words/usr/share/fonts/Montserrat-Regular.ttf) | The font "Montserrat" is licensed under SIL Open Font License and was created by [The Montserrat project](https://github.com/JulietaUla/Montserrat). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| analog-words - [Source Sans Pro - Semibold](analog-words/usr/share/fonts/SourceSansPro-Semibold.ttf) [Source Sans Pro - Light](analog-words/usr/share/fonts/SourceSansPro-Light.ttf)| The font "Source Sans Pro" is licensed under SIL Open Font License and was created by [Paul D Hunt](https://fonts.google.com/specimen/Source+Sans+Pro). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| analog-silly-walks - [Varieté - Regular](analog-silly-walks/usr/share/fonts/Varieté_Regular.ttf) | The font "Varieté" is licensed under SIL Open Font License and was created by [Peter Wiegel](https://de.fonts2u.com/variete.schriftart). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| analog-red-handed - [PTSans - Bold](analog-red-handed/usr/share/fonts/PTSans-Bold.ttf) | The font "PTSans" is licensed under SIL Open Font License and was created by [Alexandra Korolkova, Olga Umpeleva and Vladimir Yefimov and released by ParaType](https://fonts.google.com/specimen/PT+Sans). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| analog-red-handed - [Russo One - Regular](analog-red-handed/usr/share/fonts/RussoOne-Regular.ttf) | The font "Russo One" is licensed under SIL Open Font License and was created by [Jovanny Lemonad](https://fonts.google.com/specimen/Russo+One). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| pulsedot - [Source Sans Pro - Semibold](pulsedot/usr/share/fonts/SourceSansPro-Semibold.ttf) [Source Sans Pro - Regular](pulsedot/usr/share/fonts/SourceSansPro-Regular.ttf)| The font "Source Sans Pro" is licensed under SIL Open Font License and was created by [Paul D Hunt](https://fonts.google.com/specimen/Source+Sans+Pro). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| retro-lcd - [Digital-7 (Mono)](retro-lcd/usr/share/fonts/digital-7%20(mono).ttf) | The font "Digital-7" is freeware for home use and was created by [Sizenko Alexander](http://www.styleseven.com). |
| binary-lcd - [Digital-7 (Mono)](binary-lcd/usr/share/fonts/digital-7%20(mono).ttf) | The font "Digital-7" is freeware for home use and was created by [Sizenko Alexander](http://www.styleseven.com). |
| analog-rings [SlimSans](analog-rings/usr/share/fonts/SlimSans.ttf) | The font "SlimSans" was created by [Manfred Klein](https://web.archive.org/web/20170823125251/http://manfred-klein.ina-mar.com). Manfred’s fonts are free for private and charity use. They are even free for commercial use – but if there’s any profit, pls make a donation to organizations like [Doctors Without Borders](http://www.doctorswithoutborders.org/)|
| bold-hour-bebas-v2 - [BebasKai-Regular](bold-hour-bebas-v2/usr/share/fonts/BebasKai-Regular.otf), [BebasNeue](bold-hour-bebas-v2/usr/share/fonts/BebasNeueBold.ttf) | The fonts "BebasKai" and "Bebas Neue" are licensed under SIL Open Font License and was created by [Dharma Type](http://www.dharmatype.com/). [license](bold-hour-bebas/usr/share/fonts/License.txt) |
| day-clock-24h - [Vollkorn-Regular](day-clock-24h/usr/share/fonts/Vollkorn-Regular.ttf) | The font "Vollkorn" is licensed under SIL Open Font License and was created by [Friedrich Althausen](http://www.vollkorn-typeface.com). [license](day-clock-24h/usr/share/fonts/OFL.txt)|
| greenium [Titillium-Bold](greenium/usr/share/fonts/Titillium-Bold.otf), [Titillium-Light](greenium/usr/share/fonts/Titillium-Light.otf) | The font "Titillium" is licensed under SIL Open Font License and was created at the [Accademia di Belle Arti di Urbino](http://www.campivisivi.net/titillium/). [license](greenium/usr/share/fonts/OFL.txt)|
| rainbow-uprising [Titillium-Bold](greenium/usr/share/fonts/Titillium-Bold.otf), [Titillium-Regular](rainbow-uprising/usr/share/fonts/Titillium-Regular.otf), [Titillium-Thin](rainbow-uprising/usr/share/fonts/Titillium-Thin.otf) | The font "Titillium" is licensed under SIL Open Font License and was created at the [Accademia di Belle Arti di Urbino](http://www.campivisivi.net/titillium/). [license](greenium/usr/share/fonts/OFL.txt)|
| sporty-round, sporty-round-v2 [SlimSans](sporty-round/usr/share/fonts/SlimSans.ttf) | The font "SlimSans" was created by [Manfred Klein](https://web.archive.org/web/20170823125251/http://manfred-klein.ina-mar.com). Manfred’s fonts are free for private and charity use. They are even free for commercial use – but if there’s any profit, pls make a donation to organizations like [Doctors Without Borders](http://www.doctorswithoutborders.org/)|
| orbiting-asteroids - [Blue Marble](orbiting-asteroids/usr/share/asteroid-launcher/wallpapers/nasa-blue-marble.jpg) | The image "Blue Marble", Eastern Hemisphere March 2014, Photo from NASA Goddard Space Flight Center is available under creative commons license |
| binary-digital - [Simpleness](binary-digital/usr/share/fonts/Simpleness.otf) | The font "Simpleness" is licensed under SIL Open Font License and was created by [Valentin Francois](http://valentinfrancois.fr/). [license](binary-digital/usr/share/fonts/License.pdf)|
| humongous - [Item-Black](humongous/usr/share/fonts/ITEMBL__.TTF) | The font "Item" is Public Domain and was created by [Bojmic Interpro](https://www.fontzillion.com/fonts/bojmic-interpro/item).|
| logo-45degree - [Sinner](logo-45degree/usr/share/fonts/SINNER__.TTF) | The font "Sinner" is freeware for personal, non-commercial use only and was created by [Helge Barske](http://www.barske.com/). [license-info](https://www.fontzillion.com/fonts/helge-barske/sinner)|
| motivational-quotes - [Lobster](motivational-quotes/usr/share/fonts/Lobster.otf) | The font "Lobster" is licensed under SIL Open Font License and was created by [Impallari Type](http://www.impallari.com/lobster). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| clean-bars - [CPMono_v07](clean-bars/usr/share/fonts/) | The font "CPMono_v07" is licensed under CC-BY-3.0 and was created by [Tino Meinert, Liquitype](http://liquitype.fr/index.html). [license](clean-bars/usr/share/fonts/CC_License.txt)|
| analog-tactical - [Fyodor-BoldCondensed](analog-tactical/usr/share/fonts/Fyodor-BoldCondensed.ttf) | The font "Fyodor" is licensed under SIL Open Font License and was created by [Chris Hughes](http://fyodor.blueroomcollective.co.uk/). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
| analog-scientific - [Reglo](analog-scientific/usr/share/fonts/) | The font "Reglo" is licensed under SIL Open Font License and was created by [sebsan, Sebastien Sanfilippo](https://github.com/sebsan/Reglo). [license](https://github.com/sebsan/Reglo/blob/master/OFL.txt)|
| karlos-matrix - [Elektra SH](karlos-matrix/usr/share/fonts/) | According to fonts4free.net, the font "Elektra SH" is free for both personel and commercial usages and was created by [Samy Halim](https://www.fontshop.com/designers/samy-halim). [license](http://www.fonts4free.net/elektra-sh-font.html)|
| alternative-digital-mosen - [GeneraleMono](alternative-digital-mosen/usr/share/fonts/) | The font "GeneraleMono" is licensed under SIL Open Font License and was created by [ARIEL MARTÍN PÉREZ](http://www.arielgraphisme.com). [license](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)|
