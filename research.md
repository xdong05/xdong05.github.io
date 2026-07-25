---
title: "Dong Lab - Research"
layout: textlay
excerpt: "Dong Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

Our work focuses on spatial self-organization and pattern formation in ecosystems, using mathematical models, primarily partial differential equations. Here are some themes we currently work on:


<h3 style="font-size: 1.6em; font-family: 'Georgia', serif; margin-top: 40px;">
  How do spatial patterns originate, assemble, interact with their environment, and change?
</h3>

<p style="font-size:1.25em; font-style:italic; color:#555; margin-top:0;">
Pattern formation • Nonlinear dynamics • Self-organization
</p>

{::nomarkdown}

<div style="display:flex; justify-content:center; gap:10px; margin:12px 0 2px 0;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/veg3.jpeg" style="height:200px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/ant3.jpeg" style="height:200px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/reef1.png" style="height:200px;">
</div>

<p style="text-align:center;
          font-family:Georgia, serif;
          font-size:0.85em;
          color:#666;
          line-height:1.3;
          margin:2px 0 14px 0;">
  From left to right:
  (A) regular vegetation patterns in drylands;
  (B) microbial communities forming cone structures in Antarctic lakes;
  (C) reticulated coral reef patterns.
</p>

{:/nomarkdown}

<p>
We develop mathematical models to understand how interactions among organisms, resources, and the physical environment generate self-organized spatial patterns. By comparing diverse ecosystems—including dryland vegetation, biological soil crusts, Antarctic microbial communities, coral reefs, coastal wetlands, and soil redox patterns—we seek general mathematical principles governing pattern formation in living systems.
</p>

<p style="margin-top:20px; margin-bottom:4px;">
<b>Current model systems:</b>
</p>

<ul style="margin:0 0 15px 22px; line-height:1.4;">
  <li>
  Dryland vegetation and biological soil crusts
  <span style="color:#777;">
    (<a href="https://www.nsf.gov/div/index.jsp?div=DEB">NSF-DEB</a>)
  </span>
</li>
  <li>
  Antarctic microbial communities
  <span style="color:#777;">
    (<a href="https://www.nsf.gov/div/index.jsp?div=OPP">NSF-OPP</a>)
  </span>
</li>
</ul>

<p style="margin-top:18px; margin-bottom:4px;">
<b>Methods:</b>
</p>

<ul style="margin:0 0 15px 22px; line-height:1.4;">
  <li>Reaction–diffusion models</li>
  <li>Partial differential equations</li>
  <li>Stability and bifurcation analysis</li>
  <li>Numerical simulations</li>
</ul>

<div style="margin-top: 60px;"></div>




<h3 style="font-size: 1.6em; font-family: 'Georgia', serif; margin-top: 40px;">
  Vegetation Spatial Patterns in Global Drylands
</h3>

<div style="display: flex; justify-content: center; gap: 10px; margin-bottom: 1px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/veg3.jpeg" style="height: 200px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/veg4.jpg" style="height: 200px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/dx_BSC6.jpg" style="height: 200px;">
</div>
<p style="text-align: center; font-family: Georgia, serif; font-size: 0.85em; color: #555; line-height: 1.3; margin-top: 1px; margin-bottom: 20px;">
  From left to right: (A) self-organized vegetation patterns in dryland ecosystems; (B) a typical reactive-transport model to study Turing pattern formation of dryland vegetation; (C) dryland ecosystems featuring both vascular plants and biological soil crusts. 
</p>

As environmental change pushes ecosystems toward their limits, there's a growing need to predict their responses to external pressures. Prior research shows that large-scale spatial patterns in ecosystems can change in *predictable* ways near tipping points—serving as early warning signs of collapse. Drylands, which are both globally widespread and sensitive, have been a model system for developing this theory.

The prevailing dryland models predict a shift in vegetation patterns with increasing aridity: from gaps in continuous vegetation, to labyrinth-like bands, to spotty patches, and eventually to a bare-soil state. However, such patterns only appear in a small fraction of drylands globally. A likely reason is that current models overlook a crucial ecological component—species interactions, particularly the role of <span style="font-weight: 600;">biological soil crusts (biocrusts)</span> in the case of drylands.

To better understand dryland spatial dynamics, we are developing new theories and models that explicitly include biocrust-plant species interactions. Supported by [NSF-DEB](https://www.nsf.gov/div/index.jsp?div=DEB), our team (co-PIs: [Yufang Jin](https://jin.ucdavis.edu), [Rachata Muneepeerakul](https://abe.ufl.edu/people/faculty/rachata-muneepeerakul/), [Caroline A. Havrilla](https://drylandecology.com/who-we-are), and [Yu Zhang](https://scholar.google.com/citations?user=4fQCR88AAAAJ&hl=en)) aims to build models that explain the broader diversity of vegetation patterns observed in real drylands. See our recent results from the [remote sensing analysis](https://link.springer.com/article/10.1007/s10021-023-00898-2) and [mathematical modeling](https://onlinelibrary.wiley.com/doi/abs/10.1002/eco.70028).
  
<div style="margin-top: 60px;"></div>

<h3 style="font-size: 1.6em; font-family: 'Georgia', serif; margin-top: 40px;">
  Spatial Self-organization of Benthic Microbial Communities in Antarctic Lakes
</h3>
<div style="display: flex; justify-content: center; gap: 10px; margin-bottom: 1px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/ant3.jpeg" style="height: 200px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/ant1.png" style="height: 200px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/ant2.jpg" style="height: 200px;">
</div>
<p style="text-align: center; font-family: Georgia, serif; font-size: 0.85em; color: #555; line-height: 1.3; margin-top: 1px; margin-bottom: 20px;">
  From left to right: (A) microbial communities forming cone structures on the lake floor in Antartic; (B) microbial communities forming pinnacle structure on the lake floor; and (C) cross-section of a pinnacle ([read more](https://pubmed.ncbi.nlm.nih.gov/27474373/)).
</p>


Beneath permanent ice and meters of liquid water in many Antarctic lakes reside structurally complex arrays of spatially self-organized microbial mats,  forming pinnacles, cones, or hexagonal structures (<span style="font-weight: 600;">[modern stromatolites](https://en.wikipedia.org/wiki/Stromatolite)</span>). These unique ecosystems are now being reshaped by global change. We are developing models to predict how environmental changes—particularly the reduction or loss of summer ice cover—might affect, or may have already affected, benthic microbial communities. By integrating the morphology and spatial patterning of these modern stromatolites with their biophysical and biochemical environments, we aim to refine our understanding of the controls on microbial community organization. This, in turn, will improve interpretations of *ancient stromatolites* in the geologic record and shed light on key questions about Earth’s evolutionary and environmental history.

Collaborating with [Dr. Dawn Sumner](https://dysumner.faculty.ucdavis.edu), we are applying pattern formation theory and computational fluid dynamics (CFD) to understand pinnacle-forming microbial mats in Lake Vanda, Antarctica (funded by [NSF-OPP](https://www.nsf.gov/div/index.jsp?div=OPP)) and their response to ice melting under warming. 
 
<div style="margin-top: 60px;"></div>


<h3 style="font-size: 1.6em; font-family: 'Georgia', serif; margin-top: 40px;">
  Geo-evolutionary Feedbacks to Couple Evolution of Landscapes and Plants
</h3>
<div style="display: flex; justify-content: center; gap: 10px; margin-bottom: 1px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/dx_fig3.png" style="height: 200px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/river1.jpg" style="height: 200px;">
</div>
<p style="text-align: center; font-family: Georgia, serif; font-size: 0.85em; color: #555; line-height: 1.3; margin-top: 1px; margin-bottom: 20px;">
  From left to right: (A) Geo-evolutionary feedbacks using the example of coastal salt marsh landscapes (from [Dong et al. 2024](https://www.cell.com/trends/ecology-evolution/fulltext/S0169-5347(24)00119-8)); (B) a riverine landscape shaped by vegetation–sediment-flow interactions.
</p>


Biological processes affect almost all landscapes on Earth. Their effects are perhaps most prominent in biogeomorphic landscapes such as coastal wetlands, sand dunes, and peatlands. The field of biogeomorphology has been built on observations of the strong influence of organisms on landscapes; however, biogeomorphic models seldom consider genetic or phenotypic changes of organisms, because evolution is perceived to take place slowly and across great distances. Thus, geomorphologists have often assumed that they could safely ignore evolution, especially at fine temporal and spatial scales. However, evidence from evolutionary biology has accumulated that populations can evolve meaningful changes on the same timescales at which they modify the landscape. 

Looking at this knowledge gap from the other side, evolutionary biology often does not consider the effect of landscape dynamics on biological evolution. Although the effects of landscape changes on speciation in geological time are relatively well studied, synergistic interactions between evolution and landscape change in *contemporary time* have not been embodied in evolutionary biology. Such persistent disciplinary barriers have impeded the development of a much-needed integrative theory. 

The key realization to our argument is that evolutionary dynamics and landscape change can occur at *congruent timescales*, thus forming an interplay between the evolution of populations and the dynamics of landscapes on which those populations reside. We are developing models and theory that integrate <span style="font-weight: 600;">eco-evolutionary and landscape geomorphic dynamics</span>, considering feedbacks between landscape changes and evolution of plants in contemporary times. See [this modeling paper](https://www.journals.uchicago.edu/doi/full/10.1086/719425) and [conceptual paper](https://www.cell.com/trends/ecology-evolution/abstract/S0169-5347(24)00119-8) for our most recent results.


<div style="margin-top: 60px;"></div>
<h3 style="font-size: 1.6em; font-family: 'Georgia', serif; margin-top: 40px;">
  Global Plant Range Shifts under Global Climate Change
</h3>

<div style="text-align: center; margin-bottom: 1px;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/Picture1.png" style="width: 70%; max-width: 800px;">
  <p style="text-align: center; font-family: Georgia, serif; font-size: 0.85em; color: #555; line-height: 1.3; margin-top: 1px; margin-bottom: 20px;">
    Figure above: Causes and global distributions of plant extinction by 2081-2100. (a) Differences in projected plant extinction rates with realistic range shift velocity and unlimited dispersal are negligible. (b) Species at high risk of extinction are dominated by range-contracting plants and colonizing plants not subject to dispersal limitations. (c) Range shift velocity scenarios explained < 1% of variance in projected extinction rates, whereas choice of species distribution models (SDMs) explained most (60%) of the variance. (d) and (e) compares global distribution of plants at high extinction risk under medium (SSP245) and high (SSP585) emissions scenarios (paper under review).
  </p>
</div>

In collaboration with [Dr. Francis Moore](https://franmoore.faculty.ucdavis.edu) and [Dr. Marc Conte](https://marcnconte.ace.fordham.edu), we are evaluating how climate change reshapes global plant distributions and biodiversity (funded by [NSF-DEB](https://www.nsf.gov/div/index.jsp?div=DEB)).

Using global species distribution models that account for dispersal limitations, local environmental conditions, topographic complexity, and land cover, we investigate the role of plant range shifts in mitigating extinction rates and modifying biodiversity distributions globally. Additionally, we identify regions likely to lose or gain biodiversity, experience novel species assemblages, and host key migration corridors. See our most recent results in [Science (2026)](https://www.science.org/doi/abs/10.1126/science.aea1676) 

We also integrate these ecological outcomes into <span style="font-weight: 600;">Integrated Assessment Models (IAMs)</span> to better quantify the <span style="font-weight: 600;">social cost of carbon</span>. See our results in [JUE (2023)](https://www.journals.uchicago.edu/doi/10.1086/716662) and [Nature (2023)](https://www.nature.com/articles/s41586-023-06769-z).



<div style="margin-top: 60px;"></div>
<h3 style="font-size: 1.6em; font-family: 'Georgia', serif; margin-top: 40px;">
  ... and more
</h3>
