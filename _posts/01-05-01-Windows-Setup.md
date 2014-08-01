---
isChild: true
anchor: windows_setup
---

## Windows Installatie {#windows_setup_title}

PHP is voor windows op verschillende manieren beschikbaar. Je kan de [binaries downloaden][php-downloads] en tot recent kon je ook een .msi installer gebruiken. Dit is echter niet meer mogelijk sinds PHP 5.3.0.

Om PHP te leren en lokaal te ontwikkelen kan je de ingebouwde webserver bij PHP5.4+ gebruiken, zodat je je geen zorgen moet maken over configuratie en dergelijke. 
Indien je een "all-in-one" oplossing wil inclusief een volledige webserver en MySQL, kunnen programma's zoals de [Web Platform Installer][wpi], 
[Zend Server CE][zsce], [XAMPP][xampp], [EasyPHP][easyphp] en [WAMP][wamp] je helpen om een Windows development omgeving snel op te zetten. Bedenk wel dat door deze programma's te gebruiken, jouw ontwikkelingsomgeving kan verschillen van de uiteindelijke productie omgeving, zeker indien je ontwikkelt op Windows en live draait op Linux.

Als je een productie omgeving op Windows wil draaien, zal IIS7 je waarschijnlijk de meeste stabiliteit en performantie geven. 
Je kan [phpmanager][phpmanager] (een GUI plugin voor IIS7) gebruiken om php gemakkelijk te configureren en beheren.
IIS7 komt met ingebouwde FastCGI en is verder gebruiksklaar, je dient enkel PHP als handler te configureren.
Om ondersteuning te krijgen en verdere informatie te vinden is en een [specifiek onderdeel op iis.net][php-iis] voor PHP.

[php-downloads]: http://windows.php.net
[phpmanager]: http://phpmanager.codeplex.com/
[wpi]: http://www.microsoft.com/web/downloads/platform.aspx
[zsce]: http://www.zend.com/en/products/server-ce/
[xampp]: http://www.apachefriends.org/en/xampp.html
[easyphp]: http://www.easyphp.org/
[wamp]: http://www.wampserver.com/
[php-iis]: http://php.iis.net/
