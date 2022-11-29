---
name: Final Contextual Visualization 1
tools: [Python, HTML, vega-lite]
image: assets/pngs/visualization1.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Project Description


<vegachart schema-url="{{ site.baseurl }}/assets/json/final3_1.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/assets/json/final3_1.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/python_notebooks/Final Contextual Viz1.ipynb" text="The Analysis" %}
</div>

