
layout: pagetitle: project 2description: a project with a background image and giscus commentsimg: assets/img/3.jpgimportance: 2category: workgiscus_comments: true
Every project has a beautiful feature showcase page.It's easy to include images in a flexible 3-column grid format.Make your photos 1/3, 2/3, or full width.
To give your project a background in the portfolio page, just add the img tag to the front matter like so:
---
layout: page
title: project
description: a project with a background image
img: /assets/img/12.jpg
---


    
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    
    
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    
    
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    


    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.


    
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    


    This image can also have a caption. It's like magic.


You can also put regular text between your rows of images.Say you wanted to write a little bit about your project before you posted the rest of the images.You describe how you toiled, sweated, bled for your project, and then... you reveal its glory in the next row of images.

    
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    
    
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    


    You can also have artistically styled 2/3 + 1/3 images, like these.


Here's an embedded Canva presentation to showcase additional project details:

    
        
            
        
    


    An interactive Canva presentation showcasing project highlights.


The code is simple.Just wrap your images with <div class="col-sm"> and place them inside <div class="row"> (read more about the Bootstrap Grid system).To make images responsive, add img-fluid class to each; for rounded corners and shadows use rounded and z-depth-1 classes.For embedded iframes, use embed-responsive and embed-responsive-item classes to maintain responsiveness, with rounded and z-depth-1 for consistent styling. Here's the code for the Canva embed above:
{% raw %}
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="embed-responsive embed-responsive-4by5 rounded z-depth-1">
            <iframe class="embed-responsive-item" loading="lazy" src="https://www.canva.com/design/DAFplkP0V1M/3f_Zg0eKWFjwTVgDY6RShw/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen"></iframe>
        </div>
    </div>
</div>

{% endraw %}
