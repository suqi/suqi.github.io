---
layout: page
title: About
description: Beautiful Things on Beautiful Tech.
keywords: Matt Su, 苏琦
comments: true
menu: 关于
permalink: /about/
---

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
<br>

Hi there, I'm **Matt Su**. 
我是EastLakeSide东滨社的发起人（关于EastLakeSide东滨社 - 自由，创作，读书，健身的国际创意合作社）
这里是我的博客，我主要关注 `Startup, Zen & Python`，以及 `software engineering, life-long learning & writing`。
同时EastLakeSide合作社的一些新进展也会在这里公布。


## Philosophy
- 站在科技与人文的十字路口，眺望自然主义与实用哲学的交汇时空, 
- Sync up new tech ideas across world, for fun and love.



## 我的作品
- 译作[<<Python进阶>>](http://interpy.eastlakeside.com/)
	- 这是一本和小伙伴们一起用心翻译的良心之作

## 此博客的构建
- 使用jekyll静态博客引擎
- 使用github-pages自build
- 基于[马壮的博客](https://github.com/mzlogin/mzlogin.github.io)进行修改
    - 修改方向主要是让站点更扁平化, 专注于内容, 而不是绚烂的eyecandy

## 对此博客的建议
- 请在[本博客的github仓库](https://github.com/suqi/suqi.github.io/issues)提交issue
- 请猛烈地批评建议, 或者是说说你的任何想法

## 联系我
* LinkedIn：[@mattsu](https://www.linkedin.com/in/mattsu)，这里可以看到我的履历
* GitHub：[@suqi](https://github.com/suqi)，这里有我的所有项目
* 博客：[{{ site.title }}]({{ site.url }})，这有里有我所有公开的分享
* V2EX: [@qisuker](https://www.v2ex.com/member/qisuker)，这里有我在V站的问答

## 我喜欢的几个博客
- [湾区日报](https://wanqu.co/)
    - 感觉这个硅谷的工程师有股韧劲, 独立把这个小side-project运营起来了
    - 难的是, 能一直当成side-project来做, 从而不忘初心
    - maker的榜样
- [overtrue](https://github.com/overtrue/overtrue.github.io)和[马壮](http://mazhuang.org)
    - 他俩的博客样式我比较喜欢, 于是借鉴过来了


## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
