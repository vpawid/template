---
layout: project
type: project
published: true
image: images/finalproject.PNG
title: LoL Calculator
date: 2014
labels:
  - SQL
  - Java
  - mySql
summary: My team developed an application to make statistical calculation for League of Legends
---

## 1) The Project
<hr>
Professional gamers must make concise decisions within milliseconds or it may cost them to lose a 
match. To make these choices they study and memorize a vast amount of information about each 
aspect of the game. For the ordinary player, these games are less competitive which makes putting 
in the effort to study the game very trivial. Therefore, my team and I decided to try to make a 
statistical calculator that had all the data that a professional gamer would know and make 
calculations depending on the given situation. It takes in to account most everything, from 
purchasable items to the health of a target, and also can compare statistics against another 
character.

<img class="ui middle aligned centered image" src="../images/finalhud.PNG">

## 2) What's Your Role 
<hr>
For this particular project, I could have been considered the DBA. I gathered all the data from an 
open data source which the game creators provided. I also migrated all the data to the teams mySql 
database system. Then helped with the application side by connecting the Java application to the 
mySql database through a JDBC connection. Finally I wrote simple SQL queries to pull needed data 
for the application to use to calculate.

```
String url = "jdbc:mysql://192.254.189.7:3306/vpawid_321project";
               Class.forName ("com.mysql.jdbc.Driver");
               conn =DriverManager.getConnection(url,"vpawid_test","ics321");
               System.out.println ("Database connection established");
                
               PreparedStatement statement = conn.prepareStatement("select 
Champion_name, Champion_id from Passives WHERE Champion_id > 100");
```

## 3) The Experience
<hr>
This project was a terrific way to end my introduction to the SQL database and set theory. I enjoyed 
applying my gained knowledge from the class into a tangible application. The experience also tested 
my communication and team skills; being that this was my first experience working on a 
programming project with others it proved to be a lot more difficult then expected. From then on I 
learned the value of repositories and why every project should have their own, especially when a 
group member breaks the code and the application needs to be rolled back. And I also learned the 
value of using a digital workspace such as slack and how the lack there of one is incredibly 
inefficient.
