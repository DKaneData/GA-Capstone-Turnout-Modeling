# GA-Capstone-Turnout-Modeling
by David Kanevsky

The original data set (PA_VF_2024_06_04.csv) is 1.8 GB and cannot be uploaded to GitHub due to file size limitations.

## Data Sets and Data Dictionary

|Feature|Type|Description|
|---|---|---|
|UniqueID|index|A unique identifier for each voter|
|county_fips_code|object|A numeric representation of the county the voter is registered in|
|metro_type|object|Urbanicity based on the assigned census block: Urban, Suburban, Town, Rural|
|sex|object|M = Male, F = Female, U = Unknown|
|age|int|Age|
|party_registration|object|D = Democrat, R = Republican, U = Unaffiliated, I = Independent, O = Other, T = Libertarian, G = Green|
|registration_date|datetime64|The date the voter registered to vote|
|voter_status|object|A = Active, I = Inactive|
|modeled_ethnicity|object|The voter's modeled ethnicity|
|modeled_hh_income|object|The voter's modeled household_income|
|vh23g|int|2023 General Election Vote History|
|vh23p|int|2023 Primary Election Vote History|
|vh22g|int|2022 General Election Vote History|
|vh22p|int|2022 Primary Election Vote History|
|vh21g|int|2021 General Election Vote History|
|vh21p|int|2021 Primary Election Vote History|
|vh20g|int|2020 General Election Vote History|
|vh20p|int|2020 Primary Election Vote History|
|vh19g|int|2019 General Election Vote History|
|vh19p|int|2019 Primary Election Vote History|
|vh18g|int|2018 General Election Vote History|
|vh18p|int|2018 Primary Election Vote History|
|vh17g|int|2017 General Election Vote History|
|vh17p|int|2017 Primary Election Vote History|
|vh16g|int|2016 General Election Vote History|
|vh16p|int|2016 Primary Election Vote History|
|vh15g|int|2015 General Election Vote History|
|vh15p|int|2015 Primary Election Vote History|
|vh14g|int|2014 General Election Vote History|
|vh14g|int|2014 Primary Election Vote History|
|vh13g|int|2013 General Election Vote History|
|vh13p|int|2013 Primary Election Vote History|
|vh12g|int|2012 General Election Vote History|
|vh12p|int|2012 Primary Election Vote History|
|vh11g|int|2011 General Election Vote History|
|vh11p|int|2011 Primary Election Vote History|
|vh10g|int|2010 General Election Vote History|
|vh10p|int|2010 Primary Election Vote History|

The codes for each of the vote history fields are: 
0 = Did Not Vote
1 = Voted
2 = Voted by Absentee/Mail (if known)
3 = Republican Ballot (if known, open primary)
4 = Republican Absentee/Mail Ballot (if known, open primary)
5 = Democratic Ballot (if known, open primary)
6 = Democratic Absentee/Mail Ballot
7 = Voted by Early Ballot (if known)
8 = Republican Early Ballot (if known, open primary)
9 = Democratic Early Ballot (if known, open primary)