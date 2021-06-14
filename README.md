# kiccampus
---
# oracle setting

### Cmd/SQL PLUS
**C:\Users\KITCOOP>sqlplus system/1111**

SQL*Plus: Release 11.2.0.2.0 Production on 월 6월 14 12:12:13 2021

Copyright (c) 1982, 2014, Oracle.  All rights reserved.


Connected to:
Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production

**SQL> create user kic identified by 1111;** //kic이라는 유저 만들기

User created.

**SQL> grant resource, connect to kic;** //유저에게 resource, connect 권한부여

Grant succeeded.

**SQL> exit**

Disconnected from Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production

**C:\Users\KITCOOP>sqlplus kic/1111**

SQL*Plus: Release 11.2.0.2.0 Production on 월 6월 14 12:26:31 2021

Copyright (c) 1982, 2014, Oracle.  All rights reserved.


Connected to:
Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production

### SQL DEVELOPER
oracle > openJDK version-14 download

<<http://jdk.java.net/java-se-ri/14>>

create java folder

put (jdk-14)file <C:\Program Files\java\jdk-14>

**enviroment variable setting**

내pc > 속성 > 고급 시스템 설정 > 환경 변수 > 시스템변수

새로만들기 >> 변수이름 : JAVA_HOME / 변수 값 : C:\Program Files\java\jdk-14

path > C:\Program Files\java\jdk-14\bin 추가

sqldeveloper-4.1.3 다운

**  SQL DEVELOPER 실행시 DLL 에러 해결**

sqldeveloper > jdk > jre > bin > msvcr100.dll

msvcr100.dll >> system32 폴더에 추가
