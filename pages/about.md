---
layout: page
title: About
description: Beautiful Things on Beautiful Technology
keywords: Matt Su, 苏琦
comments: true
menu: 关于
permalink: /about/
---

Hi there, 我是马特苏。

仰慕「优雅编码的艺术」。

## 坚信

* 熟能生巧
* 努力改变人生

## 联系

* GitHub：[@mzlogin](https://github.com/mzlogin)
* LinkedIn：[@mazhuang](https://www.linkedin.com/in/mazhuang)
* 博客：[{{ site.title }}]({{ site.url }})
* 知乎: [@mzlogin](http://www.zhihu.com/people/mzlogin)
* 豆瓣: [@壮哥不胖](http://www.douban.com/people/freedim)

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Windows Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
