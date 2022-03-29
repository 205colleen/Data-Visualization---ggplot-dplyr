# Data-Visualization-ggplot & dplyr

## Learning Objectives
-Understand the use of tidyverse, the dplyr and the ggplot2 package
-Manipulate the gapminder dataset using different dplyr verbs
-Create different plots from the results of dplyr verbs using ggplot2

Project Structure
The hands-on project on Data Visualization using dplyr and ggplot2 in R is divided into the following tasks:

## Task 1: Import packages & dataset
About tidyverse, the dplyr, and the ggplot2 package

Why use R and familiarity with the R console

A brief introduction to the Rhyme platform

Load required packages for the project

Create a subset of the gapminder dataset called gapminder_1957

## Task 2: Scatterplots
Plot a scatterplot pop on the x-axis and lifeExp on the y-axis

Change to put pop on the x-axis and gdpPercap on the y-axis

Create a scatter plot with gdpPercap on the x-axis and lifeExp on the y-axis

Adding log Scales to the scatterplots

## Task 3: Additional Aesthetics: Color & Size Aesthetics
Scatter plot comparing pop and lifeExp, with colour representing the continent

Add the size aesthetic to represent a country's gdpPercap

## Task 4: Facetting
Scatter plot comparing pop and lifeExp, faceted by continent

Scatter plot comparing gdpPercap and lifeExp, with colour representing continent and size representing the population, faceted by year

## Task 5: Visualizing summarized data: Scatterplots
Create a variable by_year that gets the median life expectancy for each year

Create a scatter plot showing the change in medianLifeExp over time

Summarize medianGdpPercap within each continent within each year: by_year_continent

Plot the change in medianGdpPercap in each continent over time

Summarize the median GDP and median life expectancy per continent in 2007

Use a scatter plot to compare the median GDP and median life expectancy

## Task 6: Visualizing summarized data: Line plots
Summarize the median gdpPercap by year, then save it as by_year expectancy

Create a line plot showing the change in medianGdpPercap over time

Summarize the median gdpPercap by year & continent, save as by_year_continent

Create a line plot showing the change in medianGdpPercap by continent over time

## Task 7: Visualizing summarized data: Bar plots
Summarize the median gdpPercap by continent in 1957

Create a bar plot showing medianGdp by continent

Visualizing GDP per capita by country in Oceania

Create a bar plot of gdpPercap by country

## Task 8: Visualizing summarized data: Histograms
Filter the dataset for the year 1957. Create a new column called pop_by_mil. Save this in a new variable called gapminder_1957

Create a histogram of the population (pop_by_mil)

Recreate the gapminder_1957 and filter for the year 1957 only

Create a histogram of the population (pop), with x on a log scale

## Task 9: Visualizing summarized data: Boxplots
Create the gapminder_1957 and filter for the year 1957 only

Create a boxplot comparing gdpPercap among continents

Add a title to this graph: "Comparing GDP per capita across continents"
