# Branching Exercise: Re-organisation by planning group

###Situation
* An organisation with 1,505 employees in 13 departments across 13 locations
* Planning to classify departments into planning groups and take necessary actions for operational efficiency

###Complication
* The impact of changes need to be measured quickly from multiple angles

###Tasks
* Model the To-Be organisation and capture impact of changes using Branching method
* Assign each of the departments to one of 6 planning groups and determine suitable actions for each area of business
  * Planning Groups: Back Office, Distribution, P&P, R&D, Sales and Executive
  * Actions: outsourced, redundant, relocate, reassigned, new, unchanged 

**Note:** Datasets to use: 1505 Dataset (clean)
![](3A-020.visualiseimpact.png)
## How-to summary

###Set-up a Branch

![](3A-018.setupbranch.png)

1. Create a **branch** of trunk (baseline) dataset(Save as -> check ‘create branch’)
2. The branched dataset will appear in Roles tab: Branches 
3. In the branched dataset, create required new properties, e.g. planning group, action

###Model the Scenario

![](3A-019.modelscenario.png)

1. Open up the branch and go to **Pivot view**
2. Assign each department to a planning group using **‘Paint with Data’**
3. Review each planning group and determine suitable actions – **‘Paint with Data’**


###Visualise the Impact

1. View the areas affected by changes using various visualisations in **Tree view**
2. Use **Changes Report  Dashboard** to see the differences against the baseline (original scenario)

##Get exercise data into OrgVue 

1. Open the Excel workbook for OrgVue Advaned Training
2. Find a data sheet for this chapter:
     1505 (clean)
3. In OrgVue, create a dataset named ‘Delta Roles – [your name]’ in the Roles tab using the ‘1505 (clean)’ data sheet; this will be your baseline dataset

##Set up a branch 

###Create a branched dataset

1. Open a baseline dataset and click on the ‘Save-As’ to create a branched dataset from it; this will prompt ‘Save as…’ dialoge
2. Give a name to the branch as ‘Delta Branch – [your name]’ and make sure to check ‘Create branch’ option
![](3A-021.createbrancheddataset.png)
3. The branched dataset is stored in the ‘Branches’ section along with other branches

![](3A-022.createbrancheddataset2.png)




