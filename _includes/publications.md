<h2 id="publications">Selected Publications &amp; Manuscripts</h2>

<div class="publications">
<ol class="bibliography">
{% for publication in site.data.publications.main %}
  <li>
    <div class="pub-row">
      <div style="width: 100%;">
        <div class="title">
          {% if publication.paper %}<a href="{{ publication.paper }}" target="_blank" rel="noopener">{{ publication.title }}</a>{% else %}{{ publication.title }}{% endif %}
        </div>
        <div class="author">{{ publication.authors }}</div>
        <div class="periodical">{{ publication.conference }}</div>
        <div class="links">
          {% if publication.paper %}<a href="{{ publication.paper }}" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener" style="font-size:12px;">Paper</a>{% endif %}
          {% if publication.code %}<a href="{{ publication.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener" style="font-size:12px;">Code</a>{% endif %}
          {% if publication.project %}<a href="{{ publication.project }}" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener" style="font-size:12px;">Project</a>{% endif %}
        </div>
        {% if publication.notes %}<div class="pub-note">{{ publication.notes }}</div>{% endif %}
      </div>
    </div>
  </li>
  <br>
{% endfor %}
</ol>
</div>
