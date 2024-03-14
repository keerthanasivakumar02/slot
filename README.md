# Ex03 Time Table
## Date:14/03/2024

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
        <title>My Time Table</title>
    </head>
    <body>
<center>
        <img src="/static/logo.png" height="50" width="300">
        <table border="3" bgcolor="cyan">
            <caption align="center"><b>SLOT TIME - TABLE KEERTHANA(212223040092)</b></caption>
            <tr>
                <th bgcolor="purple">Day/Time</th>
                <th bgcolor="purple">Monday</th>
                <th bgcolor="purple">Tuesday</th>
                <th bgcolor="purple">Wednesday</th>
                <th bgcolor="purple">Thursday</th>
                <th bgcolor="purple">Friday</th>
                
            </tr>
            <tr>
                <th bgcolor="purple">8-10</th>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">COM ARCH</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">FWAD</td>
            </tr>
            <tr>
                <th bgcolor="purple">10-12</th>
                <td bgcolor="pink">ENGLISH</td>
                <td bgcolor="pink">COM ARCH</td>
                <td bgcolor="pink">PHY</td>
                <td bgcolor="pink">SKILLS</td>
                <td bgcolor="pink">FCP</td>
            </tr>
            <tr>
                <th bgcolor="purple">12-1</th>
                <td bgcolor="pink" colspan="5" align="center"> LUNCH</td>
                
            
            </tr>
            <tr>
                <th bgcolor="purple">1-3</th>
                <td bgcolor="pink">LOGICS</td>
                <td bgcolor="pink">FWAD</td>
                <td bgcolor="pink">ENGLISH</td>
                <td bgcolor="pink">FWAD</td>
  		<td bgcolor="pink">FREE SLOT</td>
                
            </tr>
            <tr>
                <th bgcolor="purple">3-5</th>
                <td bgcolor="pink">FCP</td>
                <td bgcolor="pink">PHY</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">OS</td>
                <td bgcolor="pink">LOGICS</td>
            </tr>

    </center>
        </table>
        <br></br>
        <table border="3">
            <tr>
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI304</td>
                <td>Fundamentals of C programming(FCP)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI414</td>
                <td>Fundamentals of web application development(FWAD)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19CS305</td>
                <td>computer architecture(COM ARCH)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EN101</td>
                <td>Fundamentals of C programming(ENGLISH)</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EY702</td>
                <td>creative skills(SKILLS)</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19MA206</td>
                <td>logics and combinatorics(LOGICS)</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19PH214</td>
                <td>physics for quantum computing(PHYSICS)</td>
            </tr>
    </body>
</html>
```


## OUTPUT
![alt text](<slot timetable fwad.png>)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
