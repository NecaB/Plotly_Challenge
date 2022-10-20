# Plotly_Challenge

This week’s challenge was to create an interactive dashboard consisting of a Bar, Bubble and Gauge chart to explore some (10) bacterial species from volunteer’s belly button.  This was to help candidates identify the bacteria in their bellybutton. To perform this challenge we utilized JavaScript, Plotly and D3.js, HTML and JSON.

## JavaScript 
In the first part of the challenge, we designed a code that would create an array for when a sample is selected from the dropdown menu options for the volunteers. This was displayed with the dashboard default ID number 940. Upon entering the page, the bacterial species of ID number 940 candidate will be shown.  However, menu options are available to display the other volunteers and the bacterial species of their belly button. 

## Plotly
The D3 library was used to read in samples.json data. A code was then created to plot the horizontal and vertical scale ‘x’ axis and ‘y’ axis the labels as well as the marker size, hover-text values and the marker colors for the visualization of the charts.  The demographic data provided the elements utilized in plotting the different labels for the charts. 

## The Bar, Bubble, Gauge Charts 
The charts displayed the ‘x’ and ‘y’ axis, while the layout function was used to insert the different chart titles and additional details about the volunteers. A bonus detail about the washing frequency of the belly button by each volunteer was included on the Gauge Charts to indicate how often they wash their bellybutton.  The charts were then customized to improve the overall presentation for the findings.  
![image](https://user-images.githubusercontent.com/109915684/196853704-e779652c-32f2-49e3-ba60-7be8e2a37da1.png)
