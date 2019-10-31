---
title: Talks
---

{% include talks/speakers.html %}

<div class="limit limit--top-margin">

  <div class="talks-intro">
    <h1 class="talks-intro__title">
      Talks
    </h1>
  </div>

  <div class="talks-intro">
    <h2 class="talks-intro__date">
      May 10th-11th
    </h2>
  </div>

  {% for talk in site.data.talks %}
    {% include talks/talk.html talk=talk %}
  {% endfor %}

</div>