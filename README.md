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
    <head>
        <title>My Time Table</title>
    </head>
    <body>
    <center>
        <img src="logo.png" height="200" width="1000">
    </center>
    <br>
        <table align="center" border="2" cellspacing="8" cellsspadding="5" width="50" height="50">
        <caption>Slot Time Table-Gokul C(23014093)</caption>
        <tr>
            <th align ="center"></th>
            <th bgcolor="red">Day/Time</th>
            <th bgcolor="red">Monday</th>
            <th bgcolor="red">Tuesday</th>
            <th bgcolor="red">Wednesday</th>
            <th bgcolor="red">Thursday</th>
            <th bgcolor="red">Friday</th>
            <th bgcolor="red">Saturday</th>
        </tr>
        <tr>
            <th align ="center"></th>
            <td bgcolor="red">8:00 to 10:00</td>
            <td bgcolor="blue">Free</td>
            <td bgcolor="blue">Free</td>
            <td bgcolor="green">PLA</td>
            <td bgcolor="blue">Free</td>
            <td bgcolor="orange">Web</td>
            <td bgcolor="blue">Free</td>
        </tr>
        <tr>
            <th align ="center"></th>
            <td bgcolor="red">10:00 to 12:00</td>
            <td bgcolor="blue">Free</td>
            <td bgcolor="green">PLA</td>
            <td bgcolor="blue">Free</td>
            <td bgcolor="blue">Free</td>
            <td bgcolor="pink">ML</td>
            <td bgcolor="blue">Free</td>
        </tr>
        <tr>
            <th align ="center"></th>
            <td bgcolor="red">12:00 to 1:00</td>
            <td colspan="6" bgcolor="indigo">Lunch Time</td>
        </tr>
        <tr>
            <th align ="center"></th>
            <td bgcolor="red">1:00 to 3:00</td>
            <td bgcolor="green">PLA</td>
            <td bgcolor="orange">Web</td>
            <td bgcolor="purple">Eng</td>
            <td bgcolor="orange">Web</td>
            <td bgcolor="gold">CN</td>
            <td bgcolor="gray">SS</td>
        </tr>
        <tr>
            <th align ="center"></th>
            <td bgcolor="red">3:00 to 5:00</td>
            <td bgcolor="blue">Free</td>
            <td bgcolor="pink">ML</td>
            <td bgcolor="gold">CN</td>
            <td bgcolor="blue">Free</td>
            <td bgcolor="purple">Eng</td>
            <td bgcolor="green">PLA</td>
        </tr>
        </table>
    </br>
    <br>
        <table align="center" cellspacing="4" cellsspadding="8" border="4">

            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI301C</td>
                <td>Python Linear Algebra</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CS406</td>
                <td>Computer Networks</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY701</td>
                <td>Soft Skills</td>
            </tr>
        </table>
    </br>
    </body>
</html>
```


## OUTPUT

![Screenshot 2024-03-14 203137](https://github.com/Gokul1410/slot/assets/153058321/13e36550-fb9b-487d-b65f-c2bf1bdf3f00)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
