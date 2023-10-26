# Week 9: Cloud-Hosted Notebook Data Manipulation
## Katelyn Hucker (kh509)

I completed the ingest and EDA stages in a Google Colab Notebook. I uploaded the jupytr notebook file to this repo. You can also find the cloud-hosted notebook at this github gist link. The notebook has headings and subheadings matching the requirements below so please take advantage of the easy access. I have also included screenshots with some of the requirements below. 

[View My Gist]([https://gist.github.com/username/gistID](https://gist.github.com/katelyn-hucker/7b9ad413b72e37174db966409d46e061))

## About my dataset

I got my dataset from two datasources:
- [Datasource 1](https://github.com/oganm/dnddata)
- [Datasource 2](https://www.kaggle.com/datasets/andrewabeles/dnd-stats)

The two datasets are about Dungeons and Dragons details characters like physical characteristics and player options. I wanted to see if there was any relationship between D&D classes (Wizard, Fighter,etc) with the statistics characters carry like strength or intelligence. 

## Requirements
The project requred the following requrements: 

- **Import a sample dataset into the cloud notebook (Ingest stage)**

I imported datasource 1, a tsv using pandas. 

- **Perform basic data inspection such as checking the number of rows and columns, data types, summary statistics etc (EDA stage).**

I looked the basic charactersitics of Datasource 1. I noticed there was a lot of cleaning with observation inputs, i.e. people input incorrect options for categories. 

![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/0203de66-b9e8-446f-af28-2e2d95ed8e2e)

- **Filter the data based on specific criteria and create a new filtered dataset (EDA)**

I filtered many things but below is an image of my dropping any observations with NA values and properly naming the alignment column.

![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/b5f6fcb4-1708-4135-b178-2f093e8d37b9)

- **Group the data by one or more columns and aggregate metrics like mean, max etc (EDA)**

I grouped the data by levels (1,5,10,20) and all classes. Then calculated the mean for all numerical data. We can see that some classes give characters higher traits and as we go up in level the  traits get better. 

![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/7976165d-a73c-4943-936a-6ba2ba07a991)

- **Join the main dataset with another supplementary dataset (EDA)**

I found and cleaned another dataset so that it could be merged with the dataset. See the notebook for this process. 

- **Create various data visualizations like histograms, scatter plots, box plots etc (EDA)**

I created 6 plots. Each a plot of the different classes and their numerical characteristic ranges in the form of boxplots. This is only at character level 1. 

##### Strength
![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/ca659bd6-ddd3-4a2c-9ad5-4fe3ae9602ac)

##### Dexterity
![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/078ff6af-5b40-432a-95f6-b04b71de9ffa)

##### Constitution
![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/1f33a1e3-ba7d-466d-9936-31bdc57e0d67)

##### Intelligence
![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/23770468-942a-472b-acd2-68e2a01bca35)

##### Wisdom
![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/d3552cec-e1af-484c-b148-37236dc9d6a8)

##### Charisma
![image](https://github.com/nogibjj/kh509_miniproject9/assets/143521756/4e961531-6adc-456c-b123-09f1a117ce52)


