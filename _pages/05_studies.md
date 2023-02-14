---
layout: default
title: Studies
permalink: /studies/
---

<h1> Would you like to register for our study? </h1> 

Please don't hesitate to write us:
<form action="https://formspree.io/f/mvoybwjv" method="POST">
    <input type="text" width=100 name="email" placeholder="Your E-Mail"><br>
    <input type="text" width=50 name="name" placeholder="Your Name"><br>
    <textarea type="text" width="50" name="content" rows="5" placeholder="Your Message"></textarea><br>
    <input type="hidden" name="_next" value="{{ site.baseurl }}/danke.html" />
    <input type="hidden" name="_subject" value="Registration " />
    <input type="submit" value="send">
</form>

