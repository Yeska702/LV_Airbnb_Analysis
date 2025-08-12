## Las Vegas Airbnb Analysis

## Background
As someone who's been fortunate enough to travel internationally an experince Airbnb pricing in cities around the world, I've always been curious how those experiences compared to what travelers encounter when booking a stay in Las Vegas. 

This project explores Airbnb listings in Las Vegas through data analysis to better understand what visitors see when planning their trip, looking at pricing trends, availability and more. Whether you're a travler, host, or data enthusisat. This analysis offers insight into how Vegas Airbnb price are during the year of Sept. 2024 to Sept 2025.

## Data Sources
Dataset was provided by [Inside Airbnb](https://insideairbnb.com/get-the-data/) Clark County, NV, Nevada, United States. Data is licensed under [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)

## Tools
- RStudio - Data Cleaning, Anaylzying, Visualization and Data Exporting
- Tableau - [Interactive Visualization](https://public.tableau.com/app/profile/marcos.paredes/viz/Tableau_LV_Airbnb_Analysis/Sheet1?publish=yes&showOnboarding=true)




Having recently completed the Google Data Analytics Cerificate, I am now equipped to apply the six phasees of data analysis.
  - Ask
  - Prepare
  - Process
  - Analyze
  - Share
  - Act


## ASK
As a local resident of Las Vegas, I have a few questions regarding tourism and accommodation trend in the city:

1. Which months are considered the buisest for vistors thoughout the year?
2. During which months is tourism typically slower, offering the best opportunties for cost savings?
3. To what extent does the pricing of individual neighborhoods influence Airbnb rates across the city?


## PREPARE

We will be utilzing data from data from Clark County, NV, United States, covering the period from September 2024 through September 2025. The file will be renamed for clarity and ease of reference for anyone accessing it via [Inside Airbnb](https://insideairbnb.com/get-the-data/)

- listing.csv     -> ( LV_listings.csv )
- calendar.csv.gz -> ( LV_Calendar.csv.gz )


## PROCESS, ANALYZE AND SHARE
[click here to view the full PDF report](https://github.com/Yeska702/LV_Airbnb_Analysis/blob/main/Las%20Vegas%20Airbnb%20Data%20Analysis%20final%20Version.pdf)

While the line graphs in PDF provided some insight into how average prices vary significantly across different neighborhoods, it also highlighted that the Unincorporated Area have the highest average prices. Given the complexity of creating a detailed map of Clark County in RStudio. I opted to use Tableau instead. The resulting map revealed that the Unincorporated Areas encompass a large portion of Clark County that was not fully captured in the initial dataset. As a local resident, I recognize that these Unincorporated Areas actully consist of several distinct neighborhoods, including Enterprise, Spring Valley, Paradise, Winchester, and Whitney. [Tableau Map](https://public.tableau.com/app/profile/marcos.paredes/viz/Tableau_LV_Airbnb_Analysis/Sheet1?publish=yes&showOnboarding=true)

#### Tableau Discoveries
Using the dataset provided by [Insdie Airbnb](https://insideairbnb.com/get-the-data/), I created a map in tableau. Although plotting the map was challenging due to limited data like zip-code and being my first time created map in Tableau. Luckly with the inclusion of longitude, latitude, and neighborhood information allowed for effective visualization. Upon reviewing the map and drawing from my local knowledge a clear trend emerges. The most expensive Airbnb listings are concentrated in the Paradise neighborhood. This is expected, as Paradise is located near both the Las Vegas strip and the airport, making it a highly desirable area for short-term rentals.

If you'd like to recreate the Tableau dashboard, I developed a step-by-step guide detailing the entire process [click here](https://github.com/Yeska702/LV_Airbnb_Analysis/blob/main/Tableau%20step-by-step_v4.pdf)


## ACT
After analyzing the data in RStudio and visualizing it through the Tableau dashboard, I can now share my recommendations for anyone planning a trip to Las Vegeas.

#### RECOMMENDATIONS

1. If you're planning to spend your vaction in Las Vegas during the summer, it's important to book in advance. As the summer months approach, the availability of quality Airbnb accommondations signigicantly decreases due to high demand and early bookings by other travelers.
2. If you prefer to avoid large crowds and save on accommodation costs, cosider visiting Las Vegas during the winter months. Airbnb availabilty is much highder during the this time, and the average price is nearly half of what it typically is during peak season like in the summer months.
3. Based on the data, the most expensive area to stay in Las Vegas is the uninvorporated region specifically, the Paradise neighborhood. Located between the Las Vegas Strip and Harry Reid International Airport, Paradise sits at the heart of the city, offering convenient access to both a major tourist destination and the airport. This prime location makes it an attravtive option for many visitors, though the added convenience comes at a premium cost. The analysis also revealed that neighborhoods on the outskirts of the Strip such as Boulder City, Henderson, Las Vegas and North Las Vegas tend to maintain a consisten average price throughout the year. This suggest that staying farther from major attractions and the airport can be a signigicant cost-saving decision for many travelers visiting Sin City.
