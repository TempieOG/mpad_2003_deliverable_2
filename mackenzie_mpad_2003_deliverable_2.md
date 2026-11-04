**November 1 2026**<br>
**MPAD2003 - Data Storytelling**<br>
**Lincoln Mackenzie**<br>
**Presented to Jean-Sébastien Marier**<br>

# Deliverable 2: Exploratory Data Analysis (EDA)

## Foreword
A pothole, Garbage still on your driveway, fallen tree, these are things that can promp Ottawa residents to contact 311. Individual reports may seem normal but when grouped together they can show different patterns that reval how resident use these municipal services. Building on assignemnt 1 (my proposal) i want to compare the mix of service types across ottawa wards, not just by ranking wards by number of call but seeing why residents are calling in each of these wards

## 1. Getting Data
I selected the city of ottwawas current year service requests data set which record all calls for municipoal services that require action from someone in the city.   The city gets these calls through its 311 contact number, service centres, email and the online self portal (City Of Ottawa, 2026). My question is: Do certain kind of 311 requests accpimt for unusually big shares of 311 activity in certain wards. This is a question about reported service needs, not a direct scale looking at the quality of each neibourhood.

To import the data, i downlaoded the csv  from the data set online. In google sheets i made a blank spreadsheet. Then i found the data set and in google sheets went file --> import --> upload, once imported into a new sheet and checked that the first row contained seperate field names. I retained a untoched tab called Raw_Import and made a copy called Working_clean before i edited anything 

Public Spreadsheet: https://docs.google.com/spreadsheets/d/1uR1RahZ7FCiUXT10IK6zn1jHEC5j_rE8KFFhthIxDsU/edit?usp=sharing

The imported sheet contains 5001 datta rows and 11 colums as of october 28th 2026, there are a ton of mistake throughout the data with missing values, wards, addresses, times. But we cleaned all of this up in the google sheet

The ward field is a nominial caregorical variable, a ward number is an identifier not a quality that has any meaning worth averageing. Type is also a nominal value by serpeating service categories without ranking them. Opened Date is a date/time variable that allows daily or monthly comparisions of the data. And a fourth useful field would be the service request ID, this connectes a number to a recortd and can help check for duplicates. Stats Canada (2021) emphasizes identifying variable types


![Ottawa 311 dataset after import](311_after_import.png)

*Figure 1: Ottawa 311 dataset before cleaning, showing the original column headings and service requests.*





 
## 2. Understanding Data


### 2.1. VIMO Analysis
Before cleaning and analyzing the data set i got from 311 ottawa, i needed to look ath the quality of the information that i was given. Is it comeplete? Are there errors? Is there anything i can manually fix?
I Used the VIMO method which stands for, valid, invalid, missing, and outlier values. This assisted me in understanding how reliable the data was and what problem could affect my analysis of the data.

Valid Values: A ton of the records seemed to have contained valid information that will be usefull and helpful. For example, the type column had categories such as "Water and Enviroment" while the status column contained data such as "resolved". These are useful as it shows what has been requested in ottawa, what is still being worked on and what the city has already completed. 

Invalid Values: I needed to check for info that might have been entred incorrect. This could include things such as inconsistant categories, incorrect dates and any requests that got submitted twice (either same ID or same address)

Missing Values: One of the largest issues that i ran into was missing info. Some records contained \N instead of giving an actual value. Example: Certain requests had no description, address or in some cases even a ward. This is a huge deal beacuse missing ward information prevents not only me  from identifying where  theos requests came from but it will also make it hard for the city of ottawa to fix these problems if they dont even know where the problem is. 

Outliers: I Also wanted to look into whether certain wards reported weirdly high numbers of certain requests. Although an unusually high number dosent just mean that there is an error. It could mean that there is sensitive or private information, but it could also be a real pattern worth looking into. I will look furtur into this using my pivot table

### 2.2. Cleaning Data
### 2.3. Analyzing Data

## 3. Delivering Data

## 4. Refrences

