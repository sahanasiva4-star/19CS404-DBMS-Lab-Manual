# Experiment 3: DML Commands

## AIM
To study and implement DML (Data Manipulation Language) commands.

## THEORY

### 1. INSERT INTO
Used to add records into a relation.
These are three type of INSERT INTO queries which are as
A)Inserting a single record
**Syntax (Single Row):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES (value_1, value_2, ...);
```
**Syntax (Multiple Rows):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES
(value_1, value_2, ...),
(value_3, value_4, ...);
```
**Syntax (Insert from another table):**
```sql
INSERT INTO table_name SELECT * FROM other_table WHERE condition;
```
### 2. UPDATE
Used to modify records in a relation.
Syntax:
```sql
UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;
```
### 3. DELETE
Used to delete records from a relation.
**Syntax (All rows):**
```sql
DELETE FROM table_name;
```
**Syntax (Specific condition):**
```sql
DELETE FROM table_name WHERE condition;
```
### 4. SELECT
Used to retrieve records from a table.
**Syntax:**
```sql
SELECT column1, column2 FROM table_name WHERE condition;
```
**Question 1**
<img width="1467" height="778" alt="image" src="https://github.com/user-attachments/assets/f47f4f09-3236-4aaa-a2dc-b023821038a2" />


**Output:**

![Output1](output.png)

**Question 2**
<img width="1473" height="757" alt="image" src="https://github.com/user-attachments/assets/67ea4002-2839-44a8-8449-b80d1a077bdb" />


**Output:**

![Output2](output.png)

**Question 3**
<img width="1488" height="811" alt="image" src="https://github.com/user-attachments/assets/5558c1ab-a885-42ad-b46a-4947ba591b9e" />


**Output:**

![Output3](output.png)

**Question 4**
<img width="1426" height="787" alt="image" src="https://github.com/user-attachments/assets/ef65512d-7887-47d4-845d-d5c89099a85b" />
<img width="1440" height="503" alt="image" src="https://github.com/user-attachments/assets/31a49eb1-ffed-4b09-9459-b565a2175e38" />


**Output:**

![Output4](output.png)

**Question 5**
<img width="1475" height="795" alt="image" src="https://github.com/user-attachments/assets/9a0cf3d3-425b-49b0-ba25-9b1e01862ffa" />


**Output:**

![Output5](output.png)

**Question 6**
<img width="1412" height="712" alt="image" src="https://github.com/user-attachments/assets/70763289-1ba9-42f0-bd3f-6178ca6cc608" />


**Output:**

![Output6](output.png)

**Question 7**
<img width="1386" height="412" alt="image" src="https://github.com/user-attachments/assets/9400b91d-228d-4bdc-9f74-a1bdffd83c18" />


**Output:**

![Output7](output.png)

**Question 8**
<img width="1431" height="430" alt="image" src="https://github.com/user-attachments/assets/fb03a7d3-56d5-478f-b36b-72a989526777" />
<img width="957" height="222" alt="image" src="https://github.com/user-attachments/assets/97774663-fe36-41e3-acc5-4fa45646bac7" />


**Output:**

![Output8](output.png)

**Question 9**
<img width="1458" height="818" alt="image" src="https://github.com/user-attachments/assets/ed2e3bf3-af12-481e-bd57-98487afdf434" />


**Output:**

![Output9](output.png)

**Question 10**
<img width="1475" height="362" alt="image" src="https://github.com/user-attachments/assets/d6eb2bfe-fff3-4bc4-af5a-38f35d76d9fe" />


**Output:**

![Output10](output.png)

## RESULT
Thus, the SQL queries to implement DML commands have been executed successfully.
