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
    <title>Time Table</title>
</head>

<body bgcolor="#eee6f5">
    <center>

        <img src="logo.png" width="600px">

        <h1><font color="#7a4d9f">FIRST SEM TIME TABLE - ADRIEL DENNIS M (26012668)</font></h1>

        <table border="2" cellpadding="10" bgcolor="#7a4d9f">

            <tr align="center" bgcolor="#22235f">
                <th><font color="white">Time</font></th>
                <th><font color="white">Monday</font></th>
                <th><font color="white">Tuesday</font></th>
                <th><font color="white">Wednesday</font></th>
                <th><font color="white">Thursday</font></th>
                <th><font color="white">Friday</font></th>
                <th><font color="white">Saturday</font></th>
            </tr>

            <tr align="center" bgcolor="white">
                <td>8:00AM-9:30AM</td>
                <td>PYT</td>
                <td>MATHS</td>
                <td>FWAD</td>
                <td>PYT</td>
                <td>PYT</td>
                <td>PS</td>
            </tr>

            <tr align="center" bgcolor="white">
                <td>9:45AM-11:15AM</td>
                <td>FWAD</td>
                <td>MAX</td>
                <td colspan="4">FREE SLOT</td>
            </tr>

            <tr align="center" bgcolor="white">
                <td>11:30AM-1:15PM</td>
                <td colspan="6">MENTOR MEET/LUNCH</td>
            </tr>

            <tr align="center" bgcolor="white">
                <td>1:15PM-2:45PM</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>PS</td>
                <td colspan="2">FREE SLOT</td>
            </tr>

            <tr align="center" bgcolor="white">
                <td>3:00PM-4:30PM</td>
                <td>EDM</td>
                <td>FREE SLOT</td>
                <td>CDS</td>
                <td>BEEE</td>
                <td>EDM</td>
                <td>FREE SLOT</td>
            </tr>

        </table>

        <br><br>

        <h2><font color="#7a4d9f">SUBJECT DETAILS</font></h2>

        <table border="1" cellpadding="8" bgcolor="white">

            <tr align="center" bgcolor="#22235f">
                <th><font color="white">S-NO</font></th>
                <th><font color="white">SUBJECT CODE</font></th>
                <th><font color="white">SUBJECT NAME</font></th>
            </tr>

            <tr>
                <td>1.</td>
                <td>19AI301</td>
                <td>Python Programming(PYT)</td>
            </tr>

            <tr>
                <td>2.</td>
                <td>19AI302</td>
                <td>ENGINEERING DESIGN AND MODELLING(EDM)</td>
            </tr>

            <tr>
                <td>3.</td>
                <td>19EE305</td>
                <td>BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING(BEEE)</td>
            </tr>

            <tr>
                <td>4.</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>

            <tr>
                <td>5.</td>
                <td>19MA201</td>
                <td>CALCULUS AND MATRIX ALGEBRA</td>
            </tr>

            <tr>
                <td>6.</td>
                <td>19EN105</td>
                <td>PUBLIC SPEAKING(PS)</td>
            </tr>

            <tr>
                <td>7.</td>
                <td>29EY708</td>
                <td>CAREER DEVELOPMENT SKILLS(CDS)</td>
            </tr>

            <tr>
                <td>8.</td>
                <td>ECA-M-SCOFT</td>
                <td>SCOFT MENTOR MEET</td>
            </tr>

        </table>

    </center>
</body>
</html>

```

## OUTPUT
![alt text](<adriel/adriel/Screenshot 2026-11-17 154600.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
