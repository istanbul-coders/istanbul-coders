---
layout: default
---

<div class="row">
  <div class="col-md-7">

    <h2>Neler yaptık?</h2>

    <p>Bu güne kadar olan 250'nin üzerindeki diğer buluşmalarımıza göz atmak için <a href="http://www.meetup.com/Istanbul-Hackers#past">meetup</a> sayfamıza bakabilirsiniz.</p>


  </div>
</div>

{% for post in site.posts %}
{% if post.date < site.time %}
<div class="row">
  <div class="col-md-5"><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></div>
  <div class="col-md-1">{{ post.date | date: "%d.%m.%Y" }}</div>
</div>
{% endif %}
{% endfor %}
