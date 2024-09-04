Snowflake supports the numeric data types for fixed-point numbers.

&nbsp;

&nbsp;

# Number

NUMBER(38, 0)

| Terminology | Description                                                | Default value |
| ----------- | ---------------------------------------------------------- | ------------- |
| Precision   | Total number of digits allowed                             | 38            |
| Scale       | Number of digits allowed to the right of the decimal point | 0             |

&nbsp;

&nbsp;

# Note

Precision limits the range of values that can be inserted into (or cast to) columns of a given type. For example, the value 999 fits into NUMBER(38,0) but not into NUMBER(2,0).

**The maximum scale (number of digits to the right of the decimal point) is 37**.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
