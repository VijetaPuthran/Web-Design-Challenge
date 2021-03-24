# Web-Design-Challenge

## Background

For this assignment, HTML and CSS was implemented to create a dashboard showing the analysis for Latitude compared to other weather factors.

![Images/landingResize.png](Images/landingResize.png)

## Latitude - Latitude Analysis Dashboard

The task was to create a visualization dashboard website using the visualizations created earlier in the weather analysis. Specifically, the weather data is used for plotting.(Resources/cities.csv).

The dashboard includes creating the individual pages for each plot and a means by which we can navigate between them. These pages contains the visualizations and their corresponding explanations. A landing page is also included, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Details

The website consists of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and on clicking an image, it takes the user to that visualization.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A "Comparisons" page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid contains two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.
  * The table is a bootstrap table component.
  * The data is obtained from exporting the `.csv` file as HTML using pandas.

The website at the top of every page, has a navigation menu that:

* Has the name of the site on the left of the navigation bar which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries).