# KPI-Dashboard

[Official Dashboard](https://public.tableau.com/app/profile/anthony.carpinello/viz/KPIDashboard_17250498862910/Dashboard1)

Imagine the manager of the IT help-desk department came to you and requested a dashboard that would show how his employees have been doing in the most recent month. That is exactly what I did for this project. Here I will walk you through the steps I took to create this dashboard and if you'd like to see the finished Dashboard on Tableau Public, click [here](https://public.tableau.com/app/profile/anthony.carpinello/viz/KPIDashboard_17250498862910/Dashboard1)!!




### Call Volume During Week:
<img width="887" alt="Call Volume during week" src="https://github.com/user-attachments/assets/3658b77a-1c75-4730-8e62-6b80f37b41f0">

This bar chart is showing the average amount of calls per day of the week. Notice in the filters section it says, "Most Recent Month: True". This limits my charts to only collecting data from the most recent month and you will see this filter is applied to all of my sheets except one. To make this filter, I used the calculated field shown below.

<img width="481" alt="Most Recent Month" src="https://github.com/user-attachments/assets/26303102-5be6-46ff-96aa-dd77832942c5">





### Calls Per Day:
<img width="465" alt="Calls Per Day" src="https://github.com/user-attachments/assets/c7e6ee2e-4a84-400f-8c6e-9255e4d76650">

In this image, the 27 is the number of calls that occurred in the most recent day and the 3.896 is the average length in minutes of each call. Rather than month, for this I used a filter to only collect data on the most recent day and used the very similar calculated field shown below to make this possible.

<img width="481" alt="Most Recent Day" src="https://github.com/user-attachments/assets/8431ff61-7ae0-48b5-8ba4-6a1f3887f036">





### Satisfaction Rate:
<img width="1013" alt="Satisfaction Rating" src="https://github.com/user-attachments/assets/88354b2f-2d54-41bc-bce0-969b0fbf5953">
Here we see the average satisfaction ratings, 5 being the highest rating and 1 being the lowest. The additional "Satisfaction Rating" filter was just used to remove nulls.



### Resolution Rate for Current Month:
<img width="440" alt="Resolution Rate for Current Month" src="https://github.com/user-attachments/assets/68665c8e-3811-44d8-aee7-72a832946a39">

Here, the 70.47% is the overall resolution rate for all the employees. To get this number I used a calculated field that divided the total number of resolved calls by the total number of calls.

<img width="554" alt="Screenshot 2024-09-01 at 10 53 14 AM" src="https://github.com/user-attachments/assets/44be98f6-40cb-4d48-b4c9-9d18301010a8">

### Resolution Rates for Each Employee:
<img width="457" alt="Resolution Rate" src="https://github.com/user-attachments/assets/e85f22bf-265d-4ee9-8c97-8088b430bf90">

In the table above, you can see each employee’s resolution rates. The ones highlighted in blue are the lower performing employees. The same calculated field used to find the overall resolution rate was also used here. Except its now broken up by employee. 



### Resolved Calls for Each Employee:
<img width="466" alt="Resolved Calls" src="https://github.com/user-attachments/assets/0be0a9cc-60c2-4ca8-9139-ff461597bcb0">

In this table, you can see the total number of resolved calls by each employee. The "Resolved: Y" filter was used to make sure the table didn’t include unresolved calls.



### Speed of Answer for Each Employee:
<img width="466" alt="Speed of Answer" src="https://github.com/user-attachments/assets/78806c60-b71f-40b9-be98-0e0574ae206f">

Finally, for each employee, we have the median of how long it took them to pick up the phone.















