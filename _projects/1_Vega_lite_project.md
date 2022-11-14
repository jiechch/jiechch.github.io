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


# Project Description

1. The visualization is a chart described the number of reports in each state, there are two classifications of these reports, the orange color is Class B, the blue color is Class A, the red color is class C.

2. I use pandas to read csv data to an external site. I use a color scheme to color variable 'classification'. And I add 'title' to x and y axis.

3. I use parse_dates to format 'data' variable.

4. I use similar plots to my HW9, the x and y coordinates are same, but I add color to clarify two classfications of reports. Also I use interactive in this visualization to zoom the chart so that we can get the number as precise as it could be.

5. I use tooltip to achieve interactive. When I move the mouse to the different color, it will show it's class A or class B which helps to clarify the meaning of different color bar.

<vegachart schema-url="{{ site.baseurl }}/assets/json/project_1.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/assets/json/project_1.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/python_notebooks/Hw10-proj_1.ipynb" text="The Analysis" %}
</div>

