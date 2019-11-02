# Data_Climate

## Title of the Dataset: Climate at a Glance: City Time Series

## Data Cleaning assessment
* Cleaning needs: This dataset is manually constructed by using the web scraping approache, so no specific cleaning is needed. (I kept making sure the whole dataset looks clean during the process.)
* Hand coding/Hand editing statements: I used web scraping approaches for obtaining data and manually collect/place the data into this dataset. During the process, I noticed that one of the states is missing (Hawaii), and I found the problem, which is because of the time. Hawaii was seen as a state of the US since 1959, whereas the data I collected is from 1949 to now. I can only find Hawaii's data from 1950 to now, but this will not influence the result I want. 

## Data Information

### Authorship
* NOAA National Centers for Environmental information, Climate at a Glance: City Time Series, published October 2019, retrieved on November 1, 2019 from https://www.ncdc.noaa.gov/cag/
* [Link of this reference](https://www.ncdc.noaa.gov/cag/city/time-series/USW00022521/tavg/12/12/1949-2013?base_prd=true&begbaseyear=1948&endbaseyear=2000)


### Semantic content of the file
* This dataset is designed to describe the US geography information. 

### Collection Process
* Search the data by key word "US geography data" online and find the most reliable source. After gather the data, use Jupyter notebook to process the dataset.

### Data Structure
* Data File: .shape
* Entities: Id, Contour, Shape_Leng, and geometry.
* Dimensions of the Data: 369202 rows and 4 columns.
* Data Types: Integer, float, and string.

### Description 
#### Column Name:
* Data Values and Units Presented: The data values present Id, Contour, Shape_Leng, and geometry of the US geographical data.
* Number of Know Missing values within this column: No missing values are found.
* Unique Values and their Meanings: N/A
* Other Notes: N/A
