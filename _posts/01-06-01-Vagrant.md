---
isChild: true
anchor: vagrant
---

## Vagrant {#vagrant_title}

Een applicatie op een verschillend omgeving draaien in productie dan in ontwikkeling kan vreemde foutmeldingen geven wanneer je live gaat.
Het is ook riskant om verschillende ontwikkelingsomgevingen up to date te houden met dezelfde versie van alle libraries wanneer je in een team van developers werkt.

Indien je bijvoorbeeld ontwikkelt op Windows, en moet deployen op Linux (of iets anders non-Windows), of in een team werkt, moet je zeker overwegen om een Virtuele Machine te gebruiken.
Dit klinkt moeilijk, maar met [Vagrant][vagrant] kan je een eenvoudige virtuele machile opzetten in slecht enkele stappen.
Deze basis 'dozen' kunnen dan manueel opgezet worden, of je kan een 'voorzienende' software gebruiken zoals [Puppet][puppet] of [Chef][chef] om dit voor jou te doen.

'Voorzienende' software gebruiken is een goede manier om te garanderen dat meerdere dozen op een identieke manier opgezet zijn en zorgt ervoor dat je geen complexe setup commando's moet oplijsten.
Je kan ook je basisdoos 'vernietigen' en opnieuw opbouwen zonder veel manuele stappen. Zo wordt het heel gemakkelijk om een 'verse' installatie op te zetten.

Vagrant maakt folders aan om je code te delen tussen eigen computer en virtuele machine, wat betekent dat je je bestanden kan aanmaken en aanpassen op je eigen werkstation en nadien de code kan draaien op de virtuele machine.

### Een beetje hulp

Indien je wat hulp nodig hebt om te starten met Vagrant zijn er drie diensten die nuttig kunnen zijn:

- [Rove][rove]: Dienst die toelaat om typische Vagrant builds aan te maken, waaronder php. De voorziening wordt voorzien door Chef.
- [Puphpet][puphpet]: eenvoudige GUI om virtuele machines op te zetten voor PHP ontwikkeling. **Zware focus op PHP**. Naast lokale VM's, kan je er ook mee deployen naar cloud-diensten. De voorziening is gemaakt met Puppet.
- [Protobox][protobox]: dit is een laag bovenop Vagrant en een web GUI om virtuele machines op te zetten voor web ontwikkeling. Eén YAML document controleert alles wat geïnstalleerd is op de virtuele machine.

[vagrant]: http://vagrantup.com/
[puppet]: http://www.puppetlabs.com/
[chef]: http://www.opscode.com/
[rove]: http://rove.io/
[puphpet]: https://puphpet.com/
[protobox]: http://getprotobox.com/
