---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />

<style>
.swiper {
  width: 100%;
  margin-bottom: 40px;
}
.swiper-slide img {
  width: 100%;
  height: 260px;
  object-fit: cover;
  border-radius: 6px;
  display: block;
}
.gallery-caption {
  font-size: 0.85em;
  color: #666;
  text-align: center;
  margin-top: 6px;
}
.swiper-button-next,
.swiper-button-prev {
  color: #555;
}
.swiper-pagination-bullet-active {
  background: #555;
}
</style>

Research Events
======

<div class="swiper" id="swiper-research">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/NCROEP_2026.jpeg" alt="NCROEP 2026" />
      <p class="gallery-caption">NCROEP Symposium 2026</p>
    </div>
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/IISE 2025.jpeg" alt="IISE 2025" />
      <p class="gallery-caption">IISE Annual Conference 2025</p>
    </div>
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/INOFRMS-2025.jpeg" alt="INFORMS 2025" />
      <p class="gallery-caption">INFORMS Annual Meeting 2025</p>
    </div>
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/INOFRMS-2024.jpg" alt="INFORMS 2024" />
      <p class="gallery-caption">INFORMS Annual Meeting 2024</p>
    </div>
  </div>
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
  <div class="swiper-pagination"></div>
</div>

Student Achievement
======

<div class="swiper" id="swiper-achievement">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/NCROEP Symposium 2026-poster.jpeg" alt="NCROEP 2026 Poster" />
      <p class="gallery-caption">NCROEP Symposium 2026 — Poster Session</p>
    </div>
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/NCROEP Symposium 2026-poster winner.jpg" alt="NCROEP 2026 Poster Award" />
      <p class="gallery-caption">NCROEP Symposium 2026 — Poster Award</p>
    </div>
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/Omer_defense.jpeg" alt="Omer's Thesis Defense" />
      <p class="gallery-caption">Omer Rehman — MS Thesis Defense, 2026</p>
    </div>
  </div>
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
  <div class="swiper-pagination"></div>
</div>

Lab Life
======

<div class="swiper" id="swiper-lablife">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/Gathering_Fall26.jpeg" alt="Lab Gathering Fall 2026" />
      <p class="gallery-caption">Lab Gathering — Fall 2026</p>
    </div>
    <div class="swiper-slide">
      <img src="{{ site.baseurl }}/assets/images/Gathering_NCROEP26.jpeg" alt="Lab Gathering NCROEP 2026" />
      <p class="gallery-caption">Lab Gathering — NCROEP 2026</p>
    </div>
  </div>
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
  <div class="swiper-pagination"></div>
</div>

<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
<script>
['swiper-research', 'swiper-achievement', 'swiper-lablife'].forEach(function(id) {
  new Swiper('#' + id, {
    loop: true,
    autoplay: {
      delay: 3500,
      disableOnInteraction: false,
      pauseOnMouseEnter: true,
    },
    navigation: {
      nextEl: '#' + id + ' .swiper-button-next',
      prevEl: '#' + id + ' .swiper-button-prev',
    },
    pagination: {
      el: '#' + id + ' .swiper-pagination',
      clickable: true,
    },
    slidesPerView: 1,
    spaceBetween: 10,
  });
});
</script>
