---
layout: post
title: "sqli-labs lesson 1"
data: 2014-12-23
categories: WEB 
tag: SQL
---

First, you must install sqli-labs in local.<br> 
Install Instructions:<br>
1. Unzip the contents inside the apache folder, for example under /var/www <br>
2. This will create a folder sql-labs under it. else you can use git command from within /var/www folder. /var/www folder and then use following command> git clone https://github.com/Audi-1/sqli-labs.git sqli-labs<br>
3. Open the file "db-creds.inc" which is under sql-connections folder inside the sql-labs folder.<br>
4. Update your MYSQL database username and password.(default for Backtrack are used root:toor)<br>
5. From your browser access the sql-labs folder to load index.html<br>
6. Click on the link setup/resetDB to create database, create tables and populate Data.<br>
7. Labs ready to be used, click on lesson number to open the lesson page.<br>
8. Enjoy the labs <br>
and you can see `https://github.com/Audi-1/sqli-labs`

that all, you can open sqli-labs in browser, then  open the number of one in lesson, just is `http://localhost/sqli-labs/Less-1/`  ,you can see <br>
		`Welcome    Dhakkan`<br>
	`Please input the ID as parameter with numeric value`

continue, you can modify uri address in browser, just as `http://localhost/sqli-labs/Less-1/?id=1` , yeah,only
add "?id=1" in last url address.refresh pages. ok, you can see<br>
`Your Login name:Dumb`<br>
`Your Password:Dumb` <br>
so, I think sql commit is: `select name, passwd from user_table where id= user_input`, you can modify the value of id, etc id=1, id=2,id=3.......but as you id=abc, then you see this error: You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ''1'' LIMIT 0,1' at line 1.  please watch out "LIMIT 0,1" so i can know this sql commit is single quotes.

