## MySQL
---

### DDL 
#### Create DataBase
```
CREATE DATABASE <DataBase Name>
```
#### Create Table
```
CREATE Table <Table Name> (
  <Column> <Type> <condition>
);
```
> ex) <br>
CREATE Table products ( <br>
&nbsp; ID INT AUTO_INCREMENT PRIMARY KEY, <br>
&nbsp; Name VARCHAR(255) NOT NULL, <br>
&nbsp; Brand VARCHAR(255) NOT NULL <Br>
);

#### Delete DataBase
```
DROP DATABASE <DataBase Name>;
```

#### Delete Table
```
DROP TABLE <Table Name>;
```

#### Add Column
```
ALTER TABLE <Table Name> ADD COLUMN <Column> <Type> <condition>;
```

#### Change to Column on Table
```
ALTER TABLE <Table Name> CHANGE <Original Column> <New Column> <Type> <condition>;
```

### Delete Coulmn
```
ALTER TABLE <Table Name> DROP COLUMN <Column>;
```

<br>

---

### DML
#### Put Data on Table
```
INSERT INTO <Table Name> (<Column>) VALUES(<Data>);
```

#### Delete Data on Table
```
DELETE FROM <Table Name>
```

#### Change to Data on Table
```
UPDATE <Table Name> SET <Column>='<Data>' where <Column>='<Data>';
```

#### Select Table Data
```
SELECT * FROM <Table Name>
```

#### Select Table Coulmn
```
explain <Table Name>
```