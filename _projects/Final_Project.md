---
name: Final Project Part 3
tools: [Python, HTML, vega-lite]
image: assets/pngs/visualization.png
description: This is a "showcase" project that uses vega-lite for interactive viz!

custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Project Description


<vegachart schema-url="{{ site.baseurl }}/assets/json/final3.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/assets/json/final3.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jiechch/jiechch.github.io/blob/main/python_notebooks/final project - part 3.ipynb" text="The Analysis" %}
</div>
<div class="text">
<p>
    Write Up
</p>
<p>The dataset our group chose to analyze is Urbana permits dataset, having 37286 samples, which is large enough to sppourt us do deep analysis. Our purpose is to investigate yearly changes of estimated cost for different permits type. The dataset has both of categorical and numerical attributes, including Permit Number, Permit Type, Issue Date, Permit Status, Estimated Cost, Fee Amount, etc,. In our analysis, we selected estimated cost, permit type and issue date to analyze the changing range by using Altair package to plot.
</p>
<p>
We used Altair package to do two interactive plots, which supports zoom/pan and selection functions for our audience and users. They can see a story after choosing one permit type in the second plot, and the first plot would correspondingly change to show detailed yearly estimated cost range for that permit type.
</p>
<p class="text">
The first plot demontrates yearly estimated cost under a specific permit type from 1998 to 2020. and the plot also shows that there are also some flunctuations for a same permit type on a same issue date. On the second plot, count of records is set as x-axis and permit type is y-axis. It is clear to see that, electrical permit, mechanical permit and plumbing permit has greatest amount of records. 
</p>
</div>






