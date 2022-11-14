---
name: Hw10 - Project_2
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Project Description

1. The visualization is a scatter plot described that for each agency, the year of buildings they have constructed.

2. I use pandas to read csv data to an external site. I use a color scheme to color variable 'Year Constructed'. And I add 'title' to x and y axis.

3. I use alt.data_transformers.disable_max_rows() to make the data satisfy 'number of rows larger than maximum' requirement.

4. I use tooltip to achieve interactive. When I move the mouse to the different color circle, it will show the specific number of the year. Also I can zoom in and zoom out the visualization
<vegachart schema-url="{{ site.baseurl }}/assets/json/project_2.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/assets/json/project_2.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/python_notebooks/Hw10-proj2.ipynb" text="The Analysis" %}
</div>

