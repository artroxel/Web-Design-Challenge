# Web-Design-Challenge

## Latitude - Latitude Analysis Dashboard
For this we'll be creating a visualization dashboard website using visualizations. Specifically, we'll be plotting weather data.
In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

## Website Requirements
The website must consist of 7 pages total, including:

A landing page containing:

An explanation of the project.
Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.


Four "Visualizations" pages, each with:

A descriptive title and heading tag.
The plot/visualization itself for the selected comparison.
A paragraph describing the plot and its significance.


A "Comparisons" page that:

Contains all of the visualizations on the same page so we can easily visually compare them.
Uses a Bootstrap grid for the visualizations.

The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.


A "Data" page that:

Displays a responsive table containing the data used in the visualizations.

The table must be a bootstrap table component. Hint

The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe.
