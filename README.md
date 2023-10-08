## DOC

```python
import sqlite3

conn = sqlite3.connect('company_database.db')
print("Opened Database succesfully")

conn.execute('''
CREATE TABLE IF NOT EXISTS Employee
(ssn INT NOT NULL,
fname TEXT NOT NULL,
sex INT NOT NULL,
salary INT,
lname TEXT,
adress TEXT,
bdate DATETIME,
minit INT,
dno INT,
PRIMARY KEY(ssn));''')

print("Table created succesfully")
```

Creating database with sqlite

Creating table with employee details.

Next Code Block in the google collab create other tables from the Week4 assingment. 
