---
title: "Team"
layout: gridlay
excerpt: "DMMG Lab: Team Members"
sitemap: true
permalink: /team/
---

# Our Team

## Group Leader
<img src="{{ site.baseurl }}/images/karthik.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <a href= "{{ site.baseurl }}/karthik"><strong> Karthikeyan S </strong><br> </a>
  Associate Professor <br>
  Materials Engineering, IISc
</div>
<div style="clear: both;"></div>

## Group Members
<img src="{{ site.baseurl }}/images/sazid.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <a href="{{ site.baseurl }}/sazid"><strong>Sazid Khan</strong></a> <br>
  PhD Student <br>
</div>
<div style="clear: both;"></div>

<img src="{{ site.baseurl }}/images/mohan.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <a href= "{{ site.baseurl }}/mohan"><strong> Mohan Kumar N</strong></a><br>
  PhD Student <br>
</div>
<div style="clear: both;"></div>

<img src="{{ site.baseurl }}/images/dapulou.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <a href= "{{ site.baseurl }}/dapulou"><strong> Dapulou Joseph</strong></a><br>
  PhD Student <br>
</div>
<div style="clear: both;"></div>

<img src="{{ site.baseurl }}/images/shiba.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <a href= "{{ site.baseurl }}/shiba"><strong> Shiba Sankar Dash</strong></a><br>
  M.Tech (Res) Student <br>
</div>
<div style="clear: both;"></div>

<img src="{{ site.baseurl }}/images/anup.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <b>Anup Mandal</b><br>
  Research Associate <br>
</div>
<div style="clear: both;"></div>

<img src="{{ site.baseurl }}/images/jyothsna.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <b>Kote Jyothsna</b><br>
  Research Associate <br>
</div>
<div style="clear: both;"></div>

<img src="{{ site.baseurl }}/images/saem.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <b>Saem Ahmed</b><br>
  Research Assistant <br>
</div>
<div style="clear: both;"></div>

<img src="{{ site.baseurl }}/images/shalini.jpg" alt="" width="200" style="float: left; margin: 10px 20px 10px 0;">
<div style="margin-top: 50px;">
  <b>Shalini Rajagopal</b><br>
  Secretary <br>
</div>
<div style="clear: both;"></div>


## Alumni
- **Subham Mridha**, PhD (2023)
- **Shailendra Verma**, PhD (2023)

<!--# Group Members

 **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


Jump to [staff](#staff), [master and bachelor students](#master-and-bachelor-students), [alumni](#alumni), [administrative support](#administrative-support), [lab visitors](#lab-visitors)

## Staff
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> 
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Alumni

<!--## Master and Bachelor Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<!--## Former visitors, BSc/ MSc students
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div>


<!--## Administrative Support
<a href=""></a> is helping us (and other groups) with administration.-->
