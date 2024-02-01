
## Day 1:  SQL Implementation
	4 languages in one 


### Data Manipulation Language #DML
	incomplete list of all the commands but basically the crud portion of the crud app are implemented here

##### 1. `SELECT`
##### 2. `INSERT`
##### 3. `UPDATE`
##### 4. `DELETE`

### Data Definition Language #DDL
##### 1. `CREATE` 
##### 2. `DROP` 
##### 3. `ALTER` 
##### 4. `TRUNCATE`
### Data Control Language #DCL
##### 1. `GRANT`
	We can give certain permissions for the table (and other objects) for specified groups/users of a database.
##### 2. `DENY`
	Bans certain permissions from groups/users.
##### 3. `REVOKE`
	this command takes away permissions from groups/users.
### Transaction Control Language #TCL




## Day 2 : Plan execution  (2024-01-01)

an sql query is first translated into an execution plan and then each of the following pieces are executed 

Thus the steps to implement a dbms system would broadly break down into 3 categories


1. Memory manipulation to read/write the data 
2. XML plan to create a pipeline of data to make the memory manipulation process abstracted behind a standard
3. Comilation and execution of SQL

Main focus for now would be 

1. Set up the raspberry pi to read and write  into files
2. Create a basic structure to access and manipulate the data in an sd card