---
title: E-Mail
permalink: /kontakt/email/

sub_menu: true
top_url: /kontakt/
sub_weight: 2

layout: main
---

<header>
	<h2 class="post-title">{{ page.title }}</h2>
</header>

<p style="text-align: center;">Sprich uns an!</p>

<section class="box">
	<h2>Allgemein</h2>

	<p>Die erste Anlaufstelle, um mit uns Kontakt aufzunehmen:</p>

	<ul class="actions align-center">
		<li><a href="mailto:{{ site.community.mail_info }}" class="button accent2 icon fa-envelope">{{ site.community.mail_info }}</a></li>
	</ul>
</section>

<section class="box">
	<h2>Vorstand</h2>

	<p>Möchtest du dich speziell beim Vorstand des Freifunk Dresden e.&nbsp;V. melden, dann sende deine E-Mail an:</p>

	<ul class="actions align-center">
		<li><a href="mailto:{{ site.community.mail_vorstand }}" class="button accent3 icon fa-users-line">{{ site.community.mail_vorstand }}</a></li>
	</ul>

	<p>Dem Vorstand gehören aktuell an:</p>

	<ul>
	{% for subcom in site.community.vorstand %}
		<li>{{ subcom }}</li>
	{% endfor %}
	</ul>
</section>

<section class="box">
    <h2>Weitere Kanäle</h2>
    <p>Es gibt viele weitere Kontaktwege. Eine Übersicht aller unserer Kanäle findest du auf unserer allgemeinen <a href="/kontakt/">Kontaktseite</a>.</p>
</section>