# Experiment 2: DDL Commands

## AIM
To study and implement DDL commands and different types of constraints.

## THEORY

### 1. CREATE
Used to create a new relation (table).

**Syntax:**
```sql
CREATE TABLE (
  field_1 data_type(size),
  field_2 data_type(size),
  ...
);
```
### 2. ALTER
Used to add, modify, drop, or rename fields in an existing relation.
(a) ADD
```sql
ALTER TABLE std ADD (Address CHAR(10));
```
(b) MODIFY
```sql
ALTER TABLE relation_name MODIFY (field_1 new_data_type(size));
```
(c) DROP
```sql
ALTER TABLE relation_name DROP COLUMN field_name;
```
(d) RENAME
```sql
ALTER TABLE relation_name RENAME COLUMN old_field_name TO new_field_name;
```
### 3. DROP TABLE
Used to permanently delete the structure and data of a table.
```sql
DROP TABLE relation_name;
```
### 4. RENAME
Used to rename an existing database object.
```sql
RENAME TABLE old_relation_name TO new_relation_name;
```
### CONSTRAINTS
Constraints are used to specify rules for the data in a table. If there is any violation between the constraint and the data action, the action is aborted by the constraint. It can be specified when the table is created (using CREATE TABLE) or after it is created (using ALTER TABLE).
### 1. NOT NULL
When a column is defined as NOT NULL, it becomes mandatory to enter a value in that column.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) NOT NULL
);
```
### 2. UNIQUE
Ensures that values in a column are unique.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) UNIQUE
);
```
### 3. CHECK
Specifies a condition that each row must satisfy.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) CHECK (logical_expression)
);
```
### 4. PRIMARY KEY
Used to uniquely identify each record in a table.
Properties:
Must contain unique values.
Cannot be null.
Should contain minimal fields.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size) PRIMARY KEY
);
```
### 5. FOREIGN KEY
Used to reference the primary key of another table.
Syntax:
```sql
CREATE TABLE Table_Name (
  column_name data_type(size),
  FOREIGN KEY (column_name) REFERENCES other_table(column)
);
```
### 6. DEFAULT
Used to insert a default value into a column if no value is specified.

Syntax:
```sql
CREATE TABLE Table_Name (
  col_name1 data_type,
  col_name2 data_type,
  col_name3 data_type DEFAULT 'default_value'
);
```

**Question 1**

<img width="1447" height="587" alt="image" src="https://github.com/user-attachments/assets/39c6cbd4-8492-4b4e-9fd8-25542de7bdaa" />


**Output:**

![Output1](output.png)

**Question 2**

<img width="1432" height="727" alt="image" src="https://github.com/user-attachments/assets/15d16677-981b-4f17-82ac-9df4b0a7841c" />


**Output:**

![Output2](output.png)

**Question 3**

<img width="1437" height="698" alt="image" src="https://github.com/user-attachments/assets/6a60f09a-fb2c-48d4-8982-de61c6b378d9" />


**Output:**

![Output3](output.png)

**Question 4**

<img width="1477" height="770" alt="image" src="https://github.com/user-attachments/assets/1f4a5c1e-0885-430b-979f-efa640f2d349" />


**Output:**

![Output4](output.png)

**Question 5**

<img width="1450" height="685" alt="image" src="https://github.com/user-attachments/assets/57aa9e47-8647-4f57-8624-a65357fa49e3" />


**Output:**

![Output5](output.png)

**Question 6**

<img width="1113" height="722" alt="image" src="https://github.com/user-attachments/assets/2ecd5a4f-6dda-461d-9b2f-280b3fdf8b3d" />



**Output:**

![Output6](output.png)

**Question 7**

<img width="1196" height="697" alt="image" src="https://github.com/user-attachments/assets/df8bb80b-4f4a-4a39-b941-35acc0979738" />


**Output:**

![Output7](output.png)

**Question 8**

<img width="1337" height="777" alt="image" src="https://github.com/user-attachments/assets/ab97d547-f567-420d-b844-f2a52f2db7f5" />


**Output:**

![Output8](output.png)

**Question 9**
<img width="1215" height="721" alt="image" src="https://github.com/user-attachments/assets/d5c4c2a9-081b-49b4-ae72-9c98e96d03df" />


**Output:**

![Output9](output.png)

**Question 10**
<img width="1420" height="763" alt="image" src="https://github.com/user-attachments/assets/bb92ca01-af18-4060-ba54-586e54f80615" />


**Output:**

![Output10](output.png)


## RESULT
Thus, the SQL queries to implement different types of constraints and DDL commands have been executed successfully.
