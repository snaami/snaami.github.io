---
layout: page
title: About Me
permalink: /about/
weight: 3
---


Hi I am **{{ site.author.name }}**,<br>

I'm a developer based in Paris, France ( yes you get it right ) I wrote code for a living.
Generally speaking, I'm a C/C++ developer under the Linux operating system but on the other hand, I do other kinds of devs as a hobbyist especially in my free time using C# and Unity Engine to make exciting tiny mobile games ( my be they are not that great but they still wonderful to me).
I'm a simple man who is driven by his passion. I like debugging ( of course I lie who like debugging ?) 
If you like to know more about Sami continue to read my CV below or just use the download button to get a PDF version of it.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Professional Skills" source=site.data.professional-skills %}
</div>

<div class="row">
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
{% include about/skills.html title="" source=site.data.empty-skills %}  
</div>

**Download CV**
<p>
{% include elements/button.html link=site.url text="Télécharger version FR" style="primary" %}
{% include elements/button.html link=site.url text="Download EN version" style="primary" %}
</p>

<div class="row">
{% include about/timeline.html %}
</div>