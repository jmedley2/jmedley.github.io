---
name: HW8
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Chart 1

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_1.json" style="width: 100%"></vegachart>

This plot is visualizing the amount of buildings acquired every year by department. I chose a color scheme that has high contrast so it is easier to decipher between departments since there are so many in the legend. I did some transformation on the Python side to reduce the amount of departments in the legend. I grouped all of the appellate courts together and all of the universities together. For interactivity, I decided to allow a zoom since the plot is so big. You can also click on a part of the legend to highlight that department on the axis as a whole. This makes it much easier to see the department you are wanting to look at.



# Chart 2

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_2.json" style="width: 100%"></vegachart>

This plot is vizualizing the amount of buildings in 'abandon', 'in use', and 'in progress' status. I did not have to use any data transformation with Python to display this visualization. This plot is not interactive either. besides from the tooltips, which make it easier to see the exact amounts of each status.

## Search The Data & Methods

Below is where we can put some links to both the data and the analysis code as buttons:

```
<div class="left">
{% include elements/button.html link="https://github.com/jmedley2/jmedley2.github.io/blob/main/python_notebooks/Buildings.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jmedley2/jmedley2.github.io/blob/main/python_notebooks/cleaning.ipynb" text="The Analysis" %}
</div>
```

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/jmedley2/jmedley2.github.io/blob/main/python_notebooks/Buildings.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jmedley2/jmedley2.github.io/blob/main/python_notebooks/cleaning.ipynb" text="The Analysis" %}
</div>

