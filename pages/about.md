---
layout: page
title: About
description: 栖迟於一丘，则天下不易其乐
keywords: jiaxiang8756
comments: true
menu: 关于
permalink: /about/
---

## Introduction

Read-Think-Write-Code

## Find Me

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
<li>
邮箱：<a href="mailto:jiaxiangjia@vip.qq.com" alt="jiaxiangjia@vip.qq.com">nanvon@foxmail.com</a>
</li>
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/qrcode.jpg" alt="南枫的寻宝之旅" />
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
