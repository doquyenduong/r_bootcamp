# R-bootcamp 

This is a pair project for the module "R-bootcamp" at HSLU. It's my first project ever with R. 

## ASSIGNMENT REQUIREMENT
- Find a use case that comes with some data
- The choice of the case is completely up to you
- The dataset must contain at least a few hundred observations and a dozen variables
- among the variables there must be numeric and categorical ones
- the dataset should also contain variables that are dates or geographic locations (both is even better)
- A chapter of your choice: we want you to use a package that was not mentioned in the course and perform a task that was not directly discussed in the course. Be creative!
- Fit model(s):Note that the focus of this course is not modelling. Therefore, do not invest time in finding fancy models. A very simple model will do it.
- Dynamic documents and reproducibility: We want you to create the pdf/html document with Rmarkdown. Make sure that your analysis is fully
reproducible and comprehensible for anyone reading it.
- Comments: The analysis needs to be commented. Keep in mind that you should make up a story to tell to a client. So, we want you to comment what you are doing and why you are doing things.

## GENERAL INFORMATION & MOTIVATION ON THE TOPIC 

1. Title of Dataset: Missing Migrant Project 
2. Motivation

Since 2014, more than 35,000 lives have been lost during migration, with many tragedies along various international migration routes. This fatal fact initiated the International Organization for Migration (IOM) to create Missing Migrant Project (MMP) with funding from governments such as Switzerland and the United Kingdom. Today, the project has evolved to a crucial and far-reaching center of data and information for policymakers, researchers, and the public.

The MMP records deaths and disappearances of migrants, covering asylum-seekers and refugees. The data from the MMP are from a variety of sources, including national authorities, NGOs, media reports, and interviews with surviving migrants. For more information about MMP, please visit: https://gmdac.iom.int/missing-migrants-project-0

Inspired by the MMP, the analysis report gathers the dead and missing migrant data from IOM and aims to gain knowledge and grasp of incidents and shed some light on the deaths of thousands of migrants fleeing from countries engulfed in warfare and conflicts.

3. Date of data download: 05-09-2021 

4. Information about funding sources that supported the collection of the data: International Organization for Migrant (IOM) MissingMigrants@iom.int 

## FOLDER OVERVIEW 

1. dataset: dataset/MissingMigrants-Global-2021-09-05T18-37-06.csv 
The original dataset
	
2. List_of_functions: 
The html list of functions used in the report
	
3. Rmarkdown files: 
- Exploratory_Data_Analysis_Draft.Rmd (The draft with EDA)
- Final_Report_Missing_Migrant_Project.Rmd (The final report)
	
4. Output final report html: Final_Report_Missing_Migrant_Project.html
	
5. Project file: R-bootcamp groupwork in pair.Rproj 
	
6. readme.txt


## DATA
- Number of variables: 20 
- Number of cases/rows: 8810 

## SOME VISUALIZATIONS FROM THE REPORT
 Incidents by regions
![image](https://user-images.githubusercontent.com/83208743/171120890-719ab86d-f622-425d-b550-6b61b4fd924e.png)
![image](https://user-images.githubusercontent.com/83208743/171120956-f3b81200-4f4e-4a3b-b0b4-434943f128e4.png)
![image](https://user-images.githubusercontent.com/83208743/171120983-5c7b4cbc-f712-4387-b442-5fb007ac8e44.png)

Incidents by migration routes
![image](https://user-images.githubusercontent.com/83208743/171121265-32b44599-84db-4d36-bda0-45abb47d42c1.png)

Incidents by months
![image](https://user-images.githubusercontent.com/83208743/171121295-afafc5a4-8695-4391-899a-14de6da30c3e.png)

Male, female, children
![image](https://user-images.githubusercontent.com/83208743/171121375-b89a5354-19eb-40c9-bc59-997718862725.png)

Causes of death
![image](https://user-images.githubusercontent.com/83208743/171121440-e63fe72b-2bd4-4294-95dc-822c6b58034e.png)




