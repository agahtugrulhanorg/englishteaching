---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Sıfırdan Başla"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'Akademik literatürdeki öğretme teknikleri ile size sıfırdan ingilizce öğretiyoruz'
widget2:
  title: "Sınavlara Hazırlık"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'Tecrübeli kadromuz ile sizi sınavlara en iyi şekilde hazırlıyoruz.<br/>1. TOEFL <br/>2. IELTS <br/>3. YDS <br/>4. YOKDİL<br/>5. LYS-TEOG'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Çok Yönlü Eğitim"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: 'Özel derslerimiz sonrasında sadece gramer odaklı değil, <b> konuşma kalıpları, telafuz dersleri, akademik ingilizce yetkinliği, amerikan kültürünü tanıma, idiomatik konuşmayı geliştirecek deyimleri öğrenme </b> gibi konular da işlenir ve ilgili kaynaklar ve egzersizler size verilir. Özel ders için: <a href="http://facebook.com/agahtugrulhan">@agahtugrulhan</a>.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
