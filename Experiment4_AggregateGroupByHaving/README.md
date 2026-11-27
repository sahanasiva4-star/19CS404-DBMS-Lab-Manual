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
<img width="1411" height="771" alt="image" src="https://github.com/user-attachments/assets/309acf79-7086-4a21-ad31-a682d799cd82" />


**Output:**

![Output1](output.png)

**Question 2**
<img width="1263" height="778" alt="image" src="https://github.com/user-attachments/assets/b7e1aa7f-b320-4b53-a0e8-f8c0eb0b8abb" />


**Output:**

![Output2](output.png)

**Question 3**
<img width="1110" height="753" alt="image" src="https://github.com/user-attachments/assets/05ce0d94-b64b-48d8-a807-6df5ea864fdc" />


**Output:**

![Output3](output.png)

**Question 4**
<img width="1071" height="597" alt="image" src="https://github.com/user-attachments/assets/8f2ee56c-8dff-400f-b5b0-0e0ee08b0dcf" />


**Output:**

![Output4](output.png)

**Question 5**
<img width="1172" height="612" alt="image" src="https://github.com/user-attachments/assets/7a5dadd0-25a6-45de-9f90-b07680c2407c" />


**Output:**

![Output5](output.png)

**Question 6**
<img width="978" height="572" alt="image" src="https://github.com/user-attachments/assets/9254e5d1-dd34-4d6f-970f-f319f7c2fff0" />


**Output:**

![Output6](output.png)

**Question 7**
<img width="1225" height="610" alt="image" src="https://github.com/user-attachments/assets/df0f740c-4a79-4127-963b-5d8a527564a7" />


**Output:**

![Output7](output.png)

**Question 8**
<img width="1385" height="657" alt="image" src="https://github.com/user-attachments/assets/779d69fd-8417-400a-b2d9-3952a1021d15" />


**Output:**

![Output8](output.png)

**Question 9**
<img width="1377" height="606" alt="image" src="https://github.com/user-attachments/assets/7863ad9e-64da-4858-b066-84691fdb6b8b" />


**Output:**

![Output9](output.png)

**Question 10**
<img width="1410" height="605" alt="image" src="https://github.com/user-attachments/assets/b4f77438-eced-4168-8ba5-bd499af6ac15" />


**Output:**

![Output10](output.png)


## RESULT
Thus, the SQL queries to implement aggregate functions, GROUP BY, and HAVING clause have been executed successfully.
