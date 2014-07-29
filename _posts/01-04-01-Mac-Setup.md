---
isChild: true
anchor: mac_setup
---

## Mac Setup  {#mac_setup_title}

OSX komt met een ingebouwde versie van PHP maar dit is meestal niet de allerlaatste stabiele versie. 
Lion komt bijvoorbeeld met PHP 5.3.6, Mountain Lion met 5.3.10 en Mavericks met 5.4.17.

Om PHP te updaten op OSX kan je 't installeren via bepaalde Mac [package managers][mac-package-managers], met als aanrader [php-osx by Liip][php-osx-downloads].

Een alternatieve oplossing is om het [zelf te compileren][mac-compile]. 
In dat geval moet je Xcode installeren, ofwel de vervanging van Apple: ["Command Line Tools for Xcode"][apple-developer], te downloaden van Apple's Mac Developer Center.

Uiteindelijk kan je ook een volledig "all-in-one" pakket installeren, inclusief PHP, Apache web server en een MySQL database, gecombineerd met een aangename interface. Kies in dat geval voor [MAMP][mamp-downloads] of [XAMPP][xampp].
w
[mac-package-managers]: http://www.php.net/manual/en/install.macosx.packages.php
[mac-compile]: http://www.php.net/manual/en/install.macosx.compile.php
[xcode-gcc-substitution]: https://github.com/kennethreitz/osx-gcc-installer
[apple-developer]: https://developer.apple.com/downloads
[mamp-downloads]: http://www.mamp.info/en/downloads/index.html
[php-osx-downloads]: http://php-osx.liip.ch/
[xampp]: http://www.apachefriends.org/en/xampp.html
