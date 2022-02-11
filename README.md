# Database-and-Mysql-Practice

### 1. MySQL:

![creating](https://user-images.githubusercontent.com/93571037/153547784-3e510350-85fb-4c4d-95e9-09194a4f6626.png)


### 2. create and show database:

```syntax
CREATE DATABASE database_name;
SHOW DATABASES;
```

![create_database](https://user-images.githubusercontent.com/93571037/153418644-b017819a-c423-4c32-8061-213c4115106a.png)

### 3. Deleting a database;

```syntax 
DROP DATABASE database_name;
```

![Drop_database](https://user-images.githubusercontent.com/93571037/153636426-5b21f1f2-1e61-423b-9a32-c54aa3432bb2.png)

### 4. Use database:

```syntax
USE database_name;
```

![use_database](https://user-images.githubusercontent.com/93571037/153546844-5a578393-e4e9-49db-9159-47638cebf728.png)

### 5. Show available tables:

```syntax
SHOW TABLES;
```

![show_table](https://user-images.githubusercontent.com/93571037/153547632-c9948cc6-962c-46e7-80c5-d1fc1b3d5c57.png)

### 6. Creating a table:

```syntax
CREATE TABLE table_name ( column_name datatype extra_info, 2nd column_name datatype extra_info,...);
```

![create_table](https://user-images.githubusercontent.com/93571037/153548997-addf3bb8-752c-42a2-9699-cd50f50fef47.png)

### 7. describing the nature of table created:

```syntax 
DESC|DESCRIBE table_name;
```

![desc_table](https://user-images.githubusercontent.com/93571037/153642030-93e9eb9f-d6a8-4ecf-b513-86b91a8f2c1d.png)

### 8. Inserting values into a table:

```syntax
INSERT INTO table_name(column_name1,column_name2,column_name3,..) VALUES (values of row1),(values of row2)...
```

![insert into tech](https://user-images.githubusercontent.com/93571037/153634869-86ae8816-25e1-4455-b7d3-3e594e021bc8.png)

### 9. Altering a table:

#### * adding a column:

```syntax
ALTER TABLE table_name ADD column_name datatype [FIRST|AFTER column_name];
```

![add_column](https://user-images.githubusercontent.com/93571037/153637595-839b4171-e451-4177-a5f3-ba076ea88b02.png)

#### * adding multiple columns;

```syntax
ALTER TABLE table_name 
ADD column_name datatype [AFTER|FIRST column_name]
ADD column_name datatype [AFTER|FIRST column_name]...

#### * renaming a column:

```syntax 
ALTER TABLE table_name RENAME COLUMN old_column_name TO new_column_name;
```

![rename_column](https://user-images.githubusercontent.com/93571037/153638091-f0e170c4-46db-4b84-89f5-92b904cb5512.png)

#### * changing a column or renaming (another method):

```syntax
ALTER TABLE table_name CHANGE COLUMN old_column_name new_column_name;
```

![rename_2nd_method](https://user-images.githubusercontent.com/93571037/153638457-5e9a417d-f180-4c33-ad87-1cefdf15c4f1.png)

#### * Changing a column's nature/modifying a table:

```syntax
ALTER TABLE table_name MODIFY column_name new_informations;
```

![alter_modify](https://user-images.githubusercontent.com/93571037/153639856-78055f06-b4bc-48c8-b583-d0a8e9dfecfd.png)

#### * Deleting a column from a table:

```syntax
ALTER TABLE table_name DROP COLUMN column_name;
```

![drop_column](https://user-images.githubusercontent.com/93571037/153640849-caacab23-e50b-4e4e-9b31-9face3337ef1.png)

#### * Renaming a table;

```syntax
ALTER TABLE table_name RENAME TO new_table_name;
```

![rename_table](https://user-images.githubusercontent.com/93571037/153641479-0eca5bc9-0237-4e50-a6e3-6490f2c0105f.png)

### 10. Updating data inside a table:

```syntax
UPDATE table_name SET column_1= 'value', column_2= 'value' WHERE condition;
```

![updat](https://user-images.githubusercontent.com/93571037/153643597-c9cbb7e8-d2a7-45f1-a014-b4691a18f476.png)

### 11. Deleting a data from table(deletes a row);

```syntax
DELETE FROM table_name WHERE condition;
```

![delete_data](https://user-images.githubusercontent.com/93571037/153644757-df24c6d8-9448-4908-ab96-60ddb94a5633.png)

### 12.















