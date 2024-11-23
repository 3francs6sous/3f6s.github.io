---
title: Equipe
layout: home
description: "L'équipe"
---
<link href="https://cdn.jsdelivr.net/npm/modern-normalize@v2.0.0/modern-normalize.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" crossorigin="anonymous">

# Notre nouveau bureau !

<div class="row">
    {% for hi in site.data.infos %}
    <div class="col-sm-2 mb-2 mb-sm-0">
        <div class="card shadow-sm" style="width: 14rem;">
            <img src="{{ hi.image }}" class="card-img-top" alt="">
            <div class="card-body">
                <h5 class="card-title">{{ hi.name }}</h5>
                <p class="card-text">{{ hi.content }}</p>
            </div>
        </div>
    </div>
    {% endfor %}
</div>
