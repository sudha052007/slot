# Ex03 Time Table
## Date:06/12/2025
## Regno:25013290

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
~~~
>>>>>>> ce5c23670092efceaf8c1633d781bb655980d468
<html>
    <body>
        <img src="logo.png" width="1000" height="200" title="SEC logo">
        <br><br>
        <table border="2" cellspacing="3" cellpadding="11">

            <caption ><b>SLOT TIME TABLE (G.sudharshini-25013290)</b></caption>
            
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
                <td bgcolor="lightgreen">PYTHON</td>
                <td bgcolor="lightred">FREE SLOT</td>
                <td bgcolor="yellow">PYTHON</td>
                <td bgcolor="lightgreen">PYTHON</td>
                <td bgcolor="lightred">FREE SLOT</td>
                <td bgcolor="yellow" >PYTHON</td>
            </tr>
            <tr>
                <td bgcolor="cyan">10:00-12:00</td>
                <td bgcolor="yellow" >FWAD</td>
                <td bgcolor="yellow" >FREE SLOT</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor=" lightgreen">PYTHON</td>
                <td bgcolor=" lightgreen">FREE SLOT</td>
                <td bgcolor=" lightgreen">FREE SLOT</td>
            </tr>
            <tr bgcolor="pink"  >
                <td colspan="7" align="center">LUNCH</td>
            </tr>
            <tr>
                <td bgcolor="cyan">1:00-2:00</td>
                <td bgcolor=" lightgreen">FWAD</td>
                <td bgcolor="orchid">FREE SLOT</td>
                <td bgcolor="red">MENTOR MEET</td>
                <td bgcolor="lightred">FWAD</td>
                <td bgcolor="orchid">FREE SLOT</td>
                <td bgcolor=" lightgreen">FREE SLOT</td>
            </tr>
            <tr>
                <td bgcolor="cyan">3:00-5:00</td>
                <td bgcolor="lightred">FREE SLOT</td>
                <td bgcolor="lightred">FREE SLOT</td>
                <td bgcolor="orchid">FWAD</td>
                <td bgcolor="orchid">FREE SLOT</td>
                <td bgcolor=" lightgreen">PYTHON</td>
                <td bgcolor=" lightgreen">FWAD</td>
            </tr>
        </table>
        <br><br><br>
        <table border="2" cellpadding="11" cellspacing="2">
            <tr >
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB DEVELOPMENT</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMMING</td>
            </tr>
        </table>
    </body>
</html>
~~~

## OUTPUT

<img width="1920" height="1020" alt="Screenshot 2025-12-11 135354" src="https://github.com/user-attachments/assets/7361a211-3786-4c5a-973e-1be801f1b227" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
