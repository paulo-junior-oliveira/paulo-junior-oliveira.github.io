---
layout: default
title: "Moon Light"
date: 2016-01-01
image: /assets/img/work/moon_light_thumbnail.jpg
category: portfolio
show_category: Fotografia
---

<div class="main-outer">
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-12">
                <div class="title-image"><img src="{{ "/assets/img/work/moon_light.jpg" | prepend: site.baseurl }}" alt="Moon Light"></div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-9">
                <div class="description">
                    <h1>Moon Light</h1>
                    <ul class="categories">
                        <li>Fotografia</li>
                    </ul>
                </div>
            </div>
            <div class="col-md-3">
                <div class="details">
                    <ul>
                        <li>Data:<span>Novembro 2014</span></li>
                        <li>Local:<span>Vila do Conde</span></li>
                    </ul>
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