# Data_Climate

## Title of the Dataset: Climate at a Glance: City Time Series

## Data Cleaning assessment
* Cleaning needs: This dataset is manually constructed by using the web scraping approach and takes me at least 5 hours so far, so no specific cleaning is needed. (I kept making sure the whole dataset looks clean during the process.) For opening this file, I only have to use excel. 
* Hand coding/Hand editing statements: I used web scraping approaches for obtaining data and manually collect/place the data into this dataset. During the process, I noticed that one of the states is missing (Hawaii), and I found the problem, which is because of the time. Hawaii was seen as a state of the US since 1959, whereas the data I collected is from 1949 to now. I can only find Hawaii's data from 1950 to now, but this will not influence the result I want. 

## Data Information

### Authorship
* NOAA National Centers for Environmental information, Climate at a Glance: City Time Series, published October 2019, retrieved on November 1, 2019 from https://www.ncdc.noaa.gov/cag/
* [Link of this reference](https://www.ncdc.noaa.gov/cag/city/time-series/USW00022521/tavg/12/12/1949-2013?base_prd=true&begbaseyear=1948&endbaseyear=2000)


### Semantic content of the file
* This dataset is designed to contains two main values: Temperature Value and Precipitation Value.

### Collection Process
* Search the data by key word "US rainfall rate data" and "US temprature" online and find the most reliable source. After gather the data, use Jupyter notebook to process the dataset. After this, do web scraping for building the dataset. (The manual process actually makes the whole dataset clean and neat.)

### Data Structure
* Data File: .xlsx
* Entities: States,	States Abbr.,	Record Dates,	Temperature Value,	Temperature Rank,	Temperature Departure from mean,	Precipitation Value,	Precipitation Rank, and	Precipitation Departure from mean.
* Dimensions of the Data: 3250 rows and 9 columns.
* Data Types: Float, charactor, timestamp, and string.

### Description 
#### Column Name:
* Data Values and Units Presented: The data values present States,	States Abbr.,	Record Dates,	Temperature Value,	Temperature Rank,	Temperature Departure from mean,	Precipitation Value,	Precipitation Rank, and	Precipitation Departure from mean of the US annual climate data.
* Number of Know Missing values within this column: No missing values are found.
* Unique Values and their Meanings: N/A
* Other Notes: N/A
