# Process mapping (Links - numbers)

##Situation

* The Marketing department has 12 people with £702K total payroll cost

* The CMO is looking for more efficient marketing processes, eliminating or simplifying steps, and achieving cost savings

##Complication

* Interviews show lack of clarity on who is doing what and how much time and cost each activity currently takes
* Unions are asking which areas and how many people will be affected by change

##Tasks

* Identify actual % time spent and cost for each activity, plan actions to increase efficiency, and see the cost and FTE impacts:
  *  Map resources (time spent) against each activity (Links)
  * View process dashboard and activity cost (Dashboard, Scaled card)
  * Determine appropriate actions for each activity (Look up)
  * Measure the impacts by process, role and area (Chart, Dashboard)

**Note:** Datasets to use: 12.1 Marketing Roles, 12.2 Marketing Processes, 12.3 Links

##How-to Summary Part 1: Mapping and Analysing Current Activities

**Set up Datasets and Links**

![](5A-001.setupdatasets.png)

1. Set up a Roles dataset and a Process dataset 
2. **Link** Roles dataset to Process dataset through % time spend (activity data)

**Show what people can do**

![](5A-002.showpeople.png)
1. See how people’s time is allocated between activities in **Org chart**
2. See how the work is done from **Process dashboard**

**Calculate and analyse Activity Cost

![](5A-003.calculateactivitycost.png)
1. Calculate **cost of each activity** based on actual FTEs involved and payroll cost
2. See which activities use most resources using **Chart**
3. See activity cost in activity tree **roll-up Scaled card**

###Set up Roles and Processes datasets

Prepare the roles and the process datasets in OrgVue using the given Excel data sheets:

1. In the Roles tab, create a new dataset using the ‘12.1 Marketing Roles’ sheet. It contains role titles, cost, department and etc.
2. In the Processes tab, create a new dataset using the ‘12.2 Marketing Processes’ sheet. It contains activity data in a hierarchy

![](5A-004.setuprolesprocesses.png)

###Link Roles dataset to Processes dataset through time spend

After setting up Roles and Processes datasets, create link values using the ‘12.3 Links’ sheet. 

1. Open up the Roles dataset ‘Marketing Roles’ you have saved in the Roles tab
2. Navigate to the Link view and click on  ![](5A-005.linkdropdown.png)          
3. Choose your Marketing Process dataset from the dropdown list
4. Copy the id to id link values from the ‘12.3 Links’ sheet and paste them into the matrix – click on ‘Paste’ at top right then press Ctrl-V

![](5A-006.linkrolestoprocesses.png)

**Note:** In practice, IAA Survey can be used to crowdsource activity data (% time spent on each activity) and populate links automatically. 

###View Org Chart including activities

See what each role does and how much time that they spend doing it:

1. Switch to Tree view within the Roles dataset and configure Summary card
2. Check ‘Display links’ to view linked activities with time spend

![](5A-007.vieworgchart.png)

###View actual FTEs on Process dashboard

To view process breakdowns with linked roles and % time spent:

1. Open the Processes dataset linked from the Roles dataset
2. Navigate to Dashboard view and choose Processes dashboard
3. Set Chevron depth as 2
4. Check ‘show links’ to display linked roles with % time spent

 ![](5A-008.viewfte.png)
###Calculate total time spent on each activity

  In the Process dataset create a new property ‘Total FTE’ to calculate actual FTEs linked to each activity using the syntax: ```node.links.value.sum``` 
  – this will calculate total number of FTEs working on each activity based on the link values (% time spent).
  
  ![](5A-009.calculatetotaltime.png)
  
###Calculate activity cost 

Converting time to cost can deliver insights on aggregated activity costs. Within the Processes dataset create a new property **‘Activity Cost’** and populate it with calculated value based on linked FTE values and the associated payroll cost using the syntax:
```node.links.math("value*to.payrollcost").sum```
– this will calculate cost of activity based on the linked % time and the associated payroll cost from Roles datasets.





