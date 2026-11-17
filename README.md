# Ex04 Time Table
## Date:17.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>slot time table 2026</title>
    </head>
    <body>
       <center><img src="logo.png" width="900"></center> 
   <center><table border="1" cellspacing="2" cellpadding="10"></center>
    <caption><b>slot time table 2026-Dharsini R(26005256)</b></caption>
		<tr bgcolor="dark blue">
			<th>DAY/TIME</th>
			<th>MONDAY</th>
			<th>TUESDAY</th>
			<th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURADY</th>
		</tr>
        <tr bgcolor="grey">
			<td bgcolor="dark blue">08-9:30</td>
			<td bgcolor="white"></td>
			<td>CD</td>
			<td>CL</td>
            <td>DE</td>
            <td>STAT</td>
            <td bgcolor="white"></td>
		</tr>
        <tr bgcolor="grey">
			<td bgcolor="dark blue">09:45-11:15</td>
			<td>DE</td>
			<td>FWAD</td>
			<td bgcolor="white"></td>
            <td>STAT</td>
            <td>FWAD</td>
            <td>EDM</td>
		</tr>
        <tr bgcolor="grey">
        <td bgcolor="dark blue">11:30-12:15</td>
        <td colspan="6"><center>MM</center></td>
		</tr>
        <tr bgcolor="grey">
        <td bgcolor="dark blue">12:15-1:00</td>
        <td colspan="6"><center>LUNCH</center></td>
		</tr>
         <tr bgcolor="grey">env
			 <td bgcolor="dark blue">1:15-2:45</td>
			<td>FWAD</td>
			<td>CL</td>
			<td bgcolor="white"></td>
            <td>EDM</td>
            <td bgcolor="white"></td>
            <td bgcolor="white"></td>
		</tr>
         <tr bgcolor="grey">
			<td bgcolor="dark blue">3:00-4:30</td>
			<td bgcolor="white"></td>
			<td bgcolor="white"></td>
			<td>EMPD</td>
            <td>EMPD</td>
            <td bgcolor="white"></td>
            <td bgcolor="white"></td>
		</tr>


        <center><table border="1" cellspacing="2" cellpadding="10"></center>
<tr bgcolor="green">
			<th>S.NO</th>
			<th>SUBJECT CODE</th>
			<th>SUBJECT NAME</th>
		</tr>
        <tr>
			<td  bgcolor="green">1</td>
			<td>19AI414</td>
			<td>Fundamentals of Web Application Development(FWAD)</td>
		</tr>
         <tr>
			<td  bgcolor="green">2</td>
			<td>19EE404 </td>
			<td> Digital Electronics(DE)</td>
		</tr>
        <tr>
			<td  bgcolor="green">3</td>
			<td>19EY708</td>
			<td> Career Development Skills(CD)</td>
		</tr>
         <tr>
			<td  bgcolor="green">4</td>
			<td>19CS418 </td>
			<td>Cyber Law and Compliance(CL)</td>
		</tr>
         <tr>
			<td  bgcolor="green">5</td>
			<td>19AI303 </td>
			<td>Engineering Mechanics and Product Development(EMPD)</td>
		</tr>
         <tr>
			<td  bgcolor="green">6</td>
			<td>19MA211  </td>
			<td>Statistics and Numerical Methods(STAT)</td>
		</tr>
         <tr>
			<td  bgcolor="green">7</td>
			<td>19AI302 </td>
			<td> Engineering Design and Modelling(EDM)</td>
		</tr>


```

## OUTPUT
![alt text](<Screenshot (19).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
