# Dataset
This is the dataset for the paper with title “*A hierarchical multi-action deep reinforcement learning method for dynamic distributed job-shop scheduling problem with job arrivals*” submitted to **IEEE TRANSACTIONS ON AUTOMATION SCIENCE AND ENGINEERING**. 

The raw data for the three scenarios from the automotive engine manufacturing company in the case study are stored in **Scenario1**, **Scenario2** and **Scenario3**, respectively. For example, the data for Scenario 1 is stored in **Scenario1** file.

For any file **Scenario[Scenario No.]**, three Excel files and two PNG files are included.
data_arrival_[number of initial jobs]_[number of arrival jobs].xlsx
data_ops_[number of initial jobs]_ [number of arrival jobs] .xlsx
data_pts_[number of initial jobs]_ [number of arrival jobs] .xlsx
Scenario[Scenario No.]_GanttChart_shopfloor_1.png
Scenario[Scenario No.]_GanttChart_shopfloor_2.png
![test](Scenario1\Scenario1_GanttChart_shopfloor_1.png)
![2](Scenario1\Scenario1_GanttChart_shopfloor_2.png)


In “data_arrival_[number of initial jobs]_[number of arrival jobs].xlsx” file, the data are stored as 

In “data_arrival_[number of initial jobs]_[number of arrival jobs].xlsx” file, the data are stored as :
|  Column 1   |  Column 2  |  Column 3  |
|  ----  | ----  |  ----  |
| Job index  | Part Type | arrival time |
		

In “data_ops_[number of initial jobs]_ [number of arrival jobs] .xlsx” file, the data are stored as 
|  Column 1   |  Column 2  |  Column 3  |   ... |
|  ----  | ----  |  ----  | ---- | 
| Job index  | the machine that the first operation of Job [Job index] is processed on | the machine that the second operation of Job [Job index] is processed on |  ... |



In "data_pts_[number of initial jobs]_ [number of arrival jobs] .xlsx" file, the data are stored as
|  Column 1   |  Column 2  |  Column 3  | ... |
|  ----  | ----  |  ----  |  ---- | 
| Job index  | the processing time of the first operation of Job [Job index] | the processing time of the second operation of Job [Job index] | ... |



File "Scenario[Scenario No.]_GanttChart_shopfloor_[Factory No.].png" presents the Gantt Chart of the scheduling scheme generated by the proposed MDRL method in factory [Factory No.].

