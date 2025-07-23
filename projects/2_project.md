
layout: pagetitle: project 2description: a project with a background image and giscus commentsimg: assets/img/3.jpgimportance: 2category: workgiscus_comments: true
Every project has a beautiful feature showcase page.It's easy to include images in a flexible 3-column grid format.Make your photos 1/3, 2/3, or full width.
To give your project a background in the portfolio page, just add the img tag to the front matter like so:
---
layout: page
title: project
description: a project with a background image
img: /assets/img/12.jpg
---

{% raw %}
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="embed-responsive embed-responsive-4by5 rounded z-depth-1">
            <iframe class="embed-responsive-item" loading="lazy" src="https://www.canva.com/design/DAFplkP0V1M/3f_Zg0eKWFjwTVgDY6RShw/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen"></iframe>
        </div>
    </div>
</div>

{% endraw %}
