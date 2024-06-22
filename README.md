#### Current version - 5.9.3

If you want to talk directly with me about stuff feel free to visit my [technical support Discord server](https://discord.gg/dNnrzs4rMb)

Jan 2021 Update - Updated Oneechan to 5.9.3. New waifu (Makima)

Jan 2020 Update - Updated OneeChan to 5.9.2. Added more font options (fonts must be installed on your system), all available mascots have been ported over to a new host (onee.moe), and a new user theme has been added (Stalenhag)

Jul 2019 Update 3 - The issue of if the previously selected mascot was the last mascot on the list and a mascot was removed, OneeChan fails to start with error "TypeError 'mascot' is undefined" in the browser console has been fixed

Jul 2019 Update 2 - Mascots changing after updates were due to removal or additions not added to the bottom of the list, changing the order of mascots and therefore changing your selection. This update should be the last time your mascots are changed. See https://github.com/KevinParnell/OneeChan/issues/18 for full explanation

Jul 2019 Update - Put some mascots into new final image host, https://onee.moe

Jun 2019 Update - Added a new mascot, will be working on putting all the mascots in a new host

Apr 2019 Update - Made it possible to move around the reply box

Mar 2019 Update - Switching image host to GitHub as the old host is gone

Nov 2018 Update - Updated for support for https://4channel.org for the SFW boards


OneeChan
====

OneeChan is a userscript that functions on top of 4chan X and allows you to customize the site with various functions, themes and mascots. Mascots are not obligatory and can be changed or disabled altogether.

Originally developed by [seaweedchan](https://github.com/seaweedchan), this fork adds compatibility with various 4chan X versions and more custom options.


## [Click to Install](https://github.com/nekonugget/OneeChan/raw/master/builds/OneeChan.user.js)


#### Install instructions

Installing [4chan X](https://github.com/ccd0/4chan-x) is **required** for Oneechan to work.

- Firefox: Requires the [Violentmonkey](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/) extension. Click the Install link above.

- Chrome: Requires the [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl) extension. Click the Install link above.

- Pale Moon: Requires the [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/versions/?page=2#version-1.15.1-signed) extension. Click the Install link above.

- MS Edge: Requires the [Tampermonkey](https://www.microsoft.com/store/apps/9NBLGGH5162S) extension. Click the Install link above.

- MS Edge Chromium: Requires the [Tampermonkey](https://www.microsoft.com/en-us/microsoft-edge/insider-addons/detail/iikmkjmpaadaobahmlepeloendndfphd) extension. Click the Install link above.

- Safari: Requires the [Tampermonkey](https://safari-extensions.apple.com/details/?id=net.tampermonkey.safari-G3XV72R5TC) extension. Click the Install link above.

An optional script I would recommend is a (You) counter - [All-Time-You-Count](https://github.com/KevinParnell/All-time-You-count)

#### Adblock/pihole filters fix:

Add this to your filters list:

```
@@||4chan.org^*$csp=default-src 'self' * data: 'unsafe-inline' 'unsafe-eval'
@@|blob:$image,media,domain=4chan.org
@@||boards.4chan.org^$csp
@@||4channel.org^*$csp=default-src 'self' * data: 'unsafe-inline' 'unsafe-eval'
@@|blob:$image,media,domain=4channel.org
@@||boards.4channel.org^$csp 
```

if you are encountering this error (can be seen with any theme):

![image](https://raw.githubusercontent.com/KevinParnell/OneeChan/master/images/1543173395179.png)

#### Compatibility with 4chan X forks and others:

(Updated 2023-04-10)

- [ccd0](https://github.com/ccd0/4chan-x) /// `Compatible` (Recommended)

ccd0's 4chan X is the recommended 4chan X version and the one OneeChan is primarily developed for. If you use another 4chan X version, please make sure you select your fork version under `Compatibility` in OneeChan options. Enabling Quick Reply, Persistent QR and Auto Hide QR in 4chan X is recommended for maximum compatibility.


#### Troubleshooting

- If you have any problems, try first resetting your 4chan X and OneeChan settings and restarting your browser

- Check if it's not a 4chan X issue first, OneeChan mostly deals with stylesheets not site functionality

- Something doesn't work let me know in the [Issues](https://github.com/KevinParnell/OneeChan/issues) page

- Please refer to the [Wiki](https://github.com/KevinParnell/OneeChan/wiki) for instructions (this is currently empty)

- If you are having issues with mascots saving or resetting, please manually select 'Select none' and save, fully refresh the page or exit, and reload it. Reselect your mascots manually, this should fix any issue with mascot settings not saving.

#### Development & Contribution

- [Changelog](https://github.com/KevinParnell/OneeChan/blob/master/CHANGELOG.md)
- [Source Code](https://github.com/KevinParnell/OneeChan)
- [Reporting Bugs and Contributing](https://github.com/KevinParnell/OneeChan/blob/master/CONTRIBUTING.md)

#### Settings I use (seen in screenshots)

[4chan X](https://kevinparnell.dev/eloper/4chan%20X%20v1.14.7.4-1559932978329.json)

[OneeChan](https://kevinparnell.dev/eloper/OneeChan%20v5.7.7%20Settings.json)

Just import them and it'll ask to reload the page.

#### Screenshots

Catalog

![image](https://raw.githubusercontent.com/KevinParnell/OneeChan/master/images/catalog1.png)

Thread

![image](https://raw.githubusercontent.com/KevinParnell/OneeChan/master/images/thread1.png)
