---
title: Sprechstunde
permalink: /kontakt/sprechstunde/

sub_menu: true
top_url: /kontakt/
sub_weight: 1

layout: main
---

{% include head-kontakt-map.html %}

<header>
	<h2 class="post-title">{{ page.title }}</h2>
</header>

<p style="text-align: center;">Der ideale Raum für Fragen und den Austausch von Ideen und gemeinsamen Plänen.</p>

<section class="box">
    <h2>Wöchentliches Treffen</h2>
    <p>Wenn dich Freifunk interessiert, laden wir dich hiermit ein, uns unkompliziert kennenzulernen. Wir treffen uns wieder <strong><span id="next_meet_date">heute</span>, ab 19 Uhr</strong>.</p>

    {% include next_meet_day.html %}

    <p>Die Treffen finden regelm&auml;&szlig;ig <strong>online und im Rosenwerk (RW)</strong> statt. Wo du uns zu welchem Termin findest, erfährst du in unserem <a href="{{ "/verein/kalender/" | prepend: site.baseurl }}">Kalender</a>.</p>
</section>

<section class="box">
    <h3>a) Sprechstunde im Netz</h3>

    <p>
        In der Woche zwischen den Treffen im Rosenwerk sind wir in unserer Online-Sprechstunde in Jitsi-Meet erreichbar auf:
        <ul class="actions align-center">
            <li><a href="{{ site.community.url_online-sprechstunde }}" class="button accent2 icon fa-microphone-lines">{{ site.community.url_online-sprechstunde  | remove: 'https://' | remove: 'http://' }}</a></li>
        </ul>
    </p>


    <h3>b) Sprechstunde vor Ort im Rosenwerk</h3>

    <div id="map" style="height: 30em; margin: 1em 0; width: 45%; float: right; margin-left: 2em"></div>
    <script>
        $(document).ready(function() {
            mapinit();
        });
    </script>

    <!-- 
    ACCENT COLORS:
    accent1: #666666 (gray)     → bg: #f0f0f0
    accent2: #dc0067 (pink)     → bg: #fcf2f7
    accent3: #ffb400 (yellow)   → bg: #fffcf0
    accent4: #009ee0 (cyan)     → bg: #f0f7fc ← Currently used
    accent5: #111111 (black)    → bg: #f0f0f0
    -->
    <div style="background: #f0f7fc; border-left: 4px solid #009ee0; padding: 1.5em; margin: 1.5em 0; border-radius: 0 4px 4px 0; margin-right: 48%;">
        <h4 style="margin: 0 0 0.5em 0; color: #333; font-size: 1.1em;">
            <i class="fa fa-map-location-dot" style="color: #009ee0; margin-right: 0.5em;"></i>
            Treffpunkt
        </h4>
        <div style="line-height: 1.6;">
            <strong><a href="https://konglomerat.org">Konglomerat e. V.</a> / Freifunk {{ site.community.name }} e. V.</strong><br>
            <span style="color: #666;">im Rosenwerk</span><br><br>
            <a href="{{ site.community.url_treffenort }}" style="color: #009ee0; text-decoration: none; font-weight: 500;">
                <i class="fa fa-city" style="color: #009ee0; margin-right: 0.3em;"></i>Jagdweg 1-3
            </a><br>
            <span style="color: #555;">01159 Dresden</span>
        </div>
    </div>
    
    <p>Das regelmäßige Treffen bietet die ideale Gelegenheit, mit uns in pers&ouml;nlichen Kontakt zu treten.</p>

    <p>Sollte die T&uuml;r geschlossen sein, findet ihr neben den Briefk&auml;sten einen silberfarbenen Funktaster f&uuml;r die Klingel im „Raum Ohne Namen“ (RON). Gleich nach dem Eingang geht es links durch den Gang in Richtung Glast&uuml;r.</p>

    <h4>Anfahrt</h4>
    <p>
        <ul>
            <li>F&uuml;r Fahrrad und KFZ bietet der Jagdweg gen&uuml;gend (kostenlose) Abstellm&ouml;glichkeiten.</li>
            <li>Per <a href="http://www.öpnvkarte.de/?zoom=17&lat=51.04774&lon=13.71672&layers=TBTTT#13.7167;51.0477;17">&Ouml;PNV</a> f&uuml;hren die Straßenbahn-Linien 7 und 12 (Haltestelle Rosenstraße) und die Linien 10 und 20 (Haltestelle Freiberger Straße – World Trade Center) sowie die S-Bahn-Linien S1 und S2 (Hp. Freiberger Straße) zu uns.</li>
        </ul>
    </p>
</section>

<section class="box">
    <h3>Mehr Informationen zur Sprechstunde</h3>
    <p>
        Bei uns im Wiki findet ihr weitere Informationen &uuml;ber die <a href="{{ site.community.url_sprechstunde }}">Sprechstunde</a> und alle <a href="{{ site.community.url_treffenthema }}">Themen</a>.
    </p>
</section>

<section class="box">
    <h2>Weitere Kanäle</h2>
    <p>Wenn es dir nicht m&ouml;glich ist uns zu besuchen, dann gibt es nat&uuml;rlich noch alternative Kontaktwege. Eine Übersicht aller unserer Kanäle findest du auf unserer allgemeinen <a href="/kontakt/">Kontaktseite</a>.</p>
</section>
