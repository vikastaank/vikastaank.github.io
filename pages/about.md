---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me** :point_down:

Hey, I am **{{ site.author.name }}** :wave:,<br>
I am Java devloper by profession and interest both! Love to work with Java & it's frameworks, love to explore technologies & things to make things easier and efficient..:computer: <br>
Love to sleep more! :zzz: <br>
Always ready to party :beers: <br>
I was never able to complete any book.. :orange_book: <br>

<!--
 ## **Skills** :octocat:
- Java
- Spring/SpringBoot
- Hibernate
- MySQL/Oracle
- Go
- Git/BitBucket, Jira
- Rest API development & Integration
- Microservices
- Linux
- Payment gateways integration in Java
-->

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
