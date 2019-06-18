---
title: Router einrichten
top_url: /mitmachen/
permalink: /mitmachen/router-einrichten/
sub_menu: true
sub_weight: 2
layout: page
---

*Ausführlich im Wiki: [{{ site.community.url_routerconf_ext }}]({{ site.community.url_routerconf_ext }})*

### Den Router aufstellen
Als Standort empfehlen sich Fenster, Balkone oder Dächer. Je näher er der Außenwelt ist, desto wahrscheinlicher ist es, dass er f&uuml;r Passanten erreichbar ist und sich mit anderen Routern verbindet um eine [Meshverbindung](https://de.wikipedia.org/wiki/Vermaschtes_Netz) zu bilden.

### Verbinde den Router mit dem Netzwerk

Wenn du deinen Internetzugang zur Verf&uuml;gung stellen m&ouml;chtest, verbinde jetzt den blauen WAN-Anschluss deines Freifunk-Router mit deinem vorhandenen Internetrouter. M&ouml;chtest oder kannst du das nicht bist du auf andere Freifunker in deiner Nähe angewiesen um eine Verbindung zum Freifunk-Netzwerk und ins Internet herzustellen.

### Den Router anschließen

1. Lade das passende Erstinstallations-Firmware-Image f&uuml;r deinen Router [von unserer Seite]({{ site.community.url_firmware }}) herunter.
2. Verbinde deinen Computer mit einem der gelben LAN-Anschl&uuml;sse des Routers.
3. Dein Computer erhält nun automatisch via DHCP eine IP-Adresse.

### Installiere das Freifunk-Image

1. &ouml;ffne das Webinterface deines Routers in deinem Browser.
2. Folge den Anweisungen im Handbuch deines Routers um die Firmware zu aktualisieren.
3. Nutze nun das von der zuvor heruntergeladene Firmware-Image.
4. Warte bis der Router wieder gestartet ist.

### Den Router konfigurieren

Dein Router sollte nun mit der Freifunk-Firmware starten. Du erhälst erneut IP-Adresse per DHCP, dein Freifunk-Router ist nun unter [http://192.168.1.1](http://192.168.1.1) in deinem Browser erreichbar.

Zum Login verwendest du als Nutzer "***root***" und das Passwort "***admin***".

1. Nach der ersten Anmeldung, wirst du zur Änderung des Passwortes aufgefordert. ( *Passwörter dürfen Buchstaben, Zahlen, Satzzeichen enthalten* )

2. Bei der ersten Installation muss der Auto-Setup durchgeführt werden. ( *Menü: Allgemein → Auto-Setup* )\\
Damit versucht der Router sich eine Knotennummer vom Server zu holen. Wenn das erfolgreich war, startet der Router erneut und ist unter der neuen IP (10.200,x.x) im Freifunknetz erreichbar. Falls der Router kein Internet zu diesem Zeitpunkt hat, so arbeitet er mit einer temporären Knotennummer bis eine Internetverbindung besteht.

3. Kontakinformationen ( *Menü: Allgemein → Kontaktinfos* )\\
Kontaktinformationen geben den Nutzern und anderen Freifunkern die Möglichkeit bei Fragen und Problemen den Routerbetreiber zu kontaktieren. Bitte trage Daten ein, unter denen du zu erreichen bist.\\
Die GPS Koordinaten und Kontaktinformationen werden von [www.freifunk-dresden.de](https://www.freifunk-dresden.de) von jedem Router regelmäßig abgefragt und zur Generierung der Netzwerktopology und Hotspot-Liste verwendet. Hier sind korrekte Daten wichtig, damit dein Knoten auf der Karte im Internet auch zu finden ist und andere Menschen sehen, dass in der Gegend Freifunk verfügbar ist.

### Fertig

Super, du hast es geschafft. Dein Freifunk-Knoten funktioniert jetzt und sollte, wenn du GPS Koordinaten angegeben hast, in K&uuml;rze auf der [Karte]({{ "/karte/" | prepend: site.baseurl }}) erscheinen.
