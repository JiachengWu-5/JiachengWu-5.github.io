---
layout: default
class: home
css: ['pages/index.css']
comments: false
title: Homepage
menu: Homepage
---
<!-- Use the Homepage content only (from pages/Homepage.md) -->

<section class="banner">
    <div class="collection-head">
        <div class="container">
            <div class="collection-title">
              <h1 class="collection-header" id="sub-title"><span>{{ site.subtitle }}</span></h1>
                <div class="collection-info">
                    <span class="meta-info mobile-hidden">
                        <span class="octicon octicon-location"></span>
                        {{ site.location }}
                    </span>
                    <span class="meta-info">
                        <span class="octicon octicon-organization"></span>
                        <a href="{{ site.organization_url }}" target="_blank">{{ site.organization }}</a>
                    </span>
                     <span class="meta-info">
                        <span class="octicon octicon-mark-github"></span>
                        <a href="https://github.com/{{ site.github_username }}" target="_blank">{{ site.github_username }}</a>
                    </span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Homepage intro (copied from pages/Homepage.md) -->
<section class="container content">
    <div class="columns">
        <div class="column two-thirds">
            <div class="post-content">
                <br>
                <p>Welcome to the academic personal website of Jiacheng Wu. Here you will find updated information about Jiacheng Wu’s academic profile, experiences, and achievements.</p>
                <!--<p>If you want to know more about Jiacheng Wu’s life, feel free to check out <a href="https://jiachengwu-5.github.io/W">(￣∀￣)</a>!-->
                </p>
            </div>
        </div>
        <div class="column one-third">
            {% comment %} {% include sidebar-search.html %} {% endcomment %}
        </div>
    </div>
</section>
