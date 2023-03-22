# Data Cleaning with Power Query

##Introduction
In this project, we will be working with a data set containing statistics for all the players in the FIFA 21 video game. FIFA 21 is a popular football simulation game that allows players to build and manage their own teams. The data set we will be using includes various attributes for each player, such as their age, position, nationality, club, and skill ratings.

To prepare the data for analysis, we will be using Power Query, a data transformation and analysis tool in Excel. We will be removing any duplicates, filling in missing values, renaming columns, and reformatting data using Power Query. By using Power Query for data cleaning, we can ensure that our analysis is based on accurate and consistent data.

The goal of this project is to clean and transform the raw data using Power Query, and to perform additional analysis to gain insights into the player statistics.

In the following sections, we will document the steps we took to clean the data using Power Query and perform additional analysis. We will also provide instructions on how to reproduce our analysis so that others can benefit from our work.

## Data Transformation
As I have stated earlier I used the Microsoft power query editor to complete the cleaning task, the raw data was messy and it contained a lot of discrepancies.

## Trim White Spaces

The first transformation made was to trim white spaces in the column "Club"

 |Before Trim                 | After Trim                          |                                 
  ---------------------------:|:-----------------------------------
  ![](https://github.com/DiegoPureco/Data-cleaning-with-Power-Query/blob/main/Capturas%20DataCleaning/Recortar_espacios_blancos1.PNG)| ![](https://github.com/DiegoPureco/Data-cleaning-with-Power-Query/blob/main/Capturas%20DataCleaning/Recortar_espacios_blancos2.PNG)                 

## OVA and POT
The OVA(Overall Analysis Rating), and POT(Potential Rating) columns contained numeric values and had a wrong data type. To transform these columns I divided each colunmn by 100 and changed the data type to percentage.

|Before|After|
------:|------
![](https://github.com/DiegoPureco/Data-cleaning-with-Power-Query/blob/main/Capturas%20DataCleaning/Ova%20y%20pot1.PNG)| ![](https://github.com/DiegoPureco/Data-cleaning-with-Power-Query/blob/main/Capturas%20DataCleaning/Ova%20y%20pot2.PNG)

