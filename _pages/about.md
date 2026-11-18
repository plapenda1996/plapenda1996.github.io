---
layout: about
title: about
permalink: /
subtitle: "Ph.D. Student in Bioengineering · <a href='https://www.iopticslab.seas.ucla.edu/'>Intelligent Optics Laboratory</a> · UCLA"

profile:
  align: right
  image: # add a photo as assets/img/prof_pic.jpg and set this to prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: # affiliation lines shown under the photo, e.g. <p>Department of Bioengineering, UCLA</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

I am a Ph.D. student in Bioengineering at UCLA, advised by [Prof. Liang Gao](https://www.iopticslab.seas.ucla.edu/) in the Intelligent Optics Laboratory. I build optical imaging systems that capture fast biological dynamics in three dimensions, from optical design and instrumentation to computational reconstruction.

My current work centers on **squeezed light-field microscopy (SLIM)**: kilohertz volumetric imaging of neural activity, and its extension to the second near-infrared window (**NIR-II**) for imaging deep inside living tissue. Before UCLA, I developed non-bleaching super-resolution techniques with gold nanorods at the University of Michigan (M.S.), and I received my B.S. in Information Display from Kyung Hee University (summa cum laude).

<h2><a href="{{ '/projects/' | relative_url }}" style="color: inherit">research</a></h2>

{% assign research_projects = site.projects | where: "category", "research" | sort: "importance" %}

<div class="projects">
<div class="row row-cols-1 row-cols-md-3">
{% for project in research_projects %}
{% include projects.liquid %}
{% endfor %}
</div>
</div>
