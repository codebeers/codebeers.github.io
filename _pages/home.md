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
  {% for post in site.posts limit: 4 %}
    <li>
      <a class="post-link post-link-small" href="{{ post.url | prepend: site.baseurl }}">
        {{ post.title }}
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
      </a>
    </li>
  {% endfor %}
</ul>

<ul class="banners">
  <li class="schedule">
    <i class="watermark fa fa-github"></i>
    <div class="info">
        <h3 markdown="1">[Help the project][github]</h3>
        On github
    </div>
  </li>
</ul>

Check out [how to be a sponsor][sponsor].

[sponsor]: {% post_url 2015-02-10-be-a-sponsor %}

[eventick]: http://eventick.com.br/code-beers

[programme]: {% post_url 2015-03-10-agenda %}

[github]: {{ site.github_url }}
