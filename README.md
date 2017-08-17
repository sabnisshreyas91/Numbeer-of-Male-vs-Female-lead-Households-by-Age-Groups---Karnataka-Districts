# Number-of-Male-vs-Female-lead-Households-by-Age-Groups---Karnataka-Districts
Uses a public dataset - DDW-HH06-2900-2011.csv available at data.gov.in to explore and visualize how many households in karnataka are lead by Men vs Women
Note that the dataset metadata is changed slightly before importing into dataframe for ease of data analysis.

ROW INFORMATION:


The modified dataset is as below:

![modified_dataset](images/modified_dataset.PNG)

from the screenshot, it is clear that the dataset has a hierarchical structure. The highest level being (KARNATAKA--Total--All Ages).

This level can be further split as (KARNATAKA--Rural--All Ages) and (KARNATAKA--Urban--All Ages)

![levels](images/levels.PNG)

Further,the (KARNATAKA-Total-All Ages),(KARNATAKA-Rural-All Ages) and (KARNATAKA-Urban-All Ages) levels can be split on age groups as below:

![age_levels](images/levels_2.PNG)

There are 3 levels below and including 'Total' (Total/Rural/Urban) and 10 levels below and including 'All Ages'. Therefore each Area should be 30 rows. Further there are 31 areas including and below 'KARNATAKA' : 

![areas](images/areas_list.PNG)

District Codes uniquely identify Areas eg. District Code 0 identifies - 'State - KARNATAKA'


COLUMN INFORMATION:

The full list of all columns is as below:

![full_col_list](images/full_column_list.PNG)

The columns as well have levels of aggregtion summaried as below:

![col_hier](images/column_hierarchy.PNG)








