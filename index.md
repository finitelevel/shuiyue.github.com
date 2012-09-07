---
layout: page
title: 水月痴人的博客
tagline: Supporting tagline
---
{% include JB/setup %}

    
## 最新文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 《诫子书》
夫君子之行，静以修身，俭以养德。非淡泊无以明志，非宁静无以致远。夫学须静也，才须学也。非学无以广才，非志无以成学。淫慢则不能励精，险躁则不能冶性。
年与时驰，意与日去，遂成枯落，多不接世，悲守穷庐，将复何及！   ——诸葛亮

