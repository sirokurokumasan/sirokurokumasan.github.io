---
layout: default
title: ブログの更新履歴
---
最近更新した順番に並んでいます。
<a href="staff.html" class="btn">タグ別</a>に見ることもできるので、そちらも参考にしてください。

<ul style="list-style: none;">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}" class="block">
        {{ post.title }}  
        {{ page.date | date_to_string }}
        {{ post.excerpt }}
      </a><br><br>
    </li>
  {% endfor %}
</ul>
