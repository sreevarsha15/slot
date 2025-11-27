# Ex02 Time Table
## Date:27-11-15

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
    <body>
        <img src="c:\Users\acer\slot\logo.png" width="1000" height="200" title="SEC logo">
        <br><br>

        <table border="2" cellspacing="3" cellpadding="11">
            <caption><b>SLOT TIME TABLE (Sree Varsha D - 25002381)</b></caption>

            <tr bgcolor="cyan">
                <th>TIME/DAY</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>

            <tr>
                <td bgcolor="cyan">8:00-10:00</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
                <td bgcolor="lightgreen">PYTHON</td>
                <td bgcolor="lightblue">WEB</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
                <td bgcolor="lightgreen">PYTHON</td>
                <td bgcolor="lightblue">WEB</td>
            </tr>

            <tr>
                <td bgcolor="cyan">10:00-12:00</td>
                <td bgcolor="lightblue">WEB</td>
                <td bgcolor="lightblue">WEB</td>
                <td bgcolor="lightblue">WEB</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
            </tr>

            <tr bgcolor="pink">
                <td colspan="7" align="center">LUNCH</td>
            </tr>

            <tr>
                <td bgcolor="cyan">1:00-3:00</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
                <td bgcolor="lightpink">ENGLISH</td>
                <td bgcolor="lightyellow">MENTOR MEET</td>
                <td bgcolor="lightgreen">PYTHON</td>
                <td bgcolor="lightpink">ENGLISH</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
            </tr>

            <tr>
                <td bgcolor="cyan">3:00-5:00</td>
                <td bgcolor="lightgreen">PYTHON</td>
                <td bgcolor="lightgreen">PYTHON</td>
                <td bgcolor="lightpink">ENGLISH</td>
                <td bgcolor="lightpink">ENGLISH</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
                <td bgcolor="lightgrey">FREE HOUR</td>
            </tr>
        </table>

        <br><br><br>

        <table border="2" cellpadding="11" cellspacing="2">
            <tr>
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB DEVELOPMENT</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMMING</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](image-2.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
