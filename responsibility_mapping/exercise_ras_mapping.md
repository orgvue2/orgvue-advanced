# Exercise: RAS mapping

##Situation

* An international bank is losing market share due to slow investment decisions
* Too many people are involved in signing off actions. It wants to simplify accountability and reduce cost and time to act

##Complication

* Regulatory pressure requires the bank to prove its compliance with anti-money laundering and multiple other regulations
* The bank’s board requires any changes to reduce workload but still be compliant

##Tasks
Review current responsibilities linked from Roles to Processes :
* Show any activities over-loaded with decision makers and approvers
* Show any processes not covered properly
* Show where >3 departments are involved in approving
* Identify opportunities to reduce numbers of decision makers

**Note:** Datasets to use: 11.1 Investment Roles, 11.2 Investment Processes, 11.3 Links

##How-to summary

###Set up Roles and Processes Datasets

![](4A-011.rollsprocesses.png)

1. Create a dataset in **Role**s tab based on the roles hierarchy
2. Create a dataset in **Processes** tab based on the defined processes

###Create Link Values (RAS Mapping)

![](4A-012.createlinkvalues.png)

1. Open up the Role dataset and **Link** it to the Processes dataset
2. In the linking matrix, map R, A, S against each activity

###Review current accountablities

![](4A-013.reviewaccountabilities.png)

1. Find out any activities not covered properly using **Processes dashboard**
2. Find out any activities over-loaded using **Summary Card**
3. Quantify number of people involved in each activity using **Linked expression and Chart**

##Set up Roles and Processes datasets

Create the roles and the process datasets to be linked in OrgVue using the given Excel data sheets:

1. In the Roles tab, create a new dataset using the ‘11.1 Investment Roles’ sheet. It contains role titles, cost, department and etc.
2. In the Processes tab, create a new dataset using the ‘11.2 Investment Processes’ sheet. It contains activity data in a hierarchy

![](4A-014.rolesprocessesdatasets.png)

##Link the Roles dataset to the Processes dataset through RAS


Create links using the ‘11.3 Links’ data sheet. 

1. Open up the ‘Investment Roles’ you saved in the Roles tab
2. Navigate to the Link view and click on    ![](4A-016.linkicon.png)        
3. Choose your ‘Investment Processes’ dataset from the dropdown list
4. Copy all data in the ‘11.3 Links’ sheet and paste them into the matrix – click on ‘Paste’ at top right then press Ctrl-V
5. RAS values are now mapped against each activity (process) as shown below

![](4A-015.RASlink.png)

##Review current accountabilities

###Process view

Processes Dashboard helps you instantly see activities over-loaded with approvers or not covered properly. To view Process dashboard with RAS:

1. Within the Processes dataset navigate to Dashboard View and choose ‘Processes’
2. On the Dashboard Control, set Chevron depth as 2
3. Check the ‘show links’ to display linked roles and their accountabilities (RAS)

![](4A-017.processviewaccountablities.png)

###Role view

You can view which activities each role is involved in and the type of involvement (RAS) in the context of organisational hierarchy:

1. Within the Roles dataset navigate to Tree View 
2. On the Card Panel, choose Summary card and the properties to display
3. Check the ‘Display links’ to display linked activities



