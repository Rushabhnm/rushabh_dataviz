---
name: DATA VISUALIZATION FINAL PROJECT
tools: [Python, HTML, vega-lite]
image: assets/pngs/assignment8.png
description: This is a visualization for Assignment 8.2 
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# DATA VISUALIZATION FINAL PROJCT


<vegachart schema-url="{{ site.baseurl }}/assets/json/bar.json" style="width: 100%"></vegachart>



#### Description of Dashboard 1:


<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter_plot.json" style="width: 100%"></vegachart>


#### Description of Dashboard 2:


  
<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/Rushabhnm/rushabh_dataviz/blob/main/python_notebooks/HW8.ipynb" text="The Analysis" %}
</div>
