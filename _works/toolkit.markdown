---
layout: post-toolkit
title:  "Toolkit"
thumbnail: toolkit.png
date:   2016-01-10
tag: project
---

<div class="body-content">
  <div class="row">
    <div class="small-12 columns">
      <p class="hero-text">A open set of web development resources to help you develop better and quicker with simple styling blocks.</p>
    </div>
  </div>
  
  <div class="row" id="tool-index">
    {% for tool in site.toolkit %}
      <div class="small-12 medium-4 columns">
        <a class="post-link" href="{{ tool.url | prepend: site.baseurl }}">
          <div class="thumbnail-container">
            <img class="thumbnail-image full-width" src="../img/toolkit/thumbnails/{{ tool.thumbnail }}">
            <span class="thumbnail-text">{{ tool.title }}</span>
          </div>
        </a>
      </div>
    {% endfor %}
  </div>
</div>