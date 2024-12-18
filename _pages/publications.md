---
title: "Visual Computing Lab - Publications"
layout: gridlay
excerpt: "Visual Computing Lab -- Publications."
sitemap: false
permalink: /publications/
---


<!-- # Publications -->

### Highlighted publications

<table cellspacing=10 style='font-family:"Arial", Courier, monospace; font-size:15px'>

<tr>
	<td>
		<center><img src='{{ site.url }}{{ site.baseurl }}/images/pubpic/fg24.jpg' width=300></center>
		
	</td>
	<td>
		Xun Tu, Karthik Desingh<br/>
		<i>"Diversity-Aware Sign Language Production through a Pose Encoding Variational Autoencoder,"</i><br/>
		<b>FG 2024.</b><br/>
		[<a href='{{ site.url }}{{ site.baseurl }}/assets/bibs/lakhal_FG_24'>Bibtex</a>] &nbsp;
    [<a href='https://ieeexplore.ieee.org/document/10581951'>IEEE</a>] &nbsp;
		[<a href='https://arxiv.org/pdf/2405.10423'>Arxiv</a>] &nbsp;
		
	</td>
</tr>

<tr>
	<td>
		<center><img src='{{ site.url }}{{ site.baseurl }}/images/pubpic/fg24.jpg' width=300></center>
		
	</td>
	<td>
		Ryan Diaz, Adam Imdieke, Vivek Veeriah, Karthik Desingh<br/>
		<i>"AugInsert: Learning Robust Visual-Force Policies via Data Augmentation for Object Assembly Tasks,"</i><br/>
		<b>under review.</b><br/>
		[<a href='{{ site.url }}{{ site.baseurl }}/assets/bibs/diaz2024AugInsertarXiv'>Bibtex</a>] &nbsp;
		[<a href='https://arxiv.org/pdf/2410.14968'>Arxiv</a>] &nbsp;
		[<a href='https://youtu.be/UTA7sefgs2o?feature=shared'>Video</a>] &nbsp;
		[<a href='https://rpm-lab-umn.github.io/auginsert/'>Project page</a>] &nbsp;
		
	</td>
</tr>

<tr>
	<td>
		<center><img src='{{ site.url }}{{ site.baseurl }}/images/pubpic/fg24.jpg' width=300></center>
		
	</td>
	<td>
		Carl Winge, Adam Imdieke, Bahaa Aldeeb, Dongyeop Kang, Karthik Desingh<br/>
		<i>"Talk Through It: End User Directed Manipulation Learning,"</i><br/>
		<b>RA-L 2024.</b><br/>
		[<a href='{{ site.url }}{{ site.baseurl }}/assets/bibs/winge2024RAL'>Bibtex</a>] &nbsp;
		[<a href='https://ieeexplore.ieee.org/document/10608414'>IEEE</a>] &nbsp;
		[<a href='https://arxiv.org/pdf/2402.12509.pdf'>Arxiv</a>] &nbsp;
		[<a href='https://www.youtube.com/watch?v=j_FHSDrw6dM'>Video</a>] &nbsp;
		[<a href='https://talk-through-it.github.io/'>Project page</a>] &nbsp;
		
	</td>
</tr>

<tr>
	<td>
		<center><img src='{{ site.url }}{{ site.baseurl }}/images/pubpic/fg24.jpg' width=300></center>
		
	</td>
	<td>
		Alireza Rezazadeh, Athreyi Badithela, Karthik Desingh, Changhyun Choi<br/>
		<i>"SlotGNN: Unsupervised Discovery of Multi-Object Representations and Visual Dynamics,"</i><br/>
		<b>ICRA 2024.</b><br/>
		[<a href='{{ site.url }}{{ site.baseurl }}/assets/bibs/rezazadeh2024ICRA'>Bibtex</a>] &nbsp;
		[<a href='https://ieeexplore.ieee.org/abstract/document/10611588'>IEEE</a>] &nbsp;
		[<a href='https://arxiv.org/pdf/2310.04617.pdf'>Arxiv</a>] &nbsp;
		[<a href='https://www.youtube.com/watch?v=0fZBY5bMh3Q'>Video</a>] &nbsp;
		[<a href='https://www.alireza.page/slot-gnn'>Project page</a>] &nbsp;
		
	</td>
</tr>


<tr>
	<td>
		<center><img src='{{ site.url }}{{ site.baseurl }}/images/pubpic/fg24.jpg' width=300></center>
		
	</td>
	<td>
		Chahyon Ku, Carl Winge, Ryan Diaz, Wentao Yuan, Karthik Desingh<br/>
		<i>"Evaluating Robustness of Visual Representations for Object Assembly Task Requiring Spatio-Geometrical Reasoning,"</i><br/>
		<b>ICRA 2024.</b><br/>
		[<a href='{{ site.url }}{{ site.baseurl }}/assets/bibs/ku2024ICRA'>Bibtex</a>] &nbsp;
		[<a href='https://ieeexplore.ieee.org/abstract/document/10610774'>IEEE</a>] &nbsp;
		[<a href='https://arxiv.org/pdf/2310.09943.pdf'>Arxiv</a>] &nbsp;
		[<a href='https://www.youtube.com/watch?v=3e5QKCdmb7Q'>Video</a>] &nbsp;
		[<a href='https://sites.google.com/view/geometric-peg-in-hole/home'>Project page</a>] &nbsp;
		
	</td>
</tr>
</table>

<!--## Group highlights

**At the end of this page, you can find the [full list of publications](#full-list-of-publications).**

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p> -->


## Full List of publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
