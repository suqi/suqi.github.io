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

## 此博客的构建
- 使用jekyll静态博客引擎
- 使用github-pages自build
- 基于[马壮的博客](https://github.com/mzlogin/mzlogin.github.io)进行修改
    - 修改方向主要是让站点更扁平化, 专注于内容, 而不是绚烂的eyecandy

## 对此博客的建议
- 请在[本博客的github仓库](github.com/suqi/suqi.github.io)提交issue
- 请猛烈地批评建议, 或者是说说你的任何想法

## 联系我

* GitHub：[@suqi](https://github.com/suqi)
* LinkedIn：[@mattsu](https://www.linkedin.com/in/mattsu)
* 博客：[{{ site.title }}]({{ site.url }})
* V2EX: [@qisuker](https://www.v2ex.com/member/qisuker)

## 我喜欢的几个博客

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
