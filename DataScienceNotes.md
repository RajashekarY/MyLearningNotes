The primitive data types supported by Hive are listed below:
1. Numeric Types
TINYINT (1-byte signed integer, from -128 to 127)
SMALLINT (2-byte signed integer, from -32,768 to 32,767)
INT (4-byte signed integer, from -2,147,483,648 to 2,147,483,647)
BIGINT (8-byte signed integer, from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807)
FLOAT (4-byte single precision floating point number)
DOUBLE (8-byte double precision floating point number)
DECIMAL (Hive 0.13.0 introduced user definable precision and scale)
2. Date/Time Types
TIMESTAMP
DATE
3. String Types
STRING
VARCHAR
CHAR
4. Misc Types
BOOLEAN
BINARY
Apart from these primitive data types Hive offers some complex data types which are listed below: 

5. Complex Types
arrays: ARRAY<data_type>
maps: MAP<primitive_type, data_type>
structs: STRUCT<col_name : data_type [COMMENT col_comment], ...>
union: UNIONTYPE<data_type, data_type, ...>