---
name: Hw10 - Project_1
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Example including vega-lite

<vegachart schema-url="{{ site.baseurl }}/assets/json/project_1.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/assets/json/project_1.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/python_notebooks/Hw10-proj_1.ipynb" text="The Analysis" %}
</div>

