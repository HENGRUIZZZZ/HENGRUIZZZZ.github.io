---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D in [您的专业]**, University College London, [开始年份] - Present
  * Supervisor: [导师姓名]
  * Research Focus: [研究方向]
* **[硕士学位] in [专业]**, [大学名称], [毕业年份]
* **[学士学位] in [专业]**, [大学名称], [毕业年份]

Research Experience
======
* **PhD Research**, University College London, [开始年份] - Present
  * [研究项目描述]
  * [主要成果或贡献]
  * Supervisor: [导师姓名]

* **[其他研究经历]**, [机构名称], [时间]
  * [工作内容描述]
  * [主要成果]
  * Supervisor: [导师姓名]

Skills
======
* **Programming Languages**: Python, R, MATLAB, [其他语言]
* **Research Methods**: 
  * [方法1]
  * [方法2]
  * [方法3]
* **Software & Tools**: [相关软件和工具]
* **Languages**: English (Fluent), Chinese (Native), [其他语言]

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards and Honors
======
* [奖项名称], [颁发机构], [年份]
* [奖学金名称], [年份]

Service and Leadership
======
* [服务经历，如审稿、组织会议等]
* [领导经历]

Professional Memberships
======
* [专业组织成员资格]
