# Belly-Button-Biodiversity

## Overview of Project

In this project, Roza who is a biological researcher is interested in bacterial species that are capable of synthesizing proteins that taste like beef. She has a hypothesis that there is an organism that can be provide the next best taste to beef and beilives it can be found from the bacteria that lives on human body. To test her hypothesis she has sampled navals of individuals across the country to identify the bacterial species that colonized the humans belly button. As a result, a website with an interactive dashboard is built to explore the the dataset of the Belly Button Biodiversity.

### Purpose

The purpose of this project is to complete building the dashboard by creating engaging and dynamic charts which displays the bacterial data for each volunteer by simply allowing the participitants to select their Id numbers to be able to view the top ten bacterial species that live in their navals. By this way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, these volunteers will be able to determine whether that species is found in their naval or not. As a result of this, Plotly which is a data visualization library of JavaScript is used to createan interactive data visualization for the webpage in terms of the following charts:

- Horizontal Bar Chart
- Bubble Chart
- Gauge Chart 

## Resources

**Documentations:** [Gauge Chart in JavaScript](https://plotly.com/javascript/gauge-charts/), [Layout Object](https://plotly.com/python-api-reference/generated/plotly.graph_objects.Layout.html).

## Results

This section of the project focuses on the results achieved using knowldege of JavaScript, Plotly, and D3.js for creating the horizontal bar, bubble and gauge charts.

**Horizontal Bar Chart**

The horizontal bar chart was created using JavaScript Plotly library which displays the top 10 bacterial species which are also known as Operational Taxonomic Units, or OTUs when an individual's ID is chosen from the dropdown menu on the webpage. As it can be seen in the figure below, the horizontal bar chart displays the **sample_values** as the values on the x axis, and the **otu_id** as the labels.

![Horizontal Bar Chart](static/images/Horizontal_Bar_Chart.png)

**Bubble Chart**

The bubble chart was created using knowledge of JavaScript, Plotly and D3.js which illustrates the concentration of the samples and bacterial biodiversity. As it can be futher seen in the figure below, the x-axis values of the chart displays the **otu_id** and the y-axis values demonstrates the **sample_values**. Additionally, the marker size is changing with respect to the **sample_values**. 

![Bubble Chart](static/images/Bubble_Chart.png)

**Gauge Chart**

Lastly, the gauge chart was created as depicted in the figure below. As it can futher be seen the gauge chart displays the weekly washing frequency's value as a measure from 0-10 on the progress bar when an individual ID is selected from the drop down menu.

![Gauge Chart](static/images/Gauge_Chart.png)

## Summary

In conclusion, the dashboard was completed successfully by adding dynamic charts which would help the volunteers who are interested in selling their bacteria to Improbable Beef to visualize and explore the types of bacteria that colonize their belly buttons. Additionally, using knwodlge of HTML and Bootstrap the dashboard was further customized using the following:

- An image was added to the jumbotron.
- Variety of compatible colors were added to the webpage.
- Custome font was used for text added to the webpage.
- Additional information about the project was added as a paragraph on the page.
- Additional information about what each chart visualizes was added under each each graph.

The customized dashboard is illustarted in the figure below which can be viewed in the Github pages through the following URL: []().

![Dashboard](static/images/Customized_Dashboard.png)
