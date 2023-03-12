## The SQL BACKUP DATABASE Statement

- The **_BACKUP DATABASE_** statement is used in SQL Server to create a full back up of an existing SQL database.

* Syntax :

  > BACKUP DATABASE databasename <br>
  > TO DISK = 'filepath';

&nbsp;

## The SQL BACKUP WITH DIFFERENTIAL Statement

- A differential back up only backs up the parts of the database that have changed since the last full database backup.

- Syntax :

  > BACKUP DATABASE databasename <br>
  > TO DISK = 'filepath' <br>
  > WITH DIFFERENTIAL;

&nbsp;

- Example :

  ```
  BACKUP DATABASE testDB
  TO DISK = 'D:\backups\testDB.bak';
  ```

* Example 2 :

  ```
  BACKUP DATABASE testDB
  TO DISK = 'D:\backups\testDB.bak'
  WITH DIFFERENTIAL;
  ```
