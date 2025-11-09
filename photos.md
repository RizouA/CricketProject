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

   
    <a class="gallery-item" href="#photo1">
      <img src="{{ '/assets/images/photo1.jpg' | relative_url }}" alt="Αγώνας κρίκετ στην Κέρκυρα">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
         Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>


    <a class="gallery-item" href="#photo2">
      <img src="{{ '/assets/images/photo2.jpg' | relative_url }}" alt="Προπόνηση Athens Cricket Academy">
      <div class="gallery-caption">
       <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>


    <a class="gallery-item" href="#img3">
      <img src="{{ '/assets/images/photo3.jpg' | relative_url }}" alt="Ομαδική φωτογραφία συλλόγου">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

  
    <a class="gallery-item" href="#img4">
      <img src="{{ '/assets/images/photo4.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

        <a class="gallery-item" href="#img5">
      <img src="{{ '/assets/images/photo5.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

        <a class="gallery-item" href="#img6">
      <img src="{{ '/assets/images/photo6.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

        <a class="gallery-item" href="#img7">
      <img src="{{ '/assets/images/photo7.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

        <a class="gallery-item" href="#img8">
      <img src="{{ '/assets/images/photo8.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
       <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

        <a class="gallery-item" href="#img9">
      <img src="{{ '/assets/images/photo9.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

        <a class="gallery-item" href="#img10">
      <img src="{{ '/assets/images/photo10.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

        <a class="gallery-item" href="#img11">
      <img src="{{ '/assets/images/photo11.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

        <a class="gallery-item" href="#img12">
      <img src="{{ '/assets/images/photo12.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
      <div class="gallery-caption">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </a>

  </div>
</div>

<!-- LIGHTBOX ΖΩΝΕΣ (μία για κάθε εικόνα) -->

<div id="img1" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo1.jpg' | relative_url }}" alt="Αγώνας κρίκετ στην Κέρκυρα">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img2" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo2.jpg' | relative_url }}" alt="Προπόνηση Athens Cricket Academy">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img3" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo3.jpg' | relative_url }}" alt="Ομαδική φωτογραφία συλλόγου">
    <div class="lightbox-caption">
     Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img4" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo4.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img5" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo5.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img6" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo6.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img7" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo4.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img8" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo7.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img9" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo8.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img10" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo9.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img11" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo10.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>

<div id="img12" class="lightbox">
  <a href="#gallery" class="lightbox-close">&times;</a>
  <div class="lightbox-content">
    <img src="{{ '/assets/images/photo11.jpg' | relative_url }}" alt="Προπονητική δράση για νέους">
    <div class="lightbox-caption">
      Στιγμιότυπα από το ελληνικό κρίκετ
    </div>
  </div>
</div>


