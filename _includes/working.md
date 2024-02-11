<h1 id="working"></h1>

<h2 style="margin: 60px 0px 10px;">Working Papers</h2>

<ol style="margin:0 0 5px;">
  <!-- geocausal -->
  <li>geocausal: R package for spatio-temporal causal inference.
  <br><font color="#a79d96">Mitsuru Mukaigawara, Georgia Papadogeorgou, Jason Lyall, and Kosuke Imai.</font></li>
  <details><summary>Abstract</summary><small>
  Scholars from diverse fields now use highly disaggregated ("microlevel") data with fine-grained spatial (e.g., locations of villages and individuals) and temporal (days, hours, or even seconds) dimensions to test their theories. Despite the proliferation of these data, however, statistical methods for causal inference with spatio-temporal data remain underdeveloped. We introduce an R package, geocausal, that enables researchers to implement causal inference methods for highly disaggregated spatio-temporal data. The geocausal package helps users implement two necessary steps for spatio-temporal causal inference: (1) preparing the data and (2) estimating causal effects. The geocausal package allows users to effectively use fine-grained spatio-temporal data, test counterfactual scenarios that have spatial and temporal dimensions, and visualize each step efficiently. We illustrate the capabilities of the geocausal package by analyzing the US airstrikes and insurgent attacks in Iraq over various spatial and temporal windows. 
  </small></details>
</ol>

<!--

<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>
</div>

-->
