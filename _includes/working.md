## Selected Working Papers

<ol style="margin:0 0 5px;">
  <!-- Diplomacy by committee -->
  <li>Diplomacy by committee: Assessing resolve and costly signals in group settings.
  <br><font color="#a79d96">Carly Wayne, Mitsuru Mukaigawara, Joshua Kertzer, and Marcus Holmes.</font>
  <br>Revise and Resubmit.</li>
  <details><summary>Abstract</summary><small>
  Assessing resolve and interpreting costly signals are crucial tasks for leaders engaging in international diplomacy. However, leaders rarely make these decisions in isolation, relying on advisers to help assess adversary intentions. How do group dynamics change the way leaders make these crucial judgments? We field a large-scale group experiment to examine how assessments of resolve vary across group settings. We find groups make significantly higher initial assessments of adversary resolve than individuals do, but also update their beliefs less after receiving new information. In the small group contexts that characterize much foreign policy decision-making then, first impressions may play a stronger role in shaping beliefs than any signals—costly or otherwise—that come afterwards. This has important implications for our understanding of international diplomacy, providing further evidence that the role of "costly signalling" in diplomatic relations is less straightforward than often assumed.
  </small></details>
  <!-- geocausal -->
  <li>geocausal: R package for spatio-temporal causal inference.
  <br><font color="#a79d96">Mitsuru Mukaigawara, Georgia Papadogeorgou, Jason Lyall, and Kosuke Imai.</font></li>
  <details><summary>Abstract</summary><small>
  Scholars in various fields enjoy the rapid expansion of granular data with spatio-temporal dimensions. Despite the proliferation of data with spatio-temporal dimensions, however, statistical methods to utilize them for causal inference remain under-developed. We introduce an R package, geocausal, a practical tool that enables scholars and practitioners to implement a causal inference method for spato-temporal data. The geocausal package allows users to implement six necessary steps for spatio-temporal causal inference: (1) converting spatio-temporal data into an object called a hyperframe; (2) smoothing point pattern data; (3) generating covariates; (4) obtaining observed densities of treatment events; (5) obtaining counterfactual densities; and (6) estimating user-defined causal effects of counterfactual scenarios with spatio-temporal dimensions. We illustrate the usage of the geocausal package by analyzing effects of airstrikes on insurgent activities in Iraq.
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
