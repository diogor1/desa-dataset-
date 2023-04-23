# desa-dataset-
the minority residents of Scotland, a hypothetical data extraction. T
## description
Desa is a dataset of black minority and Asian residents of Scotland. It shows the resident statuses, religion, country, gender, age ethnicity, residence area, jobs, employment status etc. we will query the various variables from the data, manoeuvre and structure it in the best possible ways, we will also join other tables and query data from them simultaneously.
#### The select function. We read the data... 
#### use tutsql
#### select * from desa

![Screenshot (8)](https://user-images.githubusercontent.com/30722736/233784537-ac6ccd26-86cb-428d-a1b0-0f8aabe38ac0.png)

##### use tutsql
##### select * from desa order by 8, 9

![Screenshot (10)](https://user-images.githubusercontent.com/30722736/233785625-7af80791-c3eb-4242-8610-c27e6afaa13b.png)
Here, we order by a specific column, this uses the column as key to connect oither columns.

##### Select * from desa where City = 'Dundee'.
![Screenshot (12)](https://user-images.githubusercontent.com/30722736/233787225-f1c0245f-5c05-4795-9c73-64d8d81c06b4.png)
Here, we query only those residents who live in Dundee...

##### Select * from desa where City = 'Dundee'AND Religion = 'Muslim'

![Screenshot (14)](https://user-images.githubusercontent.com/30722736/233787862-62cc431b-6b7d-4c21-bf49-34bf5fdf5678.png)
the and' function narrows down the variables 

##### Select * from desa 
##### where Useful_Feedback > 3 
##### order by Interview_Feedback Desc

![Screenshot (16)](https://user-images.githubusercontent.com/30722736/233809000-7c1390f7-753d-4e53-ad4e-aa064d7b847f.png)
we applied two concepts here; 1. the variable: useful feedback start from 3 and above, also the orderby (sorting) was in a descending order.

##### Select * from desa 
##### where Country like '%a' or Religion like '%u'
![Screenshot (19)](https://user-images.githubusercontent.com/30722736/233823928-09f28d44-a891-4e6c-8254-6a7b35af6b49.png)


##### Select * from desa 
#### where Country like '%a' and Religion like '%u'
![Screenshot (20)](https://user-images.githubusercontent.com/30722736/233824040-b865ca68-98fe-4c05-80e5-712997caafbe.png)
Here, we queriesd the countries and religions that end with a or u, eitherways, and also the countries and religions that end with both a and u.

##### select * from desa
##### where City in ('Glasgow', 'Edinburgh')
##### order by country





