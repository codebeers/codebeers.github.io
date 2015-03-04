---
layout: page
permalink: /
---

<img src="{{ site.baseurl }}/img/header-code-beers.png" alt="">

**Code Beers** is a Developers meeting created to exchange knowledge
about technology, tendencies and pratices while drinking beer.

The meetings occurs from time to time near Porto Alegre - RS. Keep in
touch with our website and contacts to know when and where is the next.

## Latest posts

<ul class="post-list post-list-small">
  {% for post in site.posts %}
    <li>
      <a class="post-link post-link-small" href="{{ post.url | prepend: site.baseurl }}">
        {{ post.title }}
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
      </a>
    </li>
  {% endfor %}
</ul>

## Next meeting

<ul class="banners">
  <li class="schedule">
    <i class="watermark fa fa-clock-o"></i>
    <div class="info">
      <h3>March, 17th <br>
      7:00pm</h3>
    </div>
  </li>
  <li class="schedule">
    <i class="watermark fa fa-map-marker"></i>
    <div class="info">
    <h3>Campus 3 <small>Rock Bar</small></h3>
      Rua Santos, 792 <br>
      Novo Hamburgo, RS
    </div>
  </li>
  <li class="schedule">
    <i class="watermark fa fa-check"></i>
    <div class="info">
        <h3 markdown="1">[Register][eventick]</h3>
        Registration is not required, but will
        help us to improve the meetup.
    </div>
  </li>
  <li class="schedule">
    <i class="watermark fa fa-video-camera"></i>
    <div class="info">
        <h3 markdown="1">[Submit a talk][call-papers]</h3>
        For presenting on the meeting
    </div>
  </li>
  <li class="schedule">
    <i class="watermark fa fa-github"></i>
    <div class="info">
        <h3 markdown="1">[Help the project][github]</h3>
        On github
    </div>
  </li>
</ul>

## Sponsors

<ul class="sponsor-logos">
  <li><a href="http://codeminer42.com"><img src="/img/logo-codeminer.png" alt="codeminer"></a></li>
  <li><a href="http://getupcloud.com"><img src="/img/logo-getup.png" alt="getupcloud"></a></li>
</ul>

Check out [how to be a sponsor][sponsor].

[sponsor]: {% post_url 2015-02-10-be-a-sponsor %}

[eventick]: http://eventick.com.br/code-beers

[call-papers]: {% post_url 2015-02-03-call-for-papers %}

[github]: {{ site.github_url }}
