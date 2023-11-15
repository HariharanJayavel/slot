# Ex03 Time Table
## Date:31.10.2023

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="yellow">
<caption><b>SLOT TIME TABLE - HARIHARAN J (23011967)</b></caption>
<tr align="center">
<th bgcolor="violet">Day/Time</th>
<th bgcolor="violet">Monday
<th bgcolor="violet">Tuesday
<th bgcolor="violet">Wednesday
<th bgcolor="violet">Thursday
<th bgcolor="violet">Friday
</tr>
<tr align="center">
<th bgcolor="violet">8-10</th>
<td >SOFT SKILLS</td>
<td >ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td >ENGINEERING DESIGN AND MODELLING</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr align="center">
<th bgcolor="violet">10-12</th>
<td >FREE SLOT</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >FREE SLOT</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td >FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr>
<th bgcolor="violet">12-01</th>
<td colspan="5" align="center"> L U N C H</td>
</tr>
<tr>
<tr align="center">
<th bgcolor="violet">01-03</th>
<td >ENGINEERING DESIGN AND MODELLING</td>
<td >FREE SLOT</td>
<td >FREE SLOT</td>
<td >FUNDAMENTALS OF C PROGRAMMING</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="violet">03-05</th>
<td >ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
<td >FREE SLOT</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
<td >FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>No.</th>
<th>Subject code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING(C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI301C</td>
<td>PYTHON AND LINEAR ALGEBRA(PYTHON PROGRAM AND LINEAR ALGEBRA)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI303</td>
<td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT(EMPD)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI302</td>
<td>ENGINEERING DESIGN AND MODELLING(EDM)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>SOFT SKILLS(SS)</td>
</tr
</table>
</body>
</html>
```
## OUTPUT

![OUTPUT](<Screenshot 2023-11-07 151939.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
