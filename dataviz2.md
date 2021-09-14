# Government Debt Data Visualizations

Below are three visualizations that all use the same [government debt data](https://data.oecd.org/gga/general-government-debt.htm) from the OECD. Here, I experiment with a couple of free, on-line tools for creating quick and easy visualizations. The data includes Debt-to-GDP ratios from 34 different countries spanning the years 1995 - 2020. 

<i><b>Data Source:</b> OECD (2021), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 13 September 2021)</i>

## Visualization 1: OECD Website Tool
This first visualization simply uses the chart tool provided on the OECD website. This simple tool is quite intuitive; you can scroll to a desired year, highlight specific countries, and choose between visualizing data over time in a line chart, a bar chart for a specific year of data, a map with 'bubbles' whose size indicates the Debt-to-GDP ration, or a simple table. While the tool is simple and quick, there is not too much room for customization. Users cannot alter colors, or much outside of the type of chart they want or the data they want to display. Any further customization would require a more advanced tool

I chose to highlight the United States, to get the reader thinking about where the United States falls in relation to other countries. A simple highlight (red) of the US serves this purpose. 

<iframe src="https://data.oecd.org/chart/6sDC" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6sDC" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

## Visualization 2: Flourish Sparklines
Here, I visualize the same data in a 'sparkline' format using the online tool [Flourish](https://flourish.studio/). Flourish adds more customization capabilities than the OECD website tool, but users are still limited in what they can do. 

The data in this sparkline format is good for comparing trends over time across countries. We can see if any countries saw similar uptiks or drops in their Debt-to-GDP ratios at around the same time, and how countries vary in their overall trajectory.

I chose to visualize the Debt-to-GDP ration in a reddish color to indicate that what we are looking at is "bad."

<div class="flourish-embed flourish-chart" data-src="visualisation/7254814"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Visualization 3: Flourish Heatmap
Lastly, I visualized the data again in Flourish in a heatmap format. I thought this could be a good way to more clearly see the extent or severity of government debt and its change over time. I also thought it could be a clearer way to compare the extend of debt between countries. It becomes clear from this graph the extent of Japan's debt (compared to its GDP). We also notice that with a few small exceptions, no country seems to be decreasing their Debt-to-GDP ratio. I chose to visualize the Debt-to-GDP ration in reds, with the higher the ratio, the darker the red. This is meant to communicate severity, vs the lighter colors for those countries/periods with lower ratios.

<div class="flourish-embed flourish-heatmap" data-src="visualisation/7254991"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
