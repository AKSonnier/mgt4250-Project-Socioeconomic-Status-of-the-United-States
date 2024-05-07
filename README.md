# MGT 4250 Spring 2024 Course Project
Author: Alexander Sonnier, (asonnier@elon.edu)

Link to the Tableau Public Application:
https://public.tableau.com/views/DataVisualizationProjectSocioeconomicStatusoftheUnitedStates/VerticalBarPlot?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

This **repository** is for the course project of MGT 4250 at Elon University.

## Project Description
### Questions of Interest
- Do cities/states with gentrified/poorer areas have a lower economic status compared to other cities?
- Does a specific sector of business affect the socioeconomic status and livability of a community?
- Does a certain race, population, or education attainment of the population indicate a certain socioeconomic status in the United States?

### Statements of Importance
These questions are *especially* **important** for understanding these visualizations because
1. This is important to know because big, metropolitan cities like New York City or Chicago have a high homeless population with little room for external housing and limited job opportunities for this population. It also causes extra resources to be diverted away from developing more career opportunities and infrastructure to facilitate better business and bring in more money for these areas. For example, “unsheltered homelessness is particularly high in California at about 68% compared to 24% of the rest of the nation” (Wurden, 2018). The US Interagency Council on Homelessness also says that”’homelessness is costly to society because people experiencing homelessness frequently require the most expensive publicly-funded services and institutions’” (Wurden, 2018). Homelessness, especially over the past couple of years, has become too rampant and being able to find the specific areas where it is the most rampant through Data Visualization will be able to address and find the most effective way to divert money and resources effectively.

2. This is important to know because some parts of the country are known for one or two industries they specialize in like Lafatyette, Louisiana, being known for extracting and selling oil. The type of industry in a city will also influence what people and businesses will be attracted to developing the city’s general economy. For example, the types of companies that will have the strongest impact on economic growth are high-value industries like “speciality manufacturing companies, consulting firms, and software businesses” (Endeavor Insight, 2019). These jobs could also be able to bring in revenue from other locations outside the main city and create more knowledge-intensive jobs. Another type of company cities should bring in are Entrepreneurial companies, since “businesses with local founders reinvest a greater share of their sales into the regions where they are based”, being able to create more jobs and grow the local economy as a result (Endeavor Insight, 2019). Examples of these places would include Silicon Valley in California, which has lots of tech companies and startups hosted like Google, AMD, Apple, Nvidia, HP, Meta, and the Research Triangle between Raleigh, Durham, and Chapel Hill, North Carolina that is becoming the second Silicon Valley of the East Coast. This could be interesting to look towards within my research and data gathering process.

3. The third question is important answers an important point about how a community has grown and the economic status of it as well. For example, if a population from a gentrified area only has the education level up to a high school diploma, that would limit the job development for an area to lower paying and lower skill level jobs, meaning there is limited growth economically for that area. This would result in less housing development and less infrastructure for the area and a higher amount of people would be unemployed as well. I was able to incorporate the question and data into 3 Tableau visualizations that I feel are able to answer the questions I laid out.

## Data Description & Upload
For this project, I will attempt to answer these three questions utilizing data found on data.gov and the US Census Bureau. Based on what was answered from the initial questions, I was able to find data, including: 

- **Data.gov**: I found my data through searching for the “Socioeconomic Status in the United States”. The dataset I was able to find was named “Country-level Data Sets” from the Data.gov website. Then, under the Web page with links to Excel Files, I clicked download and downloaded the file named “Unemployment and Median Household Income for the US States and Countries, 1970-2022”. Then, I also downloaded the “Educational Attainment for Adults Age 25 and Older for the U.S., States, and Counties, 1970-2021”. For this initial data, I then delete the descriptions of the data to make it read correctly in Tableau.

- **U.S. Bureau of Labor Statistics**: I found this set of data through googling “amount of people working in each industry in the United States excel file”. The first link is to the Employment by major industry sector by the Bureau of Labor Statistics, which you are able to download the dataset by clicking on the XLSX link under the available formats on the top left of the chart. In order to clean up the dataset, I copied the rows of data in the original excel file of only the industries instead of the headers and pasted it into a new excel file.

### Data Columns Used
Figure 1 (Symbol Map of Unemployment Rate by State):
- State or State Abbreviation of each State and County in the United States (Dimension).
- Unemployment_rate_2022 (Measure in Percentage): The average unemployment rate, in percentage, for the states and counties for the state in the United States in 2022.

Figure 2 (Vertical Bar Plot of People with a High School Diploma Only and a Bachelor's Degree or Higher by State, 2017-2021):
- State or State Abbreviation for each State in the United States (Dimension)
- High School Diploma Only 2017-2021 (Measure): The amount of people in the United States per state and county who have only gotten a High School Diploma from 2017-2021.
- Bachelor’s Degree or Higher 2017-2021 (Measure): The amount of people in the United States per state and county that have earned a Bachelor's Degree or Higher at an accredited institution from 2017-2021.

Figure 3 (Scatter Plot of Employment in 2012 versus Relative Change of Employment from 2012-2022): 
- Employment 2012: The number of people employed across a series of industries in the U.S. Bureau of Labor Statistics in 2012.
- Industry Sector: Label of the Industry Sectors in the U.S. Bureau of Labor Statistics database.
- Relative Change: The relative average change, in percentage, of the different industries from the US Bureau of Labor Statistics from 2012-2022.

## Interpretationg Visualizations
1st Visualization (Symbol Map): ![image](https://github.com/AKSonnier/mgt4250spring2024class22/assets/168772707/96fa71b8-43de-4919-9f4a-2575b0dd1073)

2nd Visualization (Vertical Bar Plot): 

3rd Visualization (Scatter Plot): 


## Discussion and Summary






### Works Cited
Publisher Economic Research Service, Department of Agriculture. (2024, January 3). Department of Agriculture - County-Level Data Sets. Catalog. https://catalog.data.gov/dataset/county-level-data-sets

U.S. Bureau of Labor Statistics. (2023, September 6). Employment by Major Industry Sector. U.S. Bureau of Labor Statistics. https://www.bls.gov/emp/tables/employment-by-major-industry-sector.ht

Julia von Wurden, C. (2018, May 1). The impact of homelessness on economic competitiveness. American Security Project. https://www.americansecurityproject.org/impact-homelessness-economic-competitiveness/

Pablo Sabillon, J. (2019, June 7). What types of companies have the strongest impact on economic growth?. Entrepreneurship Ecosystem Insights. http://www.ecosysteminsights.org/what-types-of-companies-have-the-strongest-impact-on-economic-growth/
