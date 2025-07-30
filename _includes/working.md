<h1 id="working"></h1>

<h2 style="margin: 100px 0px 60px;">| Working Papers</h2>

<ol style="margin:0 0 5px;">
  <!-- sibs -->
  <li><a href = "https://garyking.org/sibs">Survey estimates of wartime mortality</a>.
  <br><font color="#a79d96">Gary King and Mitsuru Mukaigawara.</font></li>
  <details><summary>Abstract</summary><small>
  Many scholarly literatures require mortality rates from conflict zones, but accurate information is usually among the earliest casualties of war. While political scientists typically obtain mortality data from others, much progress has been made in demography, epidemiology, and public health via original surveys about the survival of siblings, friends, or others known to respondents. Unfortunately, the formal properties of estimators based on these surveys have not been established, the intuitions offered for them (and consequent data analysis strategies) are conflicting, and the statistical consequences of the political incentives of respondents in conflict zones remain unexamined. In this paper, we demonstrate the advantages of joining ongoing efforts in these other fields with insights from political science, including especially political methodology, international relations, and comparative politics. We offer the first formal proofs of the statistical properties of all existing estimators, along with simulation and empirical illustrations, to craft simple intuitions to guide best practices. We also build practical data analytic approaches, based on modern robust statistical methods, for when some respondents are suspected of intentionally biasing answers for political, military, or other strategic purposes.
  </small></details>
  <!-- geocausal -->
  <li><a href = "https://arxiv.org/abs/2504.03464">Spatiotemporal causal inference with arbitrary spillover and carryover effects</a>.
  <br><font color="#a79d96">Mitsuru Mukaigawara, Kosuke Imai, Jason Lyall, and Georgia Papadogeorgou.</font></li>
  <details><summary>Abstract</summary><small>
  Micro-level data with granular spatial and temporal information are becoming increasingly available to social scientists. Most researchers aggregate such data into a convenient panel data format and apply standard causal inference methods. This approach, however, has two limitations. First, data aggregation results in the loss of detailed geo-location and temporal information, leading to potential biases. Second, most panel data methods either ignore spatial spillover and temporal carryover effects or impose restrictive assumptions on their structure. We introduce a general methodological framework for spatiotemporal causal inference with arbitrary spillover and carryover effects. Under this general framework, we demonstrate how to define and estimate causal quantities of interest, explore heterogeneous treatment effects, investigate causal mechanisms, and visualize the results to facilitate their interpretation. We illustrate the proposed methodology through an analysis of airstrikes and insurgent attacks in Iraq. The open-source software package geocausal implements all of our methods.
  </small></details>
  <!-- software -->
  <li><a href = "https://doi.org/10.31219/osf.io/5kc6f">geocausal: An R package for spatio-temporal causal inference</a>.
  <br><font color="#a79d96">Mitsuru Mukaigawara, Lingxiao Zhou, Georgia Papadogeorgou, Jason Lyall, and Kosuke Imai.</font></li>
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
