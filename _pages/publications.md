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
		Mohamed Ilyes Lakhal, Richard Bowden<br/>
		<i>"Diversity-Aware Sign Language Production through a Pose Encoding Variational Autoencoder,"</i><br/>
		<b>FG 2024.</b><br/>
		[<a href='{{ site.url }}{{ site.baseurl }}/assets/bibs/lakhal_FG_24'>Bibtex</a>] &nbsp;
    [<a href='https://ieeexplore.ieee.org/document/10581951'>IEEE</a>] &nbsp;
		[<a href='https://arxiv.org/pdf/2405.10423'>Arxiv</a>] &nbsp;
		
	</td>
</tr>

<tr>
	<td>
		<center><img src='{{ site.url }}{{ site.baseurl }}/images/pubpic/bmvc22.jpg' width=300></center>
		
	</td>
	<td>
		Mohamed Ilyes Lakhal, Oswald Lanz, Andrea Cavallaro<br/>
		<i>"Implicit texture mapping for multi-view video synthesis,"</i><br/>
		<b>BMVC 2022.</b><br/>
		[<a href='{{ site.url }}{{ site.baseurl }}/assets/bibs/lakhal_BMVC_22'>Bibtex</a>] &nbsp;
		[<a href='https://arxiv.org/pdf/2410.14968'>Arxiv</a>] &nbsp;
    [<a href='https://bmvc2022.mpi-inf.mpg.de/290/'>Poster</a>] &nbsp;
		
	</td>
</tr>

<tr>
	<td>
		<center><img src='{{ site.url }}{{ site.baseurl }}/images/pubpic/iccv19.jpg' width=300></center>
		
	</td>
	<td>
		Mohamed Ilyes Lakhal, Oswald Lanz, Andrea Cavallaro<br/>
		<i>"View-LSTM: novel-view video synthesis through view decomposition,"</i><br/>
		<b>ICCV 2019.</b><br/>
		[<a href='{{ site.url }}{{ site.baseurl }}/assets/bibs/lakhal_ICCV_19'>Bibtex</a>] &nbsp;
		[<a href='https://openaccess.thecvf.com/content_ICCV_2019/papers/Lakhal_View-LSTM_Novel-View_Video_Synthesis_Through_View_Decomposition_ICCV_2019_paper.pdf'>Paper</a>] &nbsp;
		
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
