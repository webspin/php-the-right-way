---
anchor: code_style_guide
---

# Code Style Guide  {#code_style_guide_title}

De PHP gemeenschap is groot en divers, en bestaat uit ontelbare libraries, frameworks en componenten. PHP ontwikkelaars hebben de gewoonte om 
verschillende hiervan te combineren in één enkel project. 
Het is belangrijk dat PHP code (zo dicht mogelijk) een gemeenschappelijke 'code style' benadert, opdat ontwikkelaars zo weinig mogelijk problemen tegen komen bij het combineren en gebruiken van verschillende libraries.

De [Framework Interop Group][fig] heeft een reeks stijl aanbevelingen gemaakt en goed gekeurd. Deze voorstellen gaan niet allemaal over code stijl, maar diegene die er wel over gaan zijn [PSR-0][psr0], [PSR-1][psr1], [PSR-2][psr2] en [PSR-4][psr4]. 
Deze aanbevelingen zijn niet meer dan een reeks regels die sommige projecten zoals Drupal, Zend, Symfony, CakePHP, phpBB, AWS SDK, FuelPHP, Lithium, 
etc beginnen toepassen. 
Je kan ze gebruiken in jouw projecten, of je eigen stijl blijven gebruiken.

Hoedanook kan je best PHP code schrijven die een gekende standaard volgt. Dit kan eender welke combinatie zijn van PSRs, of één van de code standaards van PEAR or Zend. 
Dit betekent dat andere ontwikkelaars jouw code gemakkelijk kunnen lezen en ermee werken, en software die jouw componenten gebruikt kan samenhang hebben ondanks het gebruik van veel externe code...

* [Lees meer over PSR-0][psr0]
* [Lees meer over PSR-1][psr1]
* [Lees meer over PSR-2][psr2]
* [Lees meer over PSR-4][psr4]
* [Lees meer over PEAR Code Standards][pear-cs]
* [Lees meer over Zend Code Standards][zend-cs]
* [Lees meer over Symfony Coding Standards][symfony-cs]

Je kan [PHP_CodeSniffer][phpcs] gebruiken om te conroleren of jouw code één van deze aanbevelingen volgt, en plugins voor text editors zoals [Sublime Text 2][st-cs] om real-time feedback te geven. 

Gebriuk de [PHP Coding Standards Fixer][phpcsfixer] van Fabien Potencier om automatisch jouw code syntax aan te passen zodat het deze standaarden volgt, zodat je dit niet overal manueel moet doen.

Als taal gaat de voorkeur uit naar het Engels voor alle symbolen en infrastructuur namen. Commentaar mag in iedere taal geschreven worden die door alle huidige en toekomstige ontwikkelaars van de code gemakkelijk begrepen kan worden.

[fig]: http://www.php-fig.org/
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[psr4]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md
[pear-cs]: http://pear.php.net/manual/en/standards.php
[zend-cs]: http://framework.zend.com/wiki/display/ZFDEV2/Coding+Standards
[symfony-cs]: http://symfony.com/doc/current/contributing/code/standards.html
[phpcs]: http://pear.php.net/package/PHP_CodeSniffer/
[st-cs]: https://github.com/benmatselby/sublime-phpcs
[phpcsfixer]: http://cs.sensiolabs.org/
