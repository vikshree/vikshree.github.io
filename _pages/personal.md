---
layout: page
title: Personal
permalink: /personal/
description: A few things I enjoy away from the desk.
nav: true
nav_order: 6
---

<!-- pages/personal.md -->
<!--
  Photos live in assets/img/personal/. Each hobby uses the same file twice:
  once in its tile, once (with a `caption`) in its expanded panel.

  Each hobby is a TILE followed immediately by its PANEL, so on a phone the
  description opens directly under the tile you tapped. On desktop the panels
  are pushed below the whole row of tiles by `order` (see _sass/_components.scss).

  To add a SECOND photo to a hobby, copy one of the `include figure.liquid`
  blocks inside that hobby's panel and wrap both in `<div class="col-6">`.
  To add a fourth hobby, copy one tile *and* its panel, and give both the
  same new id (e.g. #hobby-cooking).
-->

<div class="hobbies">
  <div class="row" id="hobby-panels">

    <!-- ===================== Running ===================== -->
    <div class="col-12 col-md-4 hobby-col">
      <button
        type="button"
        class="hobby-tile"
        data-toggle="collapse"
        data-target="#hobby-running"
        aria-expanded="false"
        aria-controls="hobby-running"
      >
        <div class="card h-100 hoverable">
          {%
            include figure.liquid
            loading="eager"
            path="assets/img/personal/vikram_la_marathon_2026.jpg"
            sizes="400px"
            alt="Running"
            class="card-img-top"
          %}
          <div class="card-body">
            <h3 class="card-title">
              Running
              <i class="fa-solid fa-chevron-down hobby-chevron"></i>
            </h3>
          </div>
        </div>
      </button>
    </div>

    <div class="collapse hobby-panel col-12" id="hobby-running" data-parent="#hobby-panels">
      <div class="hobby-panel-inner row align-items-start">
        <div class="col-12 col-md-5 hobby-photo mb-3 mb-md-0">
          {%
            include figure.liquid
            loading="lazy"
            path="assets/img/personal/vikram_la_marathon_2026.jpg"
            sizes="600px"
            alt="Running"
            caption="Los Angeles, 2026"
            class="img-fluid rounded z-depth-1"
            zoomable=true
          %}
        </div>
        <div class="col-12 col-md-7">
          <h4 class="hobby-heading">Running</h4>
          <p>
            I used to run occasionally, but it became a real habit at the start of 2022, when peer pressure dragged me into a 10K. Since then, I've kept chasing races across different cities - most recently, the LA Marathon in 2026.
          </p>
        </div>
      </div>
    </div>

    <!-- ===================== Hiking ===================== -->
    <div class="col-12 col-md-4 hobby-col">
      <button
        type="button"
        class="hobby-tile"
        data-toggle="collapse"
        data-target="#hobby-hiking"
        aria-expanded="false"
        aria-controls="hobby-hiking"
      >
        <div class="card h-100 hoverable">
          {%
            include figure.liquid
            loading="eager"
            path="assets/img/personal/vikram_bryce_canyon_2022.jpg"
            sizes="400px"
            alt="Hiking"
            class="card-img-top"
          %}
          <div class="card-body">
            <h3 class="card-title">
              Hiking
              <i class="fa-solid fa-chevron-down hobby-chevron"></i>
            </h3>
          </div>
        </div>
      </button>
    </div>

    <div class="collapse hobby-panel col-12" id="hobby-hiking" data-parent="#hobby-panels">
      <div class="hobby-panel-inner row align-items-start">
        <div class="col-12 col-md-5 hobby-photo mb-3 mb-md-0">
          {%
            include figure.liquid
            loading="lazy"
            path="assets/img/personal/vikram_bryce_canyon_2022.jpg"
            sizes="600px"
            alt="Hiking"
            caption="Bryce Canyon National Park, 2022"
            class="img-fluid rounded z-depth-1"
            zoomable=true
          %}
        </div>
        <div class="col-12 col-md-7">
          <h4 class="hobby-heading">Hiking</h4>
          <p>
            Hiking has become one of my favorite mood-elevators. I'm especially drawn to the US National Parks system and have been lucky to explore a handful of them over the past decade. Next on the list: making my way through a few national parks in Asia.
          </p>
        </div>
      </div>
    </div>

    <!-- ===================== Music ===================== -->
    <div class="col-12 col-md-4 hobby-col">
      <button
        type="button"
        class="hobby-tile"
        data-toggle="collapse"
        data-target="#hobby-music"
        aria-expanded="false"
        aria-controls="hobby-music"
      >
        <div class="card h-100 hoverable">
          {%
            include figure.liquid
            loading="eager"
            path="assets/img/personal/vikram_independence_day_2019_ithaca.jpg"
            sizes="400px"
            alt="Music"
            class="card-img-top"
          %}
          <div class="card-body">
            <h3 class="card-title">
              Music
              <i class="fa-solid fa-chevron-down hobby-chevron"></i>
            </h3>
          </div>
        </div>
      </button>
    </div>

    <div class="collapse hobby-panel col-12" id="hobby-music" data-parent="#hobby-panels">
      <div class="hobby-panel-inner row align-items-start">
        <div class="col-12 col-md-5 hobby-photo mb-3 mb-md-0">
          {%
            include figure.liquid
            loading="lazy"
            path="assets/img/personal/vikram_independence_day_2019_ithaca.jpg"
            sizes="600px"
            alt="Music"
            caption="Ithaca, 2019"
            class="img-fluid rounded z-depth-1"
            zoomable=true
          %}
        </div>
        <div class="col-12 col-md-7">
          <h4 class="hobby-heading">Music</h4>
          <p>
            I'm trained in playing the tabla, and have a deep appreciation for Indian classical music, both Hindustani and Carnatic traditions. During my time in Ithaca, SPICMACAY (a student organization dedicated to promoting Indian classical arts) gave me the joy of witnessing many fabulous performances.
          </p>
        </div>
      </div>
    </div>

  </div>
</div>
