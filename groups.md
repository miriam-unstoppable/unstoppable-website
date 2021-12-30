---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: homepage_layout
---
# Creative Groups

There are a handful of different ways to work with us, including creative groups, [therapy and coaching](coaching-and-therapy.html). Our group offerings change based on interest and capacity. Here are some examples of group offerings at Unstoppable. If you'd like to inquire about current group offerings, or if you have an idea for a new group, [please reach out here](contact.html)!

{% for group in site.groups %}

<div class ="group-block">
	<!--- <h3><a href="{{group.url}}"> {{group.title}}</a></h3> --->
	<h2> {{group.title}}</h2>
	<img class="group-image" src= "{{group.image}}" alt = "{{group.image-describe}}"/>
	<div> {{group.content}}</div>
	
</div>


{% endfor %}

