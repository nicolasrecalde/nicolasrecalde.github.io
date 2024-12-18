---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit cayman-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---
<style>
.container {
display: flex;
align-items: center;
justify-content: center
}

img {
min-width: 200%;
min-height:200%;
}

.text {
padding-left: 6rem;
}
</style>
<div class="container">
  <div class="image">
    <img src="{{"/images/ProfileP.png"| absolute_url}}" style="width:200%"/>
  </div>
  <div class="text">
    Welcome to my website! I am Nico, PhD researcher at Cardiff University. My work focuses on modelling mantle evolution with Noble Gases constraints (Helium and Argon). Here you can find all about my previous and ongoing research. Hope you enjoy!
    <br>
    <br>
      I will be soon looking for a Post-Doc position, feel free to <a href="/contact"> contact me!</a>
  </div>
</div>

