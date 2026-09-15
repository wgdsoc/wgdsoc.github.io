---
layout: page
title: Gallery
---

<img src="/wgd-assets/lfs/gallery/card.svg">

See games made by our members and executives during our jams. [Contact us](/contact-us/) if you think we've missed something, or if you've made a game / taken a picture to be featured. All the pictured games (alongside many more) are available to play on [itch.io](https://wgdsoc.itch.io/).

<div class="gallery">
{% for image in site.static_files %}
  {% if image.path contains "/wgd-assets/lfs/gallery/unlinked/" %}
    <a href="{{ image.path }}"><img src="{{ image.path }}"></a>
  {% endif %}
{% endfor %}

<a href="https://floppygames.itch.io/the-amazing-adventures-of-phillip-sunshine"><img src="/wgd-assets/lfs/gallery/linked/amazing-adventures-phillip-sunshine.png"></a>
<a href="https://simplyana.itch.io/dungeon-dodge"><img src="/wgd-assets/lfs/gallery/linked/dungeon-dodge.png"></a>
</div>
