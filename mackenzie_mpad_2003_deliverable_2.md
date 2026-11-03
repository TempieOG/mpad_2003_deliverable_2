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




 
## 2. Understanding Data


### 2.1. VIMO Analysis
### 2.2. Cleaning Data
### 2.3. Analyzing Data

## 3. Delivering Data

## 4. Refrences

