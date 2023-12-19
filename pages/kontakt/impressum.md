---
title: Impressum
top_url: /kontakt/
permalink: /impressum/
sub_menu: true
sub_weight: 3
layout: page
---

Freifunk {{ site.community.name }} e. V. ist seit dem 05.07.2016 im Vereinsregister des Amtsgerichts Dresden unter der Vereinregisternummer VR 9705 eingetragen.\\
Der Verein ist gemeinn&uuml;tzig und finanziert sich &uuml;ber [Mitgliedsbeitr&auml;ge]({{ "/verein/mitgliedsbeitrag/" | prepend: site.baseurl }}) und [Spenden]({{ "/verein/spenden/" | prepend: site.baseurl }}).

#### Ansprechpartner
> [{{ site.community.mail_info }}](mailto:{{ site.community.mail_info }})

#### Angaben gem&auml;ß § 5 TMG
> {{ site.community.meta }}\\
> {{ site.community.address_postbox }}\\
> {{ site.community.address_zipcode }}

> **E-Mail:** {{ site.community.mail_vorstand }}\\
> **Website:** www.freifunk-dresden.de

#### Vertreten durch den Vorstand
{% for subcom in site.community.vorstand %}> * {{ subcom }}
{% endfor %}

#### Registereintrag

> **Registergericht:** Amtsgericht Dresden\\
> **Registernummer:** VR 9705

#### Verantwortlich im Sinne des Presserechts (V. i. S. d. P.)
> Torsten Rudolph\\
> Eibenstocker Str. 89\\
> 01277 Dresden
