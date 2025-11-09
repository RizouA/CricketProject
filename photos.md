---
layout: default
title: "Φωτογραφικό Υλικό"
permalink: /photos/
---


<h2 style="text-align:center; color:#3b2b1d;">📸 Φωτογραφικό Υλικό</h2>
<p style="text-align:center; font-style:italic; margin-bottom:1.5rem;">
  Στιγμές από συλλόγους, γήπεδα και δράσεις που σχετίζονται με το ελληνικό κρίκετ.
</p>

<div class="gallery" style="display:grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap:1.5rem; justify-items:center;">

  {% for i in (1..12) %}
  <a class="gallery-item" href="{{ '/assets/images/photo' | append: i | append: '.jpg' | relative_url }}" target="_blank" style="text-decoration:none; color:#3b2b1d;">
    <div style="background:#fdf6ed; border-radius:10px; box-shadow:0 2px 6px rgba(0,0,0,0.1); overflow:hidden; transition:transform 0.2s;">
      <img src="{{ '/assets/images/photo' | append: i | append: '.jpg' | relative_url }}" alt="Στιγμιότυπο από το ελληνικό κρίκετ" style="width:100%; display:block; border-bottom:1px solid #e0d5c3;">
      <div class="gallery-caption" style="padding:0.8rem;">
        <strong>Στιγμιότυπα από το ελληνικό κρίκετ</strong><br>
        Φωτογραφικό υλικό από αγώνες, προπονήσεις και δράσεις συλλόγων, στο πλαίσιο της ιστορικής παρουσίας του κρίκετ στην Ελλάδα.
      </div>
    </div>
  </a>
  {% endfor %}

</div>

<style>
.gallery-item:hover div {
  transform: scale(1.03);
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}
</style>
