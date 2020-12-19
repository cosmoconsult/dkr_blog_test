---

title: "About COSMO Consult inofficial Blog"
permalink: "/about/"
---

This blog represents the versatility of our people and knowledge at COSMO Consult.

It's the home of the following authors:

<!-- Authors are sorted by filename -->
<ul class="taxonomy__index">
    {% for currentAuthor in site.authors %}
      <li>
        <a href="{{ currentAuthor.url | relative_url}}">
          <strong>{{site.data.authors[currentAuthor.author].name}}</strong> <span class="taxonomy__count"></span>
        </a>
      </li>
    {% endfor %}
</ul>