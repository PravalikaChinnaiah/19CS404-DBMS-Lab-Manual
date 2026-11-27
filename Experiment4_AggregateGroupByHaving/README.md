# Experiment 4: Aggregate Functions, Group By and Having Clause

## AIM
To study and implement aggregate functions, GROUP BY, and HAVING clause with suitable examples.

## THEORY

### Aggregate Functions
These perform calculations on a set of values and return a single value.

- **MIN()** – Smallest value  
- **MAX()** – Largest value  
- **COUNT()** – Number of rows  
- **SUM()** – Total of values  
- **AVG()** – Average of values

**Syntax:**
```sql
SELECT AGG_FUNC(column_name) FROM table_name WHERE condition;
```
### GROUP BY
Groups records with the same values in specified columns.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name;
```
### HAVING
Filters the grouped records based on aggregate conditions.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name
HAVING condition;
```

**Question 1**
--
<img width="1187" height="565" alt="image" src="https://github.com/user-attachments/assets/849d52ca-eb62-403b-94ba-258412753517" />


**Output:**

<img width="918" height="546" alt="image" src="https://github.com/user-attachments/assets/8db37e30-99a5-4682-860e-dbc764440122" />


**Question 2**
<img width="1223" height="712" alt="image" src="https://github.com/user-attachments/assets/5501eee4-3109-4733-97bf-cc5eb66c8c20" />


**Output:**
<img width="1177" height="531" alt="image" src="https://github.com/user-attachments/assets/b8a5cfc4-85cf-4f58-835c-f5210d1a3c10" />


**Question 3**
---
<img width="1205" height="593" alt="image" src="https://github.com/user-attachments/assets/dd092769-2758-4059-9cbe-ae20f71b7353" />


**Output:**
<img width="814" height="541" alt="image" src="https://github.com/user-attachments/assets/87b8c775-96a7-4df6-8f45-db2122cacf1a" />


**Question 4**
---
<img width="1178" height="772" alt="image" src="https://github.com/user-attachments/assets/6423d8b4-7f07-438e-ac13-65d679adebf4" />


**Output:**
<img width="1250" height="412" alt="image" src="https://github.com/user-attachments/assets/389c3a3a-c08e-4b15-87e5-72a27aaf252b" />


**Question 5**
---


**Output:**

![Output5](output.png)

**Question 6**
---
<img width="936" height="554" alt="image" src="https://github.com/user-attachments/assets/6ef219b6-c1ac-43d0-b9d7-fa3a4c7f5c57" />


**Output:**
<img width="1016" height="497" alt="image" src="https://github.com/user-attachments/assets/efdc2112-a6c0-4eca-b106-e3e8b01fe36a" />


**Question 7**
---
<img width="1198" height="681" alt="image" src="https://github.com/user-attachments/assets/37a209b0-4947-4a15-ad2a-cefff798e29d" />


**Output:**
<img width="1245" height="624" alt="image" src="https://github.com/user-attachments/assets/c96c28b2-b829-4340-a56d-cc6d8f106a59" />

**Question 8**
---
<img width="1162" height="637" alt="image" src="https://github.com/user-attachments/assets/b4986105-e4ce-46c9-9c17-0d269ee97490" />


**Output:**
<img width="1280" height="508" alt="image" src="https://github.com/user-attachments/assets/c385b22e-3f27-4bf7-9128-e644ad181def" />


**Question 9**
---
<img width="1011" height="777" alt="image" src="https://github.com/user-attachments/assets/5c0236ad-eda9-489f-818c-7dfa75363eeb" />


**Output:**
<img width="1263" height="681" alt="image" src="https://github.com/user-attachments/assets/07a0a620-51c7-4dc1-8b5e-760b9db6f560" />


**Question 10**
---
<img width="1104" height="476" alt="image" src="https://github.com/user-attachments/assets/fe917261-edb9-48de-96e6-f2fe0ec139d3" />


**Output:**
<img width="679" height="475" alt="image" src="https://github.com/user-attachments/assets/4c7257d4-089f-4231-8193-b250fc3037b4" />



## RESULT
Thus, the SQL queries to implement aggregate functions, GROUP BY, and HAVING clause have been executed successfully.
