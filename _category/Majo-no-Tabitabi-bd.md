---
layout: category
title: Majo no Tabitabi (BD)
epsname: Penyihir Jalan-Jalan
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1003664978689130557/mpv-shot0075.jpg
---

Terinspirasi dari buku favorit yang sering ia baca, Elaina berusaha melihat semua isi dunia. Seperti sebuah daun yang tertiup angin, dia mengembara dari satu negeri ke negeri lain, karena ingin memuaskan rasa ingin tahunya dan mencari pengalaman yang baru. Dia dihadapkan dengan berbagai macam sifat manusia, entah aneh, atau emosional. Karena eksplorasi rasa ingin tahunya mendorongnya untuk terus mengembara, Kemana lagi Elaina akan pergi?

Soloyolo: Noromi

Unduh

---
  <ul>
    {% for post in site.categories['Majo-no-Tabitabi-bd'] %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{% if post.epsname %}Episode {{ post.eps }}: {{ post.epsname }}{% else %}Episode {{ post.eps }}: {{ page.title }}{% endif %}</a></li>
  {% endfor %}
  </ul>