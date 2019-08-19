---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
My research centers around engineering new tools for studying biology. I have designed new tools for studying biological systems at length scales ranging from individual molecules to whole tissues.

You can find a full list of my papers and patents on <u><a href="https://scholar.google.com/citations?user=zeiZjPAAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% include base_path %}

In Situ Transcriptomics
------
Currently, I am leading the development of the in situ transcriptomics platform at the Chan Zuckerberg Biohub. Towards this, I am building hardware and software tools to reproducibly automate in situ transcriptomics assays and contributing to open sources software projects such as <u><a href="https://github.com/spacetx/starfish/">starfish</a></u>, <u><a href="https://github.com/napari/napari/">napari</a></u>, and <u><a href="https://github.com/czbiohub/imagingDB">imagingDB</a></u>.

{% for post in site.in_situ reversed %}
  {% include archive-single-research.html %}
{% endfor %}

Microfluidic tools for single-cell analysis
------
Protein localization and post translational modifications are key to understanding cell state, yet remain difficult to measure with single cell resolution. To meet this need, as a graduate student in the Herr Lab, I developed microfluidic tools for single cell protein analysis. Leveraging the favorable mass transport scaling of microfluidic length scales, we extended the sensitivity of traditional protein assays. In particular, we developed tools for measuring the subcellular localization of proteins from single cells and for highly-selective measurement of protein isoforms from single cells.

**Selected publications**
{% for post in site.microfluidics reversed %}
  {% include archive-single-research.html %}
{% endfor %}

Microfabrication of functional hydrogels
------
To extend the capabilities of microfluidic devices for biological assays, I developed fabrication methods that add new functions to hydrogels.

**Selected publications**
{% for post in site.microfab reversed %}
  {% include archive-single-research.html %}
{% endfor %}

Computational biomechanics
------
To elucidate the mechanisms through which soft tissues (e.g., articular cartilage) transduce mechanical signals into microstructual and biochemical changes, we integrated experimental systems and computional models to study how mechanical properties change in response to mechanical stimulus.

**Selected publications**
{% for post in site.res_biomech reversed %}
  {% include archive-single-research.html %}
{% endfor %}
