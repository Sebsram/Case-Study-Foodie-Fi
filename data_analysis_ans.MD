**1. How many customers has Foodie-Fi ever had?**

![a1](https://user-images.githubusercontent.com/130475600/233702942-3c6827f4-5886-44f5-8132-3223db942b99.PNG)

| total_costumers |
| --------------- |
| 1000            |

**2. What is the monthly distribution of trial plan start_date values for our dataset - use the start of the month as the group by value**

![a2](https://user-images.githubusercontent.com/130475600/233704948-1add19a7-c26d-489c-83e2-b0562f228608.PNG)

| m_name    | trial_subs |
| --------- | ---------- |
| March     | 94         |
| July      | 89         |
| May       | 88         |
| January   | 88         |
| August    | 88         |
| September | 87         |
| December  | 84         |
| April     | 81         |
| June      | 79         |
| October   | 79         |
| November  | 75         |
| February  | 68         |

**3. What plan start_date values occur after the year 2020 for our dataset? Show the breakdown by count of events for each plan_name**

![a3](https://user-images.githubusercontent.com/130475600/233706241-1d7aa62f-c33a-45b2-8b16-739b1e850dbf.PNG)

| plan_id | plan_name     | events |
| ------- | ------------- | ------ |
| 1       | basic monthly | 8      |
| 2       | pro monthly   | 60     |
| 3       | pro annual    | 63     |
| 4       | churn         | 71     |

**4. What is the customer count and percentage of customers who have churned rounded to 1 decimal place?**

![a4](https://user-images.githubusercontent.com/130475600/233708753-d79ed974-115e-451c-8694-6a391f8f8362.PNG)

| churn_count | percentage |
| ----------- | ---------- |
| 307         | 30.7       |

**5. How many customers have churned straight after their initial free trial - what percentage is this rounded to the nearest whole number?**

![a5](https://user-images.githubusercontent.com/130475600/233840310-70bbfd0f-318e-4e48-a9bb-6808fd230925.PNG)

| chunk_perc | percentage |
| ---------- | ---------- |
| 92         | 9          |

**6. What is the number and percentage of customer plans after their initial free trial?**

![a6](https://user-images.githubusercontent.com/130475600/233841797-f31fe9ab-bcad-4aa8-aef6-b23d7424324b.PNG)

| next_plan | conversions | percentage |
| --------- | ----------- | ---------- |
| 1         | 546         | 54.6       |
| 2         | 325         | 32.5       |
| 3         | 37          | 3.7        |
| 4         | 92          | 9.2        |

**7. What is the customer count and percentage breakdown of all 5 plan_name values at 2020-12-31?**

![a7](https://user-images.githubusercontent.com/130475600/234033763-30586838-4497-4dac-b4ba-c7b6075007f8.PNG)

**8. How many customers have upgraded to an annual plan in 2020?**

![a8](https://user-images.githubusercontent.com/130475600/233850347-e65835d7-fc23-402f-b8d4-b7daf97c5b1d.PNG)

| unique_customers |
| ---------------- |
| 195              |

**9. How many days on average does it take for a customer to an annual plan from the day they join Foodie-Fi?** 

![a9](https://user-images.githubusercontent.com/130475600/233851036-dda9829f-6bc2-48b9-b0e3-3805f6c087ea.PNG)

| avg_days |
| -------- |
| 105      |

**10. Can you further breakdown this average value into 30 day periods (i.e. 0-30 days, 31-60 days etc)**

![a10](https://user-images.githubusercontent.com/130475600/234033443-f5f83e6c-506d-4be8-8f67-518633dcebd5.PNG)

| grps | Customer |
| -------- | -------- |
| 0 - 30 days      | 48      |
| 30 - 60 days      | 25      |
| 60 - 90 days      | 33      |
| 90 - 120 days      | 35      |
| 120 - 150 days      | 43      |
| 150 - 180 days      | 35      |
| 180 - 210 days      | 27      |
| 210 - 240 days      | 4      |
| 240 - 270 days      | 5     |
| 270 - 300 days      | 1     |
| 300 - 330 days      | 1      |
| 330 - 360 days    | 1      |
