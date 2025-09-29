# Ex03 Time Table
## Date:27.09.2025

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
        <title>
          the sample
        </title>
        <body>
            <img scr="logo.png" height="100" widht="700">
            <table border="5" cellspacing="2" cellpadding="5" bgcolor="red">
                <caption><b>SLOT TIME TABLE  Vashmitha(25015828)</b></caption>
                <tr bgcolor="pink">
                    <th bgcolor="pink">Day/Time</th>
                    <th>Monday</th>
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thursday</th>
                    <th>Friday</th>
                    <th>Saturday</th>
                    </tr>
                <tr bgcolor="red">
                    <th bgcolor="pink">8-10</th>
                    <th aling="center">FWAD</td>
                    <td>FWAD</td>
                    <td>ENG</td>
                    <td>C PROGRAMMING</td>
                    <td>FWAD</td>
                </tr>
                <tr bgcolor="red">
                    <th bgcolor="pink">10-12</th>
                    <td>FREE SLOT</td>
                    <td>ENG</td>
                    <td>FREE</td>
                    <td>FREE SLOT</td>
                    <td>ENG</td>
                 </tr>
                    <tr bgcolor="red">
                    <th bgcolor="pink">12-1</th>
                    <td colspan="6" aling="center">LUNCH BREAK</td>
                 </tr>
                 <tr bgcolor="red">
                    <th bgcolor="pink">1-3</th>
                    <td>FWAD</td>
                    <td>FWAD</td>
                    <td>MENTOR MEET</td>
                    <td>C PROGRAM</td>
                    <td>ENG</td>
                    <td>FREE SLOT</td>
                 </tr>
                 <tr bgcolor="red">
                 <th bgcolor="pink">3-5</th>
                 <td>C PROGRAM</td>
                 <td>C PROGRAM</td>
                 <td colspan="2" aling="center">FREE SLOT</td>
                 <td>C PROGRAM</td>
                 </tr>
            </table>
            <table border="3" cellspacing="5" cellpading="10">
            <tr>
                <th><b>S.No</b>b></b></th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td aling="center">1.</td>
                <td aling="center">4L2-1</td>
                <td>Fundamental of web application development(FWAD)</td>
            </tr>
            <tr>
                <td aling="center">2.</td>
                <td aling="center">4L2-2</td>
                <td aling="center">Communicative English(ENG)</td>
            </tr>
            <tr>
                <td aling="center">3.</td>
                <td aling="center">4L3-3</td>
                <td aling="center">C program(C PROGRAM)</td>
            </tr>
            <tr>
                <td aling="center">4.</td>
                <td aling="center">ECA-M</td>
                <td aling="center">Mentor meet(MENTOR MEET)</td>
            </tr>
            </table>
        </body>
    </head>
</html>
                   
```

## OUTPUT
![alt text](<Screenshot (41).png>)
 ![alt text](<Screenshot (39).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
