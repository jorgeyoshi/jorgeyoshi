---
name: HW 5
tools: [Python, HTML, vega-lite]
image: assets/pngs/bigfoot.png
description: This is my Homework 5 post!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

<vegachart schema-url="{{ site.baseurl }}/assets/json/finalmap.json" style="width: 100%"></vegachart>

## Search The Data & Methods

Below is where we can put some links to both the data and the analysis code as buttons:

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

