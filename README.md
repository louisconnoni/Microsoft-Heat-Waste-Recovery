# Microsoft-Heat-Waste-Recovery

**Undergraduate Student Research**
**Microsoft Funded Project**
<br>

- Identify what functions and methods were used for each section of the project.

<img src="assets/Screenshot 2026-08-30 141914.png" width="55%" />
## Overview

As an undergraduate researcher I was tasked to work under a postdoctoral scholar to develop a heat waste recovery tool. The product would evaluate different "offtakers" to compare their carbon, water, economic and social benefits to the local stakeholders. Part of my responsibility was to present results through biweekly meetings where we would share project updates. The scoring system uses a normalised performance index to evaluate a data centers reuse of heat waste compared to other options. My major responsibility was to develop a web app to take the data centers input data convert it to useful data for the grading system and help visualise the data for the end user. 

## Taking Data Input
The data organised in an excel for the scoring system. One of my initial tasks was to use the pandas library in python to import the data to the scoring system. The streamlit library was also introduced to publish and format the webapp. 
<img src="assets/Cover Picture.png" width="55%" />

## Visualising Scoring Data
Scoring data was visualised using streamlits plot function. For effective data visualization it was my task to take Microsoft's suggestions and introduce two plots to convey the data. One plot compared each subscore individually to visualize what each offtaker performed best. The other plot visualisation was to stack the subscores to better convey the total out of maximum score of 1. I also introduced bar sliders to adjust the weighting each subscore within the total.

<img src="Offtaker results 1.png" width="55%" />
<img src="offtaker results 2.png" width="55%" />

## Visualising Uncertainty

Handling uncertainty and scoring required using a normalised score with other offtakers. The post doc and I collaborated on a seperate excel to store the offtakers and later use for the uncertainty calculations and scoring


## Visualising Economic Data

Streamlits built in drop box command was used to change the data visualisation to display economic data.
<img src="Economic Data.png" width="55%" />

## Handling Multiple Offtakers

Handling multiple offtakers required using nested for loops to identify the offtaker then run the scoring method needed for that particular offtaker. Separate files were imported into the main webapp folder. 
