---
layout: page
title: ¿Qué es Crowdsourcing?
description: "Información acerca del Crowdsourcing y el Crowdfunding y sus diferencias."
keywords: "crowdsource, crowdsourcing, crowd sourcing, crowdsourced, crowdfunding, crowd funding, mechanical turk, subcontratación en masa, financiación en masa, masa social, financiación colectiva, turco mecánico"
tagline: La nueva forma de trabajo en Internet
---


En la actualidad, gracias a la revolución de Internet ha surgido una **nueva forma de trabajo**
llamada [**crowdsourcing**](http://es.wikipedia.org/wiki/Crowdsourcing). El término **crowdsourcing** hace referencia a una forma de delegación 
o subcontratación de un trabajo a una **masa de gente**.

Visión general
--------------
El funcionamiento del **crowdsourcing** en internet es relativamente simple y suele estar orientado
a la **resolución de pequeños problemas** por los que se puede obtener alguna remuneración, prestigio
o simplemente satisfacción intelectual.

Dentro del **crowdsourcing** existen dos variantes:

+ Proposición de un **reto** a una masa de personas que proponen soluciones y revisan dichas soluciones para obtener la mejor.
+ Asignación de tareas a **individuos concretos** de una masa, es decir, se dispone de un **conjunto de tareas por hacer** del cual se asignan a un individuo algunas o se le permite escoger entre ellas las que desee.

Polémica del **crowdsourcing**
--------------------------
El **crowdsourcing** ha despertado bastante polémica debido principalmente a que una comunidad hace un trabajo de modo muy barato,
muchas veces por un precio muy por debajo de los salarios para otra parte que lo explota comercialmente obteniendo generalmente
altos beneficios por ello.

<div class="row">
	<div class="span4">
		<img src="assets/img/amazon_mechanical_turk.gif" alt="Logo de Amazon Mechanical Turk" title="Logo de Amazon Mechanical Turk" />
	</div>
	<div class="span10">
		<p>Proyectos como <a href="https://www.mturk.com"><strong>Amazon Mechanical Turk</strong></a> se publicitan a los <strong>crowdsourcers</strong> con mensajes como el siguiente:</p>
		<blockquote>
		<p><em>Obtenga una fuerza de trabajo escalable y bajo demanda</em></p>
		</blockquote>
	</div>
</div>

La remuneración de las tareas es completamente nula o irrisoria, apenas alcanzan unos pocos centavos
de dólar por tareas que pueden requerir media hora, cuando la media hora de trabajo de cualquier trabajador podría situarse entorno a
los tres dólares y medio.


## Temas disponibles

<ul class="posts">
  {% for page in site.pages %}
    {% if page.group == 'navigation' %}
    <li><a href="{{ BASE_PATH }}{{ page.url }}">{{ page.title }}</a> &laquo; <span>{{ site.authors[page.author].name }}</span></li>
    {% endif %}
  {% endfor %}
</ul>

<div class="hreview-aggregate">
   <span class="item">
     <span class="fn">{{ page.title }}</span>
   </span>
   <span class="rating">
	Puntuación: <span class="average">4.3</span> de <span class="best">5</span>
   </span>
   basado en <span class="votes">3</span> votos del grupo 2012-22.
</div>