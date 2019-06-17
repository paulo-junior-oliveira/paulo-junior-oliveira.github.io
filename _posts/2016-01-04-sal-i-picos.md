---
layout: default
title: "Sal i Picos"
date: 2016-01-04
image: /assets/img/work/salipicos_thumbnail.jpg
category: portfolio
show_category: Branding | Packaging
---

<div class="main-outer">
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-12">
                <div class="title-image"><img src="{{ "/assets/img/work/salipicos_apresentecao.png" | prepend: site.baseurl }}" alt="Sal i Picos"></div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-9">
                <div class="description">
                    <h1>Sal i Picos</h1>
                    <ul class="categories">
                        <li>Branding</li>
                        <li>Packaging</li>
                    </ul>
                    <p>Design do logótipo "Sal i Picos" assim como design das embalagens (frascos e sacos).</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="details">
                    <ul>
                        <li>Data:<span>Maio 2016</span></li>
                        <li>Cliente:<span>Pitada Primária</span></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
                <div class="project-image">
                    <img src="{{ "/assets/img/work/salipicos_positivo.png" | prepend: site.baseurl }}" alt="Sal i Picos">
                </div>
            </div>
            <div class="col-md-6">
                <div class="project-image">
                    <img src="{{ "/assets/img/work/salipicos_negativo.png" | prepend: site.baseurl }}" alt="Sal i Picos">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-12">
                <div class="carousel slide" id="project-carousel">
                    <ol class="carousel-indicators">
                        <li class="active" data-target=".carousel" data-slide-to="0"></li>
                        <li data-target=".carousel" data-slide-to="1"></li>
                        <li data-target=".carousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="item active"><img src="{{ "/assets/img/work/salipicos_slide1.png" | prepend: site.baseurl }}" alt="Sal i Picos"></div>
                        <div class="item"><img src="{{ "/assets/img/work/salipicos_slide2.png" | prepend: site.baseurl }}" alt="Sal i Picos"></div>
                        <div class="item"><img src="{{ "/assets/img/work/salipicos_slide3.png" | prepend: site.baseurl }}" alt="Sal i Picos"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<script>
    function setBodyId() {
        document.body.id = 'project-page';
    }
    
    window.onload = setBodyId;
    window.onresize = setBodyId;
</script>