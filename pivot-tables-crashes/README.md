You must [download NYC's 2019-2021 motor vehicle collisions](downloading.md) to complete this assignment.

# Motor vehicles collisions dataset analysis

Before you start to analyze a dataset, you need to understand its content and limitations. To prepare for answering the questions below, you will want to skim through the documentation available to you. This includes:

1. The top portion of the [the Motor Vehicles Collisions dataset page](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95), which you may have also saved separately.
2. The data dictionary you [already downloaded](downloading.md#downloading-the-data-documentation)
3. The police accident report form MV104-AN [linked in the "More" description](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)

You do not need to study them seriously, but you should have a passing familiarity with what the dataset covers.

## 📝 Question Set One: Documentation

1. What NYC department provides the motor vehicle collision data? 
2. What are the conditions that are required to be met for a motor vehicle collision to be included in this dataset?
3. What are some of the limitations of this data, according to the city’s description? 
4. What might be an issue with comparing 2013 traffic data to 2017 motor vehicle collision data?
5. What are the two types of locations a pedestrian can be marked as present at? (You can copy and paste this from the documentation if you find it there)
6. According to the documentation, what are the eight types of vehicles that could be included in the columns that refer to "vehicle type?" (You can copy and paste this from the documentation if you find it there)

# Data analysis

Now that we have a decent grasp on the sourcing and limitations of the data, it's time to analyze the data itself.

## 📝 Question Set Two: Examining, filtering and sorting

1. How many rows are there in the data? *Tip: if there are 1,048,576, then you downloaded the full dataset instead of the filtered version. [Details on row limits here](../row-limits/)*
2. Do you notice any potential limitations of the data just by glancing through it? What are they? This only needs to be a cursory answer at this point, and if nothing strikes you as a limitation, no problem.
3. What is the most number of people injured in one crash? Where and when did this incident happen? *Requires: sorting*
4. Does "number of persons killed" include pedestrians and cyclists, or just motorists? *Requires: filtering*
5. How far into 2019 was it before a cyclist was killed? *Requires: filtering, sorting*

## 📝 Question Set Three: Pivot tables

For Values, we will use the count of the `CRASH_DATE` column. According to the dataset...

1. What borough has the most crashes?
2. For each borough, list the number of people killed in motor vehicle crashes during this timeframe.
3. What percent of vehicle-related deaths are pedestrians? *It's easiest to calculate this yourself from the raw numbers*
4. Do the vehicle types in the actual dataset match the documentation? If not, list a few that are missing from the documentation.
5. What additional Excel skills would be useful for analyzing this dataset? What other questions could you ask if you had more advanced abilities?
6. How would you use this to create an accountability story? What additional information would you need to combine with what you have learned from this to develop an accountability story? Would you use additional data, and if so, what would that ideally be? You do not need to know if this data exists. 
