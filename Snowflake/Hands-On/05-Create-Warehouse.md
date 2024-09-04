# Create a virtual warehouse

If there is no warehouse we can create this.

Create an **X-Small** warehouse named **sf_tuts_wh** using the **_CREATE WAREHOUSE_** command:

```sql
CREATE OR REPLACE WAREHOUSE sf_tuts_wh WITH
   WAREHOUSE_SIZE='X-SMALL'
   AUTO_SUSPEND = 180
   AUTO_RESUME = TRUE
   INITIALLY_SUSPENDED=TRUE;
```

&nbsp;

&nbsp;

The **sf_tuts_wh** warehouse is initially suspended, but the DML statement also sets **AUTO_RESUME = true**. The AUTO_RESUME setting causes a warehouse to automatically start when SQL statements that require compute resources are executed.

&nbsp;

After you create the warehouse, it’s now in use for your current session. This information is displayed in your SnowSQL command prompt. You can also retrieve the name of the warehouse by using the following context function:

```sql
SELECT CURRENT_WAREHOUSE();
```

&nbsp;

```
+---------------------+
| CURRENT_WAREHOUSE() |
|---------------------|
| SF_TUTS_WH          |
+---------------------+
```
