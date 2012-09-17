---
isChild: true
---

## Установка на Mac

OSX предоставляется с предустановленным PHP, но данная версия не соответствует текущей стабильной. OSX Lion поставляется
 с PHP 5.3.6, а OSX Mountain Lion с 5.3.10.

Чтобы обновить PHP на OSX вы можете установить его через [менеджер пакетов Mac][mac-package-managers], с 
[php-osx от Liip][php-osx-downloads].

Другой способ — [скомпилировать пакет самому][mac-compile], в данном случае нужно убедиться, что установлен "Xcode" или 
["Command Line Tools for Xcode"][apple-developer], которые можно загрузить из "Apple's Mac Developer Center".

Для настройки полноценного окружения вебсервера (PHP + Apache + MySQL), можно воспользовуться утилитой 
[MAMP][mamp-downloads].

[mac-package-managers]: http://www.php.net/manual/en/install.macosx.packages.php
[mac-compile]: http://www.php.net/manual/en/install.macosx.compile.php
[xcode-gcc-substitution]: https://github.com/kennethreitz/osx-gcc-installer
[apple-developer]: https://developer.apple.com/downloads
[mamp-downloads]: http://www.mamp.info/en/downloads/index.html
[php-osx-downloads]: http://php-osx.liip.ch/
