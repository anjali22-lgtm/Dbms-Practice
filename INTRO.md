DBMS(Database Management System)
Basically,DBMS is a software which is used to store,manage and retrieves data efficiently in a structure format. It allows user to create,update and query data efficiently.
Reduce data redundancy and inconsistency through centrailzed control.


DATABASE------------DBMS--------------USER 

It acts as a bridge between a central database and end user application.

PROBLEM WITH TRADITAIONAL METHOD:
 Before DBMS, we managed data in file system called as hard disk . It came with numerous problems and challenges:
   -Data Redundancy:Dupilcate entries across files
   -No backup/recovery:Data loss was permanent
   -Poor security:No control over data access.
   -Difficuilt Access: Manual files search required.

   Components Of DBMS Apllication:
   -Hardware
   -Software
   -Procedure
   -Data Access language
   -Data
   -People

1.Hardware - Physical devices like servers,disks,input-output devices(Keyboard,monitor,printer).
           - Example Hard disk,RAM, network devices used for dbms


2.Software - Actual dbms software like MYSQL,Orcale,PostgreSql.
           - Include data base engine,OS networks.

3.Data - Raw factor stored in structure or unstructred formats.
       - operational and meta data 
       
4.Procedures -Instructions and rules  for using dbms effectively.
             -secure to use the system.

5.DataBase Access language -It is used to interact with database(create update delete read)
                           -DDL(Data definitation language)
                           -DML(Data Manipulation Language)

6.People -Users interact with dbms at different levels. 
         -Builds appliaction with database.



TYPES OF DBMS:
1.REALATIONAL DATABASE MANAGEMENT SYSTEM(RDBMS):
It organise data into table format composed of rows and columns.
Uses primary key uniquely  to identify rows and foreign key to establish realtion between them.
Queries are written in sql ,which allows for efficient data  and retrieval.
EX: Mysql,Orcale.

2.NoSql:
It is used to handle large sacle data and high performance for scenarios where relational models might be restrictive.
These are stored in non relational formats such as key pairs,documents ,graphs and columns.
EX: MongoDB,Redis

3.Object Oriented DBMS (OODBMS):
It integrates object oriented programming concepts into the data base environment, allowing data to be stored in objects.
EX: ObjectDB

4.Hierarchial Database:
It organise data in tree like structure, where each  record has a single parent have multiple children.
This model is similar to file system where folder having subfolder.
Navigation is fast and  predictable due to fixed structure.
EX: IBM Informtion management system (IMS)

5.Network Database:
It uses as a graph models to allow more complex realtionship between entities.
Unlike the hierarchical model, it permits each child to have multiple parents, enabling many-to-many relationships.
EX:TurboIMAGE

6.Cloud Based Database:
They are hosted on cloud like platforms such as aws,Azure or gogle cloud.
They offer on-demand scalability, high availability, automatic backups and remote accessibility.
EX: Amazon RDS (for SQL), MongoDB Atlas (for NoSQL), Google BigQuery.


DATABASE LANGUAGES: 

DDL                                          DML                                             DCL                                         TCL                                         DQL
.CREATE                                   .INSERT                                          .GRANT                                      .ROLLBACK                                  .SELECT
.DROP                                     .DELETE                                          .REVOKE                                     .COMMIT                                    
.TRUNCATE                                 .UPDATE                                         
.RENAME
.COMMENT
.ALTER

 APPLICATION OF DBMS:
 
- BANKING
- LIBRARY SYSTEM
- ONLINE SHOPING
- HELATHCARE
- SOCIAL MEDIA
            -
