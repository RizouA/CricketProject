---
layout: default
title: "Φωτογραφικό Υλικό"
permalink: /photos/
---

<style>
  .photo-page {
    max-width: 1100px;
    margin: 0 auto 3rem auto;
    padding: 1rem;
  }

  .photo-page h1 {
    text-align: center;
    margin-bottom: 0.25rem;
  }

  .photo-page p.subtitle {
    text-align: center;
    color: #6b4b2e;
    font-style: italic;
    margin-bottom: 2rem;
  }

  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 18px;
  }

  .gallery-item {
    position: relative;
    overflow: hidden;
    border-radius: 14px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.2);
    background: #fdf6e7;
    border: 1px solid #d2b48c;
  }

  .gallery-item img {
    width: 100%;
    display: block;
    transition: transform 0.4s ease, filter 0.4s ease;
  }

  .gallery-item:hover img {
    transform: scale(1.05);
    filter: sepia(0.4);
  }

  .gallery-caption {
    padding: 0.5rem 0.75rem 0.75rem;
    font-size: 0.9rem;
    color: #4b3621;
    background: #fdf6e7;
  }

  .gallery-caption strong {
    display: block;
    margin-bottom: 0.1rem;
  }

  /* Lightbox (CSS only, με :target) */
  .lightbox {
    display: none;
    position: fixed;
    z-index: 9999;
    inset: 0;
    background: rgba(0,0,0,0.85);
    align-items: center;
    justify-content: center;
  }

  .lightbox:target {
    display: flex;
  }

  .lightbox-content {
    max-width: 90vw;
    max-height: 90vh;
    background: #fdf6e7;
    border-radius: 12px;
    padding: 0.75rem;
    box-shadow: 0 4px 16px rgba(0,0,0,0.6);
    border: 1px solid #d2b48c;
  }

  .lightbox-content img {
    max-width: 100%;
    max-height: 80vh;
    display: block;
    margin: 0 auto;
  }

  .lightbox-caption {
    margin-top: 0.5rem;
    font-size: 0.9rem;
    color: #4b3621;
    text-align: center;
  }

  .lightbox-close {
    position: fixed;
    top: 12px;
    right: 18px;
    font-size: 2rem;
    color: #fdf6e7;
    text-decoration: none;
  }

  @media (max-width: 600px) {
    .photo-page {
      padding: 0.5rem;
    }
  }
</style>

<div class="photo-page" id="gallery">

  <h1>📸 Φωτογραφικό Υλικό</h1>
  <p class="subtitle">
    Στιγμές από συλλόγους, γήπεδα και δράσεις που σχετίζονται με το ελληνικό κρίκετ.
  </p>

  <div class="gallery-grid">

    <!-- ΦΩΤΟ 1 -->
    <a class="gallery-item" href="#img1">
      <img src="/assets/images/photo1.jpg" alt="Αγώνας κρίκετ στην Κέρκυρα">
      <div class="gallery-caption">
        <strong>Αγώνας κρίκετ στην Κέρκυρα</strong>
        Στιγμιότυπο από διοργάνωση της ΕΛ.Ο.Κ. στο ιστορικό γήπεδο.
      </div>
    </a>

    <!-- ΦΩΤΟ 2 -->
    <a class="gallery-item" href="#img2">
      <img src="/assets/images/photo2.jpg" alt="Προπόνηση Athens Cricket Academy">
      <div class="gallery-caption">
        <strong>Προπόνηση Athens Cricket Academy</strong>
        Νέοι αθλητές σε προπόνηση, στο πλαίσιο ανάπτυξης του αθλήματος.
      </div>
    </a>

    <!-- ΦΩΤΟ 3 -->
    <a class="gallery-item" href="#img3">
      <img src="/assets/images/photo3.jpg" alt="Ομαδική φωτογραφία συλλόγου">
      <div class="gallery-caption">
        <strong>Ομαδική φωτογραφία συλλόγου</strong>
        Αναμνηστική φωτογραφία μετά από αγώνα πρωταθλήματος.
      </div>
    </a>

    <!-- ΦΩΤΟ 4 (προαιρετικά, μπορείς να προσθέσεις όσες θέλεις) -->
    <a class="gallery-item" href="#img4">
      <img src="/assets/images/photo4.jpg" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Δράση για νέους</strong>
        Εκπαιδευτικό πρόγραμμα γνωριμίας με το κρίκετ.
      </div>
    </a>

  </div>
</div>

<!-- LIGHTBOX ΖΩΝΕΣ (μία για κάθε εικόνα) -->

<div id="img1" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="/assets/images/photo1.jpg" alt="Αγώνας κρίκετ στην Κέρκυρα">
    <div class="lightbox-caption">
      Αγώνας κρίκετ στην Κέρκυρα – διοργάνωση της ΕΛ.Ο.Κ. στο ιστορικό γήπεδο.
    </div>
  </div>
</div>

<div id="img2" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="/assets/images/photo2.jpg" alt="Προπόνηση Athens Cricket Academy">
    <div class="lightbox-caption">
      Προπόνηση της Athens Cricket Academy με συμμετοχή νεαρών αθλητών.
    </div>
  </div>
</div>

<div id="img3" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="/assets/images/photo3.jpg" alt="Ομαδική φωτογραφία συλλόγου">
    <div class="lightbox-caption">
      Ομαδική φωτογραφία συλλόγου μετά από παιχνίδι πρωταθλήματος.
    </div>
  </div>
</div>

<div id="img4" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="/assets/images/photo4.jpg" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Προπονητική δράση για νέους/νέες ως εισαγωγή στο κρίκετ.
    </div>
  </div>
</div>
