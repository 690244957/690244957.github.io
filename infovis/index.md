---
layout: archive
title: "信息可视化作品集"
date: 
modified:
excerpt: ""
tags: []
image: 
---
<div><a href="https://690244957.github.io/infovis/%E4%BF%A1%E6%81%AF%E5%8F%AF%E8%A7%86%E5%8C%96%E6%9C%9F%E6%9C%AB%E4%B8%93%E6%A1%88/"><img src="https://690244957.github.io/images/data_visualization.jpg" alt="数据图"></a></div>
<br/>信息可视化作品
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->

