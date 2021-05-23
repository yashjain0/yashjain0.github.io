---
layout: project
type: project
image: images/micromouse.jpg
title: Stock-Interactions
permalink: projects/Stock-Interactions
# All dates must be YYYY-MM-DD format!
date: 2020-12-01
labels:
  - Jupyter Notebook
  - MongoDB
  - Pandas
  - Java Script
summary: I created a website which compares stock prices of Nifty 50 with series of politically and economically important dates.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

Stock Interactions started with the agitating thought of companies getting partnered up with major political parties and how they influence policy making in the country in their profit.

For this project, I collected data of stocks of different companies from NSE's very own NSEpy API.  I started by programming the basics, such as plotting the data gained from API call using Matplotlib and pandas. These both are python libraries for data visualization. Then I created a basic database for different policies and elctions with the help of my companions from Political Science field. Plotted both data sets together and tried to see the patterns among them.

Working on better pattern visualization.

Here is some code that illustrates how we read values from the database:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



