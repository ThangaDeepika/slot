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

# index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Timetable</title>
</head>
<body style="display: flex; flex-direction: column; align-items: center; font-size: 1.5rem;">
    <img src="sec Logo.png" width="40%">
    <h1>Thanga Deepika R(212221040170)</h1>
	<table border='3'  cellspacing="4" cellpadding='4'   style="width: 50%;">
		<tr bgcolor="#eec0c8">
			<th style="background-color: lightcoral">Day/Time</th>
			<th>Monday</th>
			<th style="background-color: hsl(352, 100%, 86%);">Tuesday</th>
			<th>Wednesday</th>
            <th style="background-color: lightpink;">Thursday</th>
            <th>Friday</th>
		</tr>
		<tr>
			<td bgcolor="lightpink">8-10</td>
			<td>AQLR</td>
			<td>WEB</td>
            <td>MERN</td>
            <td>Free</td>
            <td>MERN</td>
		</tr>

		<tr>
            <td bgcolor="#eec0c8">10-12</td>
			<td>Free</td>
			<td>MERN</td>
			<td>BEEE</td>
            <td>MPMC</td>
			<td>Free</td>
		</tr>

		<tr>
            <td bgcolor="lightpink">12-1</td>
			<td colspan="5" align="center" bgcolor="skyblue">LUNCH</td>
			
		</tr>
		<tr>
            <td bgcolor="#eec0c8">1-3</td>
			
			<td>BEEE</td>
			<td>MPMC</td>
			<td>WEB</td>
			<td>MERN</td>
			<td>Free</td>
		</tr>
		<tr>
            <td bgcolor="lightpink">3-5</td>
			<td>MERN</td>
			<td>DS</td>
			<td>Free</td>
			<td>Free</td>
			<td>WEB</td>
		</tr>
	</table>
    <br>
    <table border='3' cellspacing="4" cellpadding='4' style="width: 50%;">
		<tr bgcolor="lightcoral">
			<th>S.NO</th>
			<th>Subject code</th>
			<th>Subject Name</th>
			
		</tr>
		<tr>
			<td>1.</td>
			<td>19AI414</td>
            <td>Fundamentals of Web Apllication Development</td>
		</tr>

		<tr>
            <td>2.</td>
			<td>19AI512C</td>
            <td>MERN Full Stack</td>
		</tr>

		<tr>
            <td>3.</td>
			<td>19PH206</td>
            <td>Microprocessor and Microcontroller(MPMC)</td>
			
		</tr>
		<tr>
            <td>4.</td>
			<td>19EE305</td>
            <td>Basic Electrical, Electronics Engineering(BEEE)</td>
		</tr>
		<tr>
            <td>5.</td>
			<td>19AI403</td>
            <td>Introduction to Data Science(DS)</td>
		</tr>
        <tr>
            <td>6.</td>
			<td>19EY704</td>
            <td>Advanced Quantitative and Logical Reasoning(AQLR)</td>
		</tr>
	</table>
</body>
</html>
```
## OUTPUT
![Screenshot 2024-04-04 182336](https://github.com/ThangaDeepika/slot/assets/125663099/8c5dde60-b9e7-43b0-8d46-74cebf409998)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
