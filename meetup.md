---
layout: default
title: Meetups – Upcoming and Past Meetings
redirect_from: ["/news/", "/meetups/", "/event/", "/events/"]
permalink: "/meetup/"
published: true
---

<div class="info">

<h2>Meetups</h2>
<div class="twitter-embedded">{{ site.twitter.highlight }}</div></div>
<p>We congregate monthly to showcase, learn, share, & network. We meet on the <strong>3rd Tuesday</strong> of every month in Long Beach. Please, join us.</p>


<h2>{{page.title}}</h2>
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

      <div class="entry">
        <time datetime='{{ post.date | date: "%F" }}T{{ post.meeting_start }}{{ post.date | date: "%z" }}'><h3>{{ post.date | date: "%Y %B" }} Meetup</h3></time>
        <h4><a href="{{ post.rsvp }}" target="_blank" ref="nofollow">Please R.S.V.P. for accurate headcount (food/drink)</a></h4>
        {% if post.promo_image %}
        <figure class="banner">
        {% include mdr/banner_image.html %}
        </figure>
        {% endif %}
        {{ post.excerpt }}
      </div>

      <em class="convince">Still need convincing it's going to be great?  <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read more</a></em>
    </article>
  {% endfor %}
</div>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
