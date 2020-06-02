# ORM 

## Miss match between DB and App.

1. **Persistence** of data is one of the fundamental requirement of any Java application
2. Therefore DB is used, although **DB follows SQL** Language most of the time
3. On the other hand **Application follows Object Oriented** Language
4. To **reduce the mismatch** between this two, a need of ORM arises
5. Although Java app can interface with DB without ORM
6. ORM reduces the boilerplate code and programmer can focus on business logic rather then interface with DB 
7. ORM can provide solution for problems like Granularity, Inheritance, Identity, Association, Navigation
8. **Granularity** refers to the miss match between number of **object model** and number of tables in **DB**
9. **Inheritance** is not defined in Relational DBs
10. **Associations** OOP Language represent association using object ref. RDB represent it by foreign key
11. **Identity** Notation in RDB is primary key, whereas in OOP Language (a==b) [Object Identity]as well as (a.equals(b)) [Object Equality]  (pg.15)
12. Navigation describe the way of accessing the data 

## What is ORM?

1. ORM stands for **O**bject **R**elational **M**apping
2. A programming technique for **converting data** between **RD and OOP** languages
3. **Problem Statement:**
   1. **Persistence** of data is one of the fundamental requirement of any Java application
   2. Therefore DB is used, although **DB follows SQL** Language most of the time
   3. On the other hand **Application follows Object Oriented** Language
   4. To **reduce the mismatch** between this two, a need of ORM arises
   5. Although Java app can interface with DB without ORM
   6. ORM reduces the boilerplate code and programmer can focus on business logic rather then interface with DB 
   7. ORM can provide solution for problems like Granularity, Inheritance, Identity, Association, Navigation
   8. **Granularity** refers to the miss match between number of **object model** and number of tables in **DB**
   9. **Inheritance** is not defined in Relational DBs
   10. **Associations** OOP Language represent association using object ref. RDB represent it by foreign key
   11. **Identity** Notation in RDB is primary key, whereas in OOP Language (a==b) [Object Identity]as well as (a.equals(b)) [Object Equality]  (pg.15)
4. 

## Links

1. [JPA vs. Raw JDBC](https://medium.com/@Colin_But/spring-data-jpa-vs-raw-jdbc-e3492354d2ab)
2. 

