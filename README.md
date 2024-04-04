# Ex03 Time Table
## Date:

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
<img src="logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lavender">
<caption><b>SLOT TIME TABLE - SWETHA D (212223040222)</b></caption>
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
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPEMENT</td>
<td >INTRODUCTION TO MACHINE LEARNING</td>
<td >COMPUTER ARCHITECTURE</td>
<td >CALCULUS AND MATRIX ALGEBRA</td>
<td >FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="violet">10-12</th>
<td >FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</td>
<td >COMPUTER ARCHITECTURE</td>
<td >FREE SLOT</td>
<td >FREE SLOT</td>
<td >FUNDAMENTALS OF C</td>
</tr>
<tr>
<th bgcolor="violet">12-01</th>
<td colspan="5" align="center"> L U N C H - B R E A K</td>
</tr>
<tr>
<tr align="center">
<th bgcolor="violet">01-03</th>
<td >CALCULUS AND MATRIX ALGEBRA</td>
<td >FREE SLOT</td>
<td >DIGITAL ELECTRONICS</td>
<td >FUNDAMENTALS OF WEB APPLICATION AND DEVELOPEMENT</td>
<td >FUNDAMENTALS OF WEB APPLICATION AND DEVELOPEMENT</td>
</tr>
<tr align="center">
<th bgcolor="violet">03-05</th>
<td >FUNDAMENTALS OF C</td>
<td >FREE SLOT</td>
<td >FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</td>
<td >FREE SLOT</td>
<td >FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>No.</th>
<th>Subject Code:</th>
<th>Subject Name:</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI405</td>
<td>FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA201</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI410</td>
<td>INTRODUCTION TO MACHINE LEARNING</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EE404</td>
<td>DIGITAL ELECTRONCS</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19CS305</td>
<td>COMPUTER ARCHITECTURE</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![output](https://github.com/swetha23013979/slot/assets/153823422/7639c05d-a58b-4e26-a946-c798bc977879)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
