# kiccampus
---
## oracle setting

1. Cmd
C:\Users\KITCOOP>sqlplus system/1111

SQL*Plus: Release 11.2.0.2.0 Production on 월 6월 14 12:12:13 2021

Copyright (c) 1982, 2014, Oracle.  All rights reserved.


Connected to:
Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production

SQL> create user kic identified by 1111;

User created.

SQL> grant resource, connect to kic;

Grant succeeded.

SQL> exit
Disconnected from Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production

C:\Users\KITCOOP>sqlplus kic/1111

SQL*Plus: Release 11.2.0.2.0 Production on 월 6월 14 12:26:31 2021

Copyright (c) 1982, 2014, Oracle.  All rights reserved.


Connected to:
Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production
