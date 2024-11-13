# Ex04 Time Table
## Date:13/11/24

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
<html></html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png"height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="gold">
<caption><b>SLOT TIMETABLE - DURGADEVI P (212223100006)</b></caption>
<tr align="center">
	<th bgcolor="blue">Day/Time</th>
	<th bgcolor="blue">Monday</th>
	<th bgcolor="blue">Tuesday</th>
	<th bgcolor="blue">Wednesday</th>
	<th bgcolor="blue">Thursday</th>
	<th bgcolor="blue">Friday</th>
    <th bgcolor="blue">Saturday</th>
</tr>
<tr align="center">
	<th bgcolor="blue">8-10</th>
	<td>FREE </td>
	<td>CN</td>
	<td> WEB</td>
	<td>FREE </td>
	<td>STATISTIC</td>
    <td>FREE </td>
</tr>
<tr align="center">
	<th bgcolor="blue">10-12</th>
	<td>ANT</td>
	<td>GEN AI</td>
	<td>STATISTIC</td>
	<td>ANT </td>
	<td>FREE</td>
    <td>EMPD</td>
</tr>
<tr>
	<th bgcolor="blue">12-1</th>
	<td colspan="5" align="center">L U N C H   B R E A K</td>
</tr>
<tr align="center">
	<th bgcolor="blue">1-3</th>
	<td>ML</td>
	<td>FREE </td>
	<td>MENTOR MEET</td>
	<td>QUANTITATIVE</td>
	<td>FREE </td>
    <td>CN</td>
</tr>
<tr align="center">
	<th bgcolor="blue">3-5</th>
	<td>FREE </td>
	<td>FREE </td>
	<td>FREE </td>
	<td>EMPD</td>
	<td>FREE </td>
    <td>FREE </td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI303</td>
<td>Engineering Mechanics and Product Development</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI410</td>
<td>Intro to Machine Learning</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS406</td>
<td>Computer Networks</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS579</td>
<td>Generative AI Application Development</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY710</td>
<td>Quantitative Ability I</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical Methods</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19MA212</td>
<td>Algebra and Number Theory</td>
</tr>
<td align="center">8.</td>
<td align="center">19AI305</td>
<td>Advanced C Programming</td>
</tr>
<td align="center">9.</td>
<td align="center">ECA-M</td>
<td>Mentor Meet</td>
</tr>


</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (220).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
