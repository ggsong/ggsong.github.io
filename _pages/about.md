---
layout: single
permalink: /
title: ""
author_profile: true
classes: wide
redirect_from:
  - /about/
  - /about.html
---


## Introduction {#introduction}
I am a general practitioner and functional medicine physician with interests in digital health and patient-centered chronic disease management. My current work spans primary care pathways, nutrition and metabolism, and translational projects such as HPV screening and prevention. I enjoy building pragmatic, data-driven solutions that improve accessibility and care quality.

## Education {#education}
20XX–20XX — Degree / Major, University / School (Advisor: Name)<br>
20XX–20XX — Residency / Training, Hospital / Program<br>
20XX–20XX — Continuing education / Exchange (reverse chronological order)

## Awards {#awards}
20XX — Award name · Organization (one-line note on contribution if relevant)<br>
20XX — Award name · Organization<br>
20XX — Award name · Organization

## Certificate {#certificate}
20XX — License / Certificate name (Issuing body / Registration No., optional)<br>
20XX — License / Certificate name (Issuing body / Registration No., optional)

## Publication {#publication}
Representative publications will be listed here (to be updated).

<!-- If you want auto-rendered entries later, uncomment and ensure _publications/ has items:

{% assign pubs = site.publications | sort: "date" | reverse %}
{% if pubs.size > 0 %}
  {% for pub in pubs %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>No publications yet.</p>
{% endif %}

-->

<style>
  h2, h3 { scroll-margin-top: 90px; }  /* 锚点下移，避免被固定导航挡住 */
</style>		

<style>
/* 只改作者侧栏头像为矩形 */
.author__avatar img { border-radius: 0 !important; }
/* 如需控制侧栏头像尺寸，可加一条，例如固定 160px 宽 */
.author__avatar img { width: 160px; height: auto; }
/* 侧栏本来就是“头像在上、信息在下”的上下排布，无需额外设置 */
</style>

<style>
  /* 全页字体：正文、导航、标题、侧栏统一 Times New Roman */
  html, body, .site-title, .site-nav, .page__title,
  .page__content, .author__content, .author__urls-wrapper,
  h1, h2, h3, h4, h5, h6 {
    font-family: "Times New Roman", Times, serif !important;
    letter-spacing: normal;
  }

  /* 去掉小标题自带的底部边线（Minimal Mistakes 默认给 h2/h3 加线） */
  .page__content h2, .page__content h3 {
    border-bottom: 0 !important;
  }

  /* 你的锚点偏移保留（避免被固定导航遮住） */
  h2, h3 { scroll-margin-top: 90px; }
</style>
