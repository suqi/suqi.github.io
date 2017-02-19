---
layout: page
title: About
description: Beautiful Things on Beautiful Tech.
keywords: Matt Su, 苏琦
comments: true
menu: 关于
permalink: /about/
---


Hi there, I'm Matt Su.

This blog is about `Startup, Zen & Python`

<div class="collection-info">
    <span class="meta-info mobile-hidden">
        <span class="octicon octicon-location"></span>
        {{ site.location }}
    </span>
    <span class="meta-info">
        <span class="octicon octicon-organization"></span>
        {{ site.organization }}
    </span>
     <span class="meta-info">
        <span class="octicon octicon-mark-github"></span>
        <a href="https://github.com/{{ site.github_username }}" target="_blank">{{ site.github_username }}</a>
    </span>
</div>

---

> 站在科技与人文的十字路口，眺望自然主义与实用哲学的交汇时空

## 我的作品
- 译作[<<Python进阶>>](http://interpy.eastlakeside.com/)
	- 这是一本和小伙伴们一起用心翻译的良心之作

## 联系

* GitHub：[@suqi](https://github.com/suqi)
* LinkedIn：[@mattsu](https://www.linkedin.com/in/mattsu)
* 博客：[{{ site.title }}]({{ site.url }})
* V2EX: [@qisuker](https://www.v2ex.com/member/qisuker)

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
