---
layout: home
title: 3 Francs 6 Sous
description: Economie sociale et solidaire, Insertion, seconde main.
---
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

<h1 style="text-align: center;">Infos pratiques</h1>
<h2 style="text-align: center;">Horaires</h2>
<table class="table table-striped table-bordered">
  <thead>
    <tr>
      <th scope="col">Jour</th>
      <th scope="col">Horaires</th>
    </tr>
  </thead>
  <tbody>
    {% for hi in site.data.horaires %}
      <tr class="table-{{ hi.status }}">
        <th scope="row">{{ hi.name }}</th>
        <td>{{ hi.horaires }}</td>
      </tr>
    {% endfor %}
  </tbody>
</table>

<h2 style="text-align: center;">Plan</h2>
<div class="row">
    <div class="col d-flex justify-content-center">
              <iframe class="embed-responsive-item"  width="100%" height="300px" frameborder="0" allowfullscreen allow="geolocation" src="//umap.openstreetmap.fr/fr/map/3f6s_1149485?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=true&editMode=disabled&moreControl=false&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false&captionMenus=true&datalayers=295a0123-a9e9-4d6f-80c4-1e595f8f2787#16/45.8218/-0.7797"></iframe>
               </div>
  </div>

<h2 style="text-align: center;">Nous contacter</h2>

  <div>
        <p class="text-center">
          <a href="mailto:asso.3francs6sous@gmail.com?subject=[BENEVOLAT]" target="_blank" class="btn btn-primary">Je deviens bénévole</a>
          <a href="mailto:asso.3francs6sous@gmail.com?subject=[DONS]" target="_blank" class="btn btn-primary">Je donne des objets</a>
        </p>
      </div>