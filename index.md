---
layout: default
title: ホーム
---

# プロフィール

こんにちは、stonewell25です。これは自分の活動記録・研究・論文のまとめページです。

## 最近の記録

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
