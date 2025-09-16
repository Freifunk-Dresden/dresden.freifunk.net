---
title: H&auml;ufige Fragen
top_url: /mitmachen/
permalink: /mitmachen/faq/
sub_menu: true
sub_weight: 7
layout: page
---

### Wo stehen schon Freifunk-Router?

Schau mal auf der [Karte]({{ "/karte/" | prepend: site.baseurl }}) nach. Wenn es bei dir noch keinen Freifunk-Router in der Nachbarschaft gibt, dann sei die oder der Erste!

### Warum ist das alles kostenlos? Wo ist der Haken?

Freifunk ist eine gemeinschaftliche Bewegung, die einen freien Netzzugang als gesellschaftlichen Grundstein sieht. Wir m&ouml;chten zudem den derzeitigen rechtlichen (St&ouml;rerhaftung) sowie datenschutzrechtlichen (Kundendaten sammeln) Problematiken aus dem Weg gehen. Die Infrastruktur wird ausschließlich &uuml;ber Spenden finanziert.

### Ben&ouml;tige ich einen Router f&uuml;r 2,4 GHz oder 5 GHz?

Jedes Endger&auml;t heutzutage funkt mindestens auf dem 2,4 GHz Band, modernere Modelle k&ouml;nnen außerdem das 5 GHz Band nutzen, auf dem, wenn nicht allzu viel Sichtbehinderung vorliegt, h&ouml;here Datenraten erreicht werden k&ouml;nnen.

Beachte: Damit sich ein Freifunk-Router mit einem anderen Freifunk-Router &uuml;ber WLAN verbinden kann, m&uuml;ssen beide Router im gleichen Frequenzband (2,4 GHz oder 5 GHz) arbeiten.

### K&ouml;nnen mehrere Freifunk-Router an einem Ort miteinander verbunden werden?

Mehrere Freifunk-Router k&ouml;nnen sowohl &uuml;ber Funk meshen, als auch &uuml;ber den WAN-Port. Hierzu gibt es die Mesh-on-WAN-Funktion, welche sich in den Experteneinstellungen aktivieren l&auml;sst. Nat&uuml;rlich k&ouml;nnen die Router auch v&ouml;llig unabh&auml;ngig voneinander eine Verbindung zum Rest der Freifunk-Wolke herstellen.

### Kann ich den Freifunk-Router auch &uuml;ber ein existierendes privates WLAN anbinden?

Dies ist aus verschiedenen Gr&uuml;nden mit der Standard-Freifunk-Firmware nicht m&ouml;glich:

 - Das im Router verbaute WLAN-Modul kann meist nur auf einer Frequenz gleichzeitig funken. Somit w&auml;re allein technisch eine Verbindung nur dann m&ouml;glich, wenn das Uplink-WLAN auf der gleichen Frequenz wie Freifunk sendet.
 - In diesem Fall w&uuml;rde die "Airtime" (also die Zeit, die der Funkkanal belastet wird) doppelt beansprucht, zum Senden im Freifunk-Netz und zum Weiterreichen ins Uplink-WLAN.
 - Zwei WLAN-Radios an einem Freifunkrouter k&ouml;nnten einen Uplink theoretisch auch auf einem anderen Kanal erm&ouml;glichen, dies erfordert jedoch manuelle Konfiguration, welche bei aktivem Autoupdater kaputt gehen k&ouml;nnte.
 - Ein USB-WLAN-Stick, welcher das 2. Radio bereitstellen k&ouml;nnte, kostet auch ~15€, ungef&auml;hr so viel wie schon ein kleiner vollst&auml;ndiger Freifunk-Router (TP-Link WR841N).

Unsere Empfehlung w&auml;re daher, einen Freifunk-Router an der Quelle hinzustellen (dort, wo es ein Netzwerkkabel gibt), und am zweiten Standort einen zweiten Freifunk-Router, welcher mit dem ersten meshen w&uuml;rde und so den Zugang zum Rest des Netzes bereitstellt. Diese L&ouml;sung ist auch updatesicher und erfordert keine manuelle Konfiguration.

### Weitere FAQs im Wiki

[{{ site.community.url_faq }}]({{ site.community.url_faq }})


