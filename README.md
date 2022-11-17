# Plotly_Belly_Button_Biodiversity
Building an interactive dashboard using JavaScript and Plotly.js to explore and visualize data on the human bellybutton biodiversity with also an interactive environment deployed.

## Deployed Environment
Visit the Plotly Bellybutton Biodiversity dashboard here.

### Resources
Data:
samples.json
Software/Application:
JavaScript
Plotly.js
HTML/CSS
Bootstrap
D3 Visualization
## Project Overview
This project incorporated a dynamic and interactive visualization dashboard and charts using Plotly.js with a human belly button diversity dataset. Interactive dashboard and charts display bacteria that live inside the human body. Upon selection of an id number in a pull down list, the id metadata will be displayed in a div element and the top ten bacterial samples will be displayed in a pie chart and bubble chart.

## Results
* Since the task was to only plot the top 10 values, the three arrays were sliced and reversed to display the bar chart as below.
![sstop10](https://user-images.githubusercontent.com/111541268/202551261-19124fcf-8a86-4344-b098-9feda4f1c651.png)


* The entire sample arrays were used to plot a bubble chart.



![ssbubble](https://user-images.githubusercontent.com/111541268/202551299-e771c00b-44fb-4a5a-8993-bab79c1b6758.png)


* To create a gauge chart. Using the documentation, an indicator trace was created with wfreq as the value for plotting. Any null values were given a value of zero.
   * The gauge chart accounts for weekly washing frequency values ranging from 0-9.
   *  The default bar that indicates the value was set to transparent so that a needle pointer could be used on the chart.



![sswashing](https://user-images.githubusercontent.com/111541268/202551319-2f7eb59c-f059-44ef-87b6-3a858808cff1.png)


## Dashboard Framework
custom CSS was used to pretty up the dashboard. A screenshot of the dashboard can be seen below.
The complete results was an interactive dashboard launched through GitHub Pages.




![ssdata](https://user-images.githubusercontent.com/111541268/202551344-b3841de7-058a-4639-b172-ec05f70245d9.png)

