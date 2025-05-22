---
layout: archive
permalink: /publications/
author_profile: true
---
{% comment %} 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Preprints
{% include base_path %}

{% for post in site.publications reversed %}{% if post.type == "preprint" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

## Conference articles

{% for post in site.publications reversed %}{% if post.type == "conf" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

## Journal articles
{% include base_path %}

{% for post in site.publications reversed %}{% if post.type == "journal" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

## PhD Thesis
{% include base_path %}
{% for post in site.publications reversed %}{% if post.type == "thesis" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}
{% endcomment %}

## Preprint articles
<p><iframe src="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=Quoc-Tung%2C+Le&idHal=quoc-tung-le&annee_publideb=2020&typdoc=('UNDEFINED')&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_vignette=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuRubriqueEncadre.css" width="100%" height="700"></iframe></p>

## Conference articles
<p><iframe src="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=Quoc-Tung%2C+Le&idHal=quoc-tung-le&annee_publideb=2020&typdoc=(%27COMM%27)&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_vignette=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuRubriqueEncadre.css" width="100%" height="700"></iframe></p>

## Journal articles
<p><iframe src="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=Quoc-Tung%2C+Le&idHal=quoc-tung-le&annee_publideb=2020&typdoc=('ART')&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_vignette=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuRubriqueEncadre.css" width="100%" height="700"></iframe></p>

## Ph.D. Thesis
<p><iframe src="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=Quoc-Tung%2C+Le&idHal=quoc-tung-le&annee_publideb=2020&typdoc=(%27THESE%27)&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_vignette=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuRubriqueEncadre.css" width="100%" height="250"></iframe></p>