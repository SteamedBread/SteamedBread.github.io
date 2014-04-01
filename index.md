---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/"><span>Blog</span></a></li>
            <li style="text-align:center"><a href="/opinion"><span>Opinion</span></a></li>
            <li style="text-align:right"><a href="/project"><span>Project</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.blog %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
        <div class="aside_box">
            <a href="http://steamedbread.github.io/">
                <img src="/images/Avatar.jpg" width="230">                
            </a>
            <h2 style="margin-top:20px;"><span style="float:left">王允兵</span><a href="http://weibo.com/yunbing" target="_blank" style="margin:0 0 0 5px;"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"></a></h2>
            <p>虽然以后未知，但努力就会有收获！</p>
        </div>
    </div>
</div>
