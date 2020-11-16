---
layout: page
title: About
description: 关于我的一些信息
keywords: ziyu
comments: true
menu: 关于
permalink: /about/
---

勤能补拙，熟能生巧。

## 联系

<ul>
<li>
Github: https://github.com/ziyu123
</li>
</ul>

## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
