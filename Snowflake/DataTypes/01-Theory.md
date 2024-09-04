Snowflake supports most basic SQL data types (with some restrictions) for use in columns, local variables, expressions, parameters, and any other appropriate/suitable locations.

&nbsp;

In some cases, data of one type can be converted to another type. For example, INTEGER data can be converted to FLOAT.

&nbsp;

&nbsp;

# Supported Data Types

| Category                   | Type                                             | Notes                                                                     |
| -------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------- |
| Numeric data types         | NUMBER                                           | Default precision and scale are (38,0).                                   |
|                            | DECIMAL, NUMERIC                                 | Synonymous with NUMBER.                                                   |
|                            | INT, INTEGER, BIGINT, SMALLINT, TINYINT, BYTEINT | Synonymous with NUMBER except precision and scale cannot be specified.    |
|                            | FLOAT, FLOAT4, FLOAT8                            |
|                            | DOUBLE, DOUBLE PRECISION, REAL                   | Synonymous with FLOAT.                                                    |
| String & binary data types | VARCHAR                                          | Default (and maximum) is 16,777,216 bytes.                                |
|                            | CHAR, CHARACTER                                  | Synonymous with VARCHAR except default length is VARCHAR(1).              |
|                            | STRING                                           | Synonymous with VARCHAR.                                                  |
|                            | TEXT                                             | Synonymous with VARCHAR.                                                  |
|                            | BINARY                                           |
|                            | VARBINARY                                        | Synonymous with BINARY.                                                   |
| Logical data types         | BOOLEAN                                          | Currently only supported for accounts provisioned after January 25, 2016. |
| Date & time data types     | DATE                                             |
|                            | DATETIME                                         | Alias for TIMESTAMP_NTZ                                                   |
|                            | TIME                                             |
|                            | TIMESTAMP                                        | Alias for one of the TIMESTAMP variations (TIMESTAMP_NTZ by default).     |
|                            | TIMESTAMP_LTZ                                    | TIMESTAMP with local time zone; time zone, if provided, is not stored.    |
|                            | TIMESTAMP_NTZ                                    | TIMESTAMP with no time zone; time zone, if provided, is not stored.       |
|                            | TIMESTAMP_TZ                                     | TIMESTAMP with time zone.                                                 |
| Semi-structured data types | VARIANT                                          |
|                            | OBJECT                                           |
|                            | ARRAY                                            |
| Geospatial data types      | GEOGRAPHY                                        |
|                            | GEOMETRY                                         |
| Vector data types          | VECTOR                                           |

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
