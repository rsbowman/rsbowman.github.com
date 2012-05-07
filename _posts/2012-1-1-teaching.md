---
layout: default
title: Sean Bowman - Teaching Experience
---

<h2>Teaching Experience</h2>

I have taught math classes ranging from college algebra to
differential equations; a full list is given below.  During the period
2005--2011, I taught calculus for the Longhorn Scholars program for
three semesters.  These classes include first generation and
historically underrepresented students who sometimes need extra help
adjusting to college life.  These classes are challenging, but also
rewarding, to teach.

Rewarding in a different way are classes for honors students.  I
taught one semester of honors differential equations, and I was
invited to teach calculus for emerging scholars for two semesters.
This class, in which students can enroll by invitation only, is a
challenging adjunct to the traditional calculus sequence.

My teaching philosophy involves lots of student contact, frequent low
risk assessment opportunities, and feedback between student and
teacher.  You can
[read my teaching statement here](/documents/teaching-statement.pdf).

Here is a more or less complete list of classes I have taught:
- college algebra
- discrete math
- precalculus
- calculus I, II, and III,
- differential equations
- calculus for emerging scholars (a challenging adjunct to the traditional calculus sequence) 

In addition to undergraduate teaching, I have also had many
opportunities to speak about mathematics in general and my work in
particular.  Here are a few:

- Austin Math Circle, Fall 2010 (Grade school students)
- University of Arkansas Topology Seminar, Spring 2011
- University of Texas Topology Seminar, Fall 2011
- AMS/MAA Joint Meetings, Winter 2012
- Caltech Topology Seminar, Winter 2012

Here are some other teaching related projects I've been involved in:

{% for post in site.categories.teaching %}
<h2>{{ post.title }}</h2>
<p>{% if post.image %}<img src="{{ post.image }}" class="floatleft" />{% endif %}
  {{ post.content | markdownify }}</p>
<div style="clear:both;"></div>
{% endfor %}
