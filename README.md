# Visualizing Gender Gap 
#### By Eloá França Verona and Ali Mahad

### The goal
Women are viral for economic growth, but their value is not reflect by positions and wages in labor market. The undervaluing of women's work and the under-utilisation of their skills is both a lot resource and a disadvantage to a deserving workforce.

**We wanted to visualize and compare performance of various countries in overcoming wage gap.**

### The data
The data is from the  [Organization fo Economic Co-operation and Development](https://data.oecd.org/) (OECD)
You can find the wage gao data at this [link](https://data.oecd.org/earnwage/gender-wage-gap.htm) and the employment gap data at this [link](https://data.oecd.org/emp/employment-rate.htm).
We used R and Excel for the data processing. 

### The visualization
We coded the visualization using the  [D3.js](https://d3js.org/) library.
Opening the bar_chart.html in a browser, will show a bar chart showing the wage gap for the year of 2014 for the OECD member countries.
Hovering over a bar you can see the full country name and the wage gap. Clicking on a bar will open a pop-up with more detailed information on that country.
The pop-up shows a line graph with employment gap and wage gap from 2000-2014. A slider allows for the date range to be changed.
The pop-up also shows information of the percentage difference in wage gap and employment gap between the beginning and the end of the time period.
It also shows the countries ranked in terms of how much they have improved in the time period. Users can click in a country in the rank to see the detailed data for that country. 
The user can navigate the data by clicking in the arrows to the side of the pop-up.

### D3 tutorials and code examples
Here are some of the tutorials and examples we looked into to figure out D3. We are grateful to the authors for making those resources available.

* [How to make a bar chart in D3](https://bost.ocks.org/mike/bar/) (good introduction to D3) 
* [Slider example 1](https://bl.ocks.org/mbostock/6452972)
* [Slider example 2](https://github.com/evoluteur/d3-dual-range-slider/tree/master/js)
* [Responsive design in D3](https://blog.webkid.io/responsive-chart-usability-d3/)
    
  

