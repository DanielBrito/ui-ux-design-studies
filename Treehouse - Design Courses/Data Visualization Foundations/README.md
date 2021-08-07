# Data Visualization Foundations - Notes

What is data visualization? A simple answer might be something like the graphic representation of data. But to get a better understanding of what practitioners of data visualization do, let’s start with the term data. By data, I mean raw, unorganized facts and numbers. Practitioners of data visualization take raw, hard to grasp data and turn that data into information by providing context and a purpose.

---

## What is Data Visualization?

### **Vocabulary**

- **data:** raw, unorganized facts and numbers.
- **information:** data with context and a purpose.
- **data visualization:** using the graphic representation of data to tell a meaningful story

### **Further Reading**

- **[The Case For Dennis Rodman](https://skepticalsports.com/the-case-for-dennis-rodman-part-14-c-rodman-v-ancient-history/)**
- **[Data visualization beginner's guide: a definition, examples, and learning resources](https://www.tableau.com/learn/articles/data-visualization)**

---

## Before You Begin: Preparing Your Story

### **Four steps before starting data visualization**

1. Identify your audience.
2. Decide on your story.
3. Double-check your data
4. Choose the right amount of data

### **Further reading**

- **[Good Charts](https://store.hbr.org/product/good-charts-the-hbr-guide-to-making-smarter-more-persuasive-data-visualizations/15005)**
- **[Job Market Tracker](http://graphics.wsj.com/job-market-tracker/)**
- **[Poppy Field project](https://www.poppyfield.org/)**

---

## Bar Charts

A bar chart uses rectangular bars to make numerical comparisons between independent categories of data. The larger the rectangle, the greater the value represented.

### **Vocabulary**

- **Bar chart:** a chart that uses rectangular bars to make numerical comparisons between independent categories of data. The larger the rectangle, the greater the value represented.

### **Further reading**

- **[The purpose of visualization is insight, not pictures: An interview with Ben Shneiderman](http://interactions.acm.org/blog/view/the-purpose-of-visualization-is-insight-not-pictures-an-interview-with-ben)**
- **[Data Visualization and Storytelling Part 1: Which is the Right Chart?](https://www.grazitti.com/blog/data-visualization-and-storytelling-part-1-which-is-the-right-chart/)**
- **[Choosing the right chart type: Bar charts vs Column charts](https://www.fusioncharts.com/blog/bar-charts-or-column-charts/)**
- **[Five Ways to Mislead with Data Visualizations](https://www.tessellationtech.io/top-five-ways-mislead-data-visualization/)**
- **[Fundamentals of Data Visualization: Visualizing Amounts](https://clauswilke.com/dataviz/visualizing-amounts.html#fig:titanic-passengers-by-class-sex)**

---

## Histograms

The most obvious visual difference between histograms and bar charts is in the way the rectangular bars are presented: in histograms, the bars touch, whereas bar charts have space separating each bar. But how do we know when to use each one?

### **Vocabulary**

**What is a histogram?**

- Shows the distribution of numerical data
- X-axis consists of bins containing ranges of numbers
- X-axis uses continuous numbers
- Vertical bars touch each other

### **Further reading**

- **[differences between histograms and bar charts](https://www.storytellingwithdata.com/blog/2021/1/28/histograms-and-bar-charts)**

---

## Pie charts

A pie chart shows how a total amount is divided into parts. The size of each slice indicates a proportion of the whole. You can imagine this as a literal pie. If I cut a pie into six equal slices and eat one of them, we’re left with a visual representation of how much of the pie has been eaten–that’s one-sixth of the total pie–and the five-sixths of the pie that remains.

### **Vocabulary**

**What is a pie chart?** A circular graph showing how a total amount is divided into parts. The size of each slice indicates a proportion of the whole.

- Compare parts of a whole
- Percentages must add up to 100%
- Don’t use 3D or distort slices
- Limit number of slices
- Storytelling shouldn’t depend on comparing similarly sized slices

### **Further reading**

- **[Think before you pie chart (and more effective ways to visualize your data)](https://medium.com/geckoboard-under-the-hood/think-before-you-pie-chart-and-more-effective-ways-to-visualize-your-data-862ea3456b26)**
- **[Survey of Web Accessibility Practitioners #2 Results](https://webaim.org/projects/practitionersurvey2/)**
- **[An updated post on pies](https://www.storytellingwithdata.com/blog/2017/1/10/an-updated-post-on-pies)**

---

## Line and Area Charts

Line charts show the change of data over a continuous time span. If the story you’re telling depends on showing trends in your data or changes in value, line charts are an effective choice.

### **Vocabulary**

**Line chart:** a chart that shows the change of data over a continuous time span. Line charts show trends or changes in value.

**Area chart:** Similar to a line chart, but the area between lines and the x-axis is filled in

**Stacked area chart:** An area chart in which one data set is stacked on top of another, demonstrating individual contributions to a whole.

### **Further reading**

- **[Line graph](https://datavizcatalogue.com/methods/line_graph.html)**
- **[A complete guide to line charts](https://chartio.com/learn/charts/line-chart-complete-guide/)**
- **[Bar charts should always start at zero. But what about line charts?](http://www.chadskelton.com/2018/06/bar-charts-should-always-start-at-zero.html)**
- **[Choosing the right chart type: Line charts vs Area charts](https://www.fusioncharts.com/blog/line-charts-vs-area-charts/)**
- **[A complete guide to area charts](https://chartio.com/learn/charts/area-chart-complete-guide/)**

---

## Scatter Plots

When you’re examining a set of data, sometimes you’re unsure whether there’s a correlation between two variables or not. When I say correlation, I mean how strong a relationship or connection is there between these two factors. In a scatter plot, we place various points on a graph based on two different variable values, then study the correlation between those variables.

### **Vocabulary**

- **Scatter plot:** a chart that displays the values of two different variables as points so we can study the correlation between the variables.
- **Outliers:** data points that don’t fit the general pattern.

### **Further reading**

- **[What Is a Scatter Plot and When To Use One](https://visme.co/blog/scatter-plot/)**
- **[Scatterplot](https://datavizcatalogue.com/methods/scatterplot.html)**
- **[Per Game Team Statistics in the NBA](https://sports.sites.yale.edu/game-team-statistics-nba)**
- **[Correlation vs Causation: Definition, Differences, and Examples](https://clevertap.com/blog/correlation-vs-causation/)**

---

## Maps

So far, the visualizations we’ve covered have mostly taken place on a grid with a labeled x-axis and y-axis. The exception is the pie chart, but even the pie chart has a fixed shape and strict parameters on how it can be presented. However, sometimes the story you’re telling involves geographic data. It might be possible to convey election results using a bar chart, for example, but users will likely find election information more meaningful when results are visualized by city, state, or county. Let’s take a look at some different ways that data visualization and geographic maps intersect.

### **Vocabulary**

- **Choropleth map:** a map created by coloring in existing geographic regions based on the relative frequency of a variable.
- **Proportional symbol map:** a map in which existing geographic regions include symbols that increase in size based on the absolute frequency of a variable.
- **Geographic heat map:** a map demonstrating the frequency of data points while ignoring geographic boundaries.

### **Further reading**

- **[Data Visualization In Web Design: Why We Need It More Than Ever](https://xd.adobe.com/ideas/principles/web-design/data-visualization-web-design-need-ever/)**
- **[What to consider when creating choropleth maps](https://academy.datawrapper.de/article/134-what-to-consider-when-creating-choropleth-maps)**
- **[Proportional symbol maps](https://xdgov.github.io/data-design-standards/visualizations/proportional-symbol-map)**
- **[Geographic heat maps](https://mode.com/example-gallery/geographic-heat-map/)**

---

## Sketching

Effective data visualization sketches should be executed quickly, should communicate information, and are meant to be exploratory.

### **Effective Data Visualization Sketches**

- Executed quickly
- Communicate information
- Exploratory

### **Further reading**

- **[How to Sketch, Doodle, and Draw Data Visualization Drafts by Hand](https://depictdatastudio.com/how-to-sketch-doodle-and-draw-data-visualization-drafts-by-hand/)**
- **[How and Why We Sketch When Visualizing Data](https://medium.com/nightingale/how-and-why-we-sketch-when-visualizing-data-d843e0ce8c74)**
- **[Mona Chalabi (@monachalabi) | Instagram](https://www.instagram.com/monachalabi/)**

---

## Accessible Visualizations

By accessible, I mean designing your visualizations so disabled users can understand them.

### **How to Design Accessible Visualizations**

- Don’t rely on color alone to explain data
- Follow color contrast guidelines
- Label data points directly
- Avoid hover overlays
- Provide alternate descriptions
- Use plain language

### **Further reading**

- **[An intro to designing accessible data visualizations](https://fossheim.io/writing/posts/accessible-dataviz-design/)**
- **[Accessible Data Visualization](https://www.betterment.com/resources/accessible-data-visualization/)**
- **[Web Content Accessibility Guidelines (WCAG) 2.1](https://www.w3.org/TR/WCAG21/)**
- **[Understanding Web Accessibility Color Contrast Guidelines and Ratios](https://css-tricks.com/understanding-web-accessibility-color-contrast-guidelines-and-ratios/)**
- **[Writing Alt Text for Data Visualization](https://medium.com/nightingale/writing-alt-text-for-data-visualization-2a218ef43f81)**
- **[plainlanguage.gov](https://www.plainlanguage.gov/)**
- **[The Daily Routines of Famous Creative People](https://podio.com/site/creative-routines)**
- **[Job Market Tracker](http://graphics.wsj.com/job-market-tracker/)**

---

## Ethical Visualizations

Practitioners of data visualization carry a lot of responsibility. While good charts can create joy, provide insight, or win an argument, bad charts have the potential to confuse, to misinform, or mislead. And in the most extreme cases, a faulty visualization could incite panic.

### **Further reading**

- **[Mapping Coronavirus Responsibly](https://www.esri.com/arcgis-blog/products/product/mapping/mapping-coronavirus-responsibly/)**
- **[Ten Considerations Before You Create Another Chart About COVID-19](https://medium.com/nightingale/ten-considerations-before-you-create-another-chart-about-covid-19-27d3bd691be8)**
- **[Communicating COVID-19 Complexity Through Data Visualization](https://xd.adobe.com/ideas/perspectives/leadership-insights/data-visualization-role-during-pandemic/)**
- **[The Meaning of Colors in Cultures Around the World](https://www.shutterstock.com/blog/color-symbolism-and-meanings-around-the-world)**
