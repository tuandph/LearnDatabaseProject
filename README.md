# LearnDatabaseProject
Practice how to work with database project in real life

# Problem:
1. SQL Server cannot snapshot changes.
2. Changes need other devs review before merge to Database

# Solution:
Micosoft prodive Dabase project included in Visual Studio. So, you can intergrated with source control like .git. With enable you to 
1. Create branches (manage feature)
2. Create PR
3. Review carefully after changes in real database
4. Compare schema changes with current database before apply

# Key Features
1. Create Table
2. Init Data for Table
3. Extend Script.PostDeployment.sql to ContinuousDeployment folder
4. Compare schema before apply

![image](https://user-images.githubusercontent.com/12756406/183879019-406660d8-b2a7-4d05-9ce7-167bd02f1b7b.png)

![image](https://user-images.githubusercontent.com/12756406/183878654-52b43901-c801-4a04-b0bf-4b6255cf6520.png)
