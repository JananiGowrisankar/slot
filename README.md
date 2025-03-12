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
    <body>
        <center>
        <a href="https://saveetha.ac.in/">
        <img src="logo.png" width="500" height="100">
        </a>
        </center>
        <br>
    <table align="center" border="2"cellspacing="1"cellpadding="5">
    <caption>Timetable Janani(212224100022)</caption>
    <tr bgcolor="cyan">
        <th>Day</th>
        <th>8-10</th>
        <th>10-12</th>
        <th>1-3</th>
        <th>3-5</th>
    </tr>
    <tr>
        <td bgcolor="cyan">Monday</td>
        <td bgcolor="red">WEB</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="yellow">AI</td>
        <td bgcolor="pink">free</td>
    </tr>
    <tr>
        <td bgcolor="cyan">Tuesday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="red">WEB</td>
        <td bgcolor="yellow">AI</td>
        <td bgcolor="pink">free</td>
    </tr>
    <tr>
        <td bgcolor="cyan">Wednesday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="orange">Mentor meet</td>
        <td bgcolor="pink">free</td>
    </tr>
    <tr>
        <td bgcolor="cyan">Thursday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="yellow">AI</td>
        <td bgcolor="pink">free</td>
    </tr>
    <tr>
        <td bgcolor="cyan">Friday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="red">WEB</td>
        <td bgcolor="pink">fee</td>
        <td bgcolor="pink">free</td>
    </tr>
    <tr >
        <td bgcolor="cyan">Saturday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="pink">free</td>
    </tr>
</table>
    <table align="center" border="1">
        <tr>
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamental Web Application Development(WEB)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI302</td>
            <td>Fundamental of AI(AI)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI304</td>
            <td>Data science</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EN101</td>
            <td>Machine learning</td>
        </tr>
    </table>
</body>
</html>
```


## OUTPUT

![alt text](<Screenshot (5).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
