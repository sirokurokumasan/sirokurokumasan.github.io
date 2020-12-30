---
layout: default
title: ブログの更新履歴
---
ブログの更新履歴が、最近更新した順番に見ることができます。
<a src="staff.html" class="btn">タグ別</a>に見ることもできるので、そちらも参考にしてください。

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}" class="btn">{{ post.title }}
      {{ post.excerpt }}</a>
    </li>
  {% endfor %}
</ul>
