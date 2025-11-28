---
layout: about
title: about
permalink: /
subtitle: 

profile:
  align: right
  image: seongwoolim.jpg
  image_circular: false # crops the image to make it circular

#selected_papers: false # includes a list of papers marked as "selected={true}"
#scholar:
#  selected_papers_only: false # Set to true to only show selected papers
#  order: asc # Optional: 'asc' for oldest first, 'desc' for newest first

social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I’m a postdoctoral researcher in <a href='https://sail.kaist.ac.kr'>SAIL</a> at Korea Advanced Institute of Science and Technology (KAIST). I received my B.S. and Ph.D. degrees from Ulsan National Institute of Science and Technology (UNIST) under the supervision of Prof. Jaesik Choi. I am interested in explainable AI that clarifies how models make decisions, as well as in efficient inference in symbolic model.

Here are my main links:
- [CV](/assets/pdf/CV.pdf)
- [Mail](mailto:seongwoolim@kaist.ac.kr)
- [GitHub](https://github.com/SeongwooLimKR)

## Publications

{% bibliography --query @* %}
