# Ex03 Time Table
## Date:06.04.24

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
```html
<html>
<head>
<title> My Time Table </title>
</head>
<body>
<center>
<table border="3" cellspacing="6" cellpading="6">
<caption>SLOT TIMETABLE - MITHUN KALYAN(212223040142)</caption>
<tr>
<th bgcolor="green">Day/Time</th>
<th bgcolor="green">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="green">Wednesday</th>
<th bgcolor="green">Thursday</th>
<th bgcolor="green">Friday</th>
<th bgcolor="green">Saturday</th>
</tr>
<tr>
<td bgcolor="green">8-10</td>
<td bgcolor="pink">FREE</td>
<td bgcolor="pink">FREE</td>
<td bgcolor="pink">FRENCH</td>
<td bgcolor="pink">WEB</td>
<td bgcolor="pink">WEB</td>
<td bgcolor="pink">PROB</td>
</tr>
<tr>
<td bgcolor="green">10-12</td>
<td bgcolor="lightblue">FREE</td>
<td bgcolor="lightblue">SM</td>
<td bgcolor="lightblue">FREE</td>
<td bgcolor="lightblue">PROB</td>
<td bgcolor="lightblue">C</td>
<td bgcolor="lightblue">ANT</td>
</tr>
<tr>
<td bgcolor="green">12-1</td>
<td colspan="6" bgcolor="violet">------------BREAK TIME------------</td>
</tr>
<tr>
<td bgcolor="green">1-3</td>
<td bgcolor="lightblue">ANT</td>
<td bgcolor="lightblue">FRENCH</td>
<td bgcolor="lightblue">HRM</td>
<td bgcolor="lightblue">SM</td>
<td bgcolor="lightblue">HRM</td>
<td bgcolor="lightblue">FREE</td>
</tr>
<tr>
<td bgcolor="green">3-5</td>
<td bgcolor="yellow">C</td>
<td bgcolor="yellow">WEB</td>
<td bgcolor="yellow">FREE</td>
<td bgcolor="yellow">FRENCH</td>
<td bgcolor="yellow">FREE</td>
<td bgcolor="yellow">FREE</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19MS156</td>
<td>Human Resource Management(HRM)</td>
</tr>
<tr>
<td>2.</td>
<td>19AI304</td>
<td>Fundamentals of C programming(C)</td>
</tr>
<tr>
<td>3.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Development(WEB)</td>
</tr>
<tr>
<td>4.</td>
<td>19MS155</td>
<td>Stock Market(SM)</td>
<tr>
<td>5.</td>
<td>19MA222</td>
<td>Probability and Queueing Models(PROB)</td>
</tr>
<tr>
<td>6.</td>
<td>19MA212</td>
<td>Algebra and Number Theory(ANT)</td>
</tr>
<tr>
<td>7.</td>
<td>19EN611C</td>
<td>French</td>
</tr>
</table>
</center>
</body>
</html>
```

## OUTPUT

![timeout](https://github.com/MithunKalyan/slot/assets/148410106/390dc0ec-b0b3-4fe8-ae50-2122ac296ec0)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
