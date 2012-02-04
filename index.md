---
layout: page
title: Welcome!

---
{% include JB/setup %}
<div class="row">
<div class="span9">
<ul class="posts">
  <h4>Latest Posts</h4><br />
  {% for post in site.posts limit:10 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</div>
<div class="span5">
    <center>
        <img src="{{ BASE_PATH }}/images/aravindj.jpg" id="photo" />
        <br /><br />
        <a href="http://www.facebook.com/people/Aravind-Jayakumar/100000239415661">
            <img src="{{ BASE_PATH }}/images/facebook-icon.png" height="32px" width="32px" />
        </a>
        
        <a href="https://twitter.com/#!/aravindj">
            <img src="{{ BASE_PATH }}/images/twitter-icon.png" height="32px" width="32px" />
        </a>
        
        <a href="https://plus.google.com/108870936772923523588/about">
            <img src="{{ BASE_PATH }}/images/google-icon.png" height="32px" width="32px" />
        </a>

        <a href="http://www.linkedin.com/pub/aravind-j/17/56b/7b">        
            <img src="{{ BASE_PATH }}/images/linkedin-icon.png" height="32px" width="32px" />
        </a>
        
        <a href="mailto:aravindkumar.leo@gmail.com">
            <img src="{{ BASE_PATH }}/images/mail-icon.png" height="32px" width="32px" />
        </a>
        
        <a href="{{BASE_PATH}}/atom.xml">
            <img src="{{ BASE_PATH }}/images/feed-icon.png" height="32px" width="32px" />
        </a>
    </center>
</div>
</div>
