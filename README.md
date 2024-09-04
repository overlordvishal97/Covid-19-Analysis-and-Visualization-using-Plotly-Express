# Covid-19-Analysis-and-Visualization-using-Plotly-Express
Analyse Covid-19 data and will visualize it using Plotly Express in Python.

# Importing three datasets into this project

covid– This dataset contains Country/Region, Continent,  Population, TotalCases, NewCases, TotalDeaths, NewDeaths,  TotalRecovered, NewRecovered, ActiveCases, Serious, Critical, Tot Cases/1M pop, Deaths/1M pop, TotalTests, Tests/1M pop, WHO Region, iso_alpha.
covid_grouped– This dataset contains Date(from 20-01-22 to 20-07-27), Country/Region, Confirmed, Deaths, Recovered, Active, New cases, New deaths, New recovered, WHO Region, iso_alpha.
coviddeath– This dataset contains real-world examples of a number of Covid-19 deaths and the reasons behind the deaths.

# Visualization of Data in terms of Maps

We can use choropleth to visualize the data in terms of maps, with maps usually being the predominant way of visualizing the data. Since COVID-19 is a global phenomenon and so we look through and fix them in terms of wall maps. Ortho-graphics, rectangular and natural earth projection to visualize the data With dataset2 for the purpose as it has Dates column. It will look at the growth of Covid-19 (from Jan to July 2020) as in how the virus reached across the world.

# Visualize text using Word Cloud
Visualize the causes of death due to covid-19, as covid-19 affects people in different ways, hence creating a word cloud to visualize the leading cause of covid-19 deaths. To visualize the text the steps need to be followed are-

Used to convert data elements of an array into list.
Convert the string to one single string.
Convert the string into word cloud
