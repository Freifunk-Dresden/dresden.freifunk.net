---
title: E-Mail
top_url: /kontakt/
permalink: /kontakt/email/
sub_menu: true
sub_weight: 1
layout: page
---
Sprich uns an!

## Allgemein

Die erste Anlaufstelle, um mit uns Kontakt aufzunehmen:

>[{{ site.community.mail_info }}](mailto:{{ site.community.mail_info }})

## Vorstand

Möchtest du dich speziell beim Vorstand des Freifunk Dresden e.&nbsp;V. melden, dann sende deine E-Mail an:

>[{{ site.community.mail_vorstand }}](mailto:{{ site.community.mail_vorstand }})

Dem Vorstand gehören aktuell an:

{% for subcom in site.community.vorstand %}>* {{ subcom }}
{% endfor %}

## Mailing-Listen

Außerdem halten wir dich in unserem <a href="{{ "/kontakt/mailinglists" | prepend: site.baseurl }}">Newsletter</a> auf dem Laufenden und bieten zahlreiche weitere <a href="{{ "/kontakt/mailinglists" | prepend: site.baseurl }}">Mailing-Listen</a> an, in denen über allerlei Freifunk-Themen diskutiert wird.