# Exercise: Payment Review

**Situation**

* An organisation employs people across several European countries
* Current payroll records show what employees are paid in their local currencies

**Complication**

* The company wants to move activity to the best locations in terms of cost
* To focus the discussion, it wants to estimate the overall salary benefit and the benefit per department and per role from a move

**Tasks**

Identify the gap between actual and target salaries per department:

* Convert current local salary to GBP by looking up exchange rate (Lookups)
* Look up target salary for each grade (Lookups)
* Calculate the gap between current salary and target salary (Expressions)
* Visualise the salary difference (Chart, Color by)

**Note:** Datasets to use: 8.1 Payment review, 8.2 Country (lookup), 8.3 Grade (lookup)

##How-to summary

1.
**Get actual salary in GBP**
  
  * **Look up** exchange rate for each country from Country dataset  
  * Create a property for salary in GBP using ** *Expressions* ** 
  
2.
**Get target salary by grade**

 * **Look up** target salary for each employee based on grade

3.
**Capture the difference**

* Create a property fill in the gap between actual and target salary using ** *Expressions* **

4.**Visualise the gaps**

* See the gap between the two in the Tree using **Color by**
* See the gap by department / depth using **Chart**
  
##Get exercise data into OrgVue 

1. Open the Excel workbook for OrgVue Advaned Training

2. Find 3 sheets for this chapter:

  * 8.1 Payment review,
  * 8.2 Country (lookup)
  * 8.3 Grade (lookup)

3.  In OrgVue, create a dataset named ‘Payment Review – [your name]’ in the People tab using ‘8.1 Payment review’ data sheet; this dataset will be the main dataset
Navigate to the Lookups tab, create 2 lookup datasets using ‘8.2 Country (lookup)’ and ‘8.3 Grade (lookup)’








