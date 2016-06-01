# OrgVue v2.20 scaling guidelines

|  | Working upper limit|Notes|
| -- | -- | -- |
| Dataset size | 5 million cells e.g. 100,000 nodes(people), 50 properties(columns)| For organisational analytics purposes, datasets are usually smaller than this. Analyses are usually carried out on subsections of the main organisation of 3,000 – 30,000 people or using consolidated posts, each one containing many FTE|
| Number of Links | 50,000 links e.g. 10,000 people linked to any 5 activities out of 10,000 activities| Most analytics are carried out between roles and a limited set of activities – so 1,000 roles, for example, linked to 5-20 activities each, which is well within the 50,000 limit|
| PPT export | 10,000 objects |Above 10,000 nodes, it is recommended that export is made to pdf (for high resolution printing) or png (for an image on e.g. slides)|
| Number of Photos |200 when photo size is 10KB|When the photo size is larger than 10k, dataset performance is slow|

**NOTE:** Maximum number of datasets is based on licence level (100 for basic, 250 for advanced, 500 for professional).
