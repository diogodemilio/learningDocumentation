# PL/SQL Fundamentals

## Data Types

### Integer

BINARY\_INTEGER or PLS\_INTEGER \
&#x20;\-> More efficient than NUMBER. Should be used if values will be integer

SIMPLE\_INTEGER \
\-> Only available in Oracle 11g and later. Better performance than PLS\_INTEGER

### Floating

BINARY\_FLOAT\
&#x20;\-> 32-bit single precision float\
&#x20;\-> Offers more precision than NUMBER(). \
&#x20;\-> Supports **infinity** and **NaN**

BINARY\_DOUBLE\
&#x20;\-> 64-bit double precision.\
&#x20;\-> Recommmended for scientific computign applications.

NUMBER (precision,scale)\
&#x20;\-> Precision from 1 to 38 and Scale from -84 to 127.\
&#x20;\-> Can be integer or floating point but will operate slower that the types identified above.

### Character

CHAR(n)\
&#x20;\-> Fixed length from 1 to 32,767\
&#x20;\-> Map CHAR or LONG database columns

VARCHAR2(n)\
&#x20;\-> Varied length from 1 to 32,767\
&#x20;\-> Map VARCHAR2 or LONG database columns

