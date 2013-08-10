---
layout: page
title: Welcome
posts: 5
---

<img src="/files/2011/09/profile_thumbnail.jpg" alt="yuyutianling" style="float:left; padding:10px" />
欢迎来到玉宇天灵的主页
<!--
Welcome to 玉宇天灵's Site! You may be interested in <a href="/archive.html" title="yuyutianling's Blog">my blog</a> 
for which I write technology related articles. Or you can read more <a href="/about.html" title="About 玉宇天灵">about who I am</a>. 
If there is anything you wish to say or to give me feedback, you can always contact me (see below).
-->

<aside id="recent-posts">
<h2>Recent Blog Posts:</h2>

<!-- Start of Display Recent Posts -->
<table class="posts">
<!-- Get 7 most recent entries by date (asc) -->
 {% for post in site.posts limit:7 offset:0 %}
 <tr>
               <th>{{ post.date | date_to_string }}</th>
      <td> <a href='{{ post.url }}'>{{ post.title }}</a></td>         
 </tr>
      {% endfor %} 
             </table>
</aside>
<!-- End of Display Recent Posts -->
<br />
