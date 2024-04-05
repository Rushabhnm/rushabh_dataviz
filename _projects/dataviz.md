---
name: Vega Lite Example Project
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

Example comes from this [great blog post right here](https://blog.4dcu.be/programming/2021/05/03/Interactive-Visualizations.html) that was also used in [our test import script](https://github.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/blob/main/week01/test_imports_week01.ipynb).

We can use a vegachart HTML tag like so:

```
<vegachart schema-url="{{ site.baseurl }}/assets/json/cars.json" style="width: 100%"></vegachart>
```

<vegachart schema-url="{{ site.baseurl }}/assets/json/bar.json" style="width: 100%"></vegachart>
<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter_plot.json" style="width: 100%"></vegachart>


## About the Plot 1

- The code creates a bar chart with Altair, displaying building counts by acquisition year and status. Bars are colored to represent different statuses (active, inactive, demolished), showing their distribution over time.
- Chosen based on "Bldg Status" to visually differentiate statuses for easier interpretation.
- Aggregated data to count buildings by acquisition year and status using count().
- Added tooltip for detailed info (year acquired, status, count) on hover, enhancing interactivity and insights. Made chart interactive with .interactive() for clearer understanding and engagement.

## About the Plot 2

- The code generates a scatter plot with Altair, showing the relationship between building "Square Footage" and "Year Acquired." Each circle represents a building, colored by its "Bldg Status" (e.g., active, demolished).
- Color Scheme is based on "Bldg Status" to visually differentiate statuses.
- Added .interactive() for hover tooltip with detailed info (Agency Name, Year Acquired, Square Footage, Bldg Status), enhancing engagement and clarity.
```
<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://blog.4dcu.be/programming/2021/05/03/Interactive-Visualizations.html" text="The Analysis" %}
</div>
```

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

