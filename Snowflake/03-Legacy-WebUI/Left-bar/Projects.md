# Projects > Worksheets

Under Projects on the left-hand panel, select the **​Worksheets​** tab. This provides the following

- **interface for submitting SQL queries**,
- **performing DDL and DML operations**,
- **viewing results** as your queries or operations complete.

A new worksheet is created by clicking **+** on the top right.

&nbsp;

&nbsp;

# Worksheet Structure

The **top left corner** contains the following:

- **Snowflake icon**: Use this to get back to the main console/close the worksheet.

- **Worksheet_name drop-down**: The default name is the **timestamp** when the worksheet was created. Click the timestamp to edit the worksheet name. The drop-down also displays additional actions you can perform for the worksheet.

- **Filters button**: Custom filters are special keywords that resolve as a sub-query or list of values.

&nbsp;

The **top right corner** contains the following:

- **Context box**: This lets Snowflake know which role and warehouse to use during this session. It can be changed via the UI or SQL commands.

- **Share button**: Open the sharing menu to share to other users or copy the link to the worksheet.
  Play/Run button: Run the SQL statement where the cursor currently is or multiple selected statements.

&nbsp;

The **middle pane** contains the following:

- **Drop-down** at the top for setting the database/schema/object context for the worksheet.
- **General working area** where you enter and execute queries and other SQL statements.

&nbsp;

The **middle-left panel** contains the following:

- **Worksheets tab**: Use this tab to quickly select and jump between different worksheets
- **Databases tab**: Use this tab to view all of the database objects available to the current role
- **Search bar**: database objects browser which enables you to explore all databases, schemas, tables, and views accessible by the role currently in use for the worksheet.

The bottom pane displays the results of queries and other operations. Also includes 4 options (Object, Query, Result, Chart) that open/close their respective panels on the UI. Chart opens a visualization panel for the returned results. More on this later.

&nbsp;

The various panes on this page can be resized by adjusting their sliders. If you need more room in the worksheet, collapse the database objects browser in the left panel. Many of the screenshots in this guide keep this panel closed.

**Worksheets vs the UI** Most of the exercises in this lab are executed using pre-written SQL within this worksheet to save time. These tasks can also be done via the UI, but would require navigating back-and-forth between multiple UI tabs.

&nbsp;

&nbsp;

# Projects > Dashboards

Under Projects on the left-hand panel, select the ​Dashboards​ tab. This tab allows you to create flexible displays of one or more charts (in the form of tiles, which can be rearranged). Tiles and widgets are produced by executing SQL queries that return results in a worksheet. Dashboards work at a variety of sizes with minimal configuration.

&nbsp;

&nbsp;

# Data > Databases

Under Data, the Databases​ tab shows information about the databases you have created or have permission to access. You can create, clone, drop, or transfer ownership of databases, as well as load data in the UI. Notice that a database already exists in your environment. However, we will not be using it in this lab.

&nbsp;

&nbsp;

&nbsp;
