---
isChild: true
anchor: windows_setup
---

## Windows Setup {#windows_setup_title}

PHP is voor windows op verschillende manieren beschikbaar. Je kan de [binaries downloaden][php-downloads] en tot recent kon je ook een .msi installer gebruiken. Dit is echter niet meer mogelijk sinds PHP 5.3.0.

Om PHP te leren en lokaal te ontwikkelen kan je de ingebouwde webserver bij PHP5.4+ gebruiken, zodat je je geen zorgen moet maken over configuratie en dergelijke. 
Indien je een "all-in-one" oplossing wil inclusief een volledige webserver en MySQL, kunnen programma's zoals de [Web Platform Installer][wpi], 
[Zend Server CE][zsce], [XAMPP][xampp], [EasyPHP][easyphp] en [WAMP][wamp] je helpen om een Windows development omgeving snel op te zetten. Bedenk wel dat door deze programma's te gebruiken, jouw ontwikkelingsomgeving kan verschillen van de uiteindelijke productie omgeving, zeker indien je ontwikkelt op Windows en live draait op Linux.

If you need to run your production system on Windows then IIS7 will give you the most stable and best performance. You can use 
[phpmanager][phpmanager] (a GUI plugin for IIS7) to make configuring and managing PHP simple. IIS7 comes with FastCGI built in and ready 
to go, you just need to configure PHP as a handler. For support and additional resources there is a [dedicated area on iis.net][php-iis] for 
PHP.

[php-downloads]: http://windows.php.net
[phpmanager]: http://phpmanager.codeplex.com/
[wpi]: http://www.microsoft.com/web/downloads/platform.aspx
[zsce]: http://www.zend.com/en/products/server-ce/
[xampp]: http://www.apachefriends.org/en/xampp.html
[easyphp]: http://www.easyphp.org/
[wamp]: http://www.wampserver.com/
[php-iis]: http://php.iis.net/
