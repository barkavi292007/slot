# Ex03 Time Table
## Date:01/12/25
## Register:25018916


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
time.html
```
<html>
    <head>
        <title>Slot timetable</title>
    </head>

    <body>
        <center>
            <img src="logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" border="5" cellspacing="2" cellpadding="4" width="540" bgcolor="Skyblue">
            <caption><b>SLOT TIME TABLE-BHARGAVI (25018916)</b></caption>
            <tr align="center">
                <th bgcolor="pink">Day/Time</th>
                <th bgcolor="pink">Monday</th>
                <th bgcolor="pink">Tuesday</th>
                <th bgcolor="pink">Wednesday</th>
                <th bgcolor="pink">Thursday</th>
                <th bgcolor="pink">Friday</th>
                <th bgcolor="pink">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="pink">8-10</th>
                <td>PYTHON PROGRAMMING</td>
                <td>FREE SLOT</td>
                <td colspan="2">PYTHON PROGRAMMING</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>PYTHON PROGRAMMING</td>
                


            
                
            </tr>
            <tr align="center">
                <th bgcolor="pink">10-12</th>
                <td>FWAD</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>FREE SLOT</td>
                <td>PYTHON PROGRAMMING</td>
                <td colspan="2">FREE SLOT</td>
                



        
            </tr>
            <tr align="center">
                <th bgcolor="pink">12-1</th>
                <td colspan="6">L U N C H</td>

            </tr>
            <tr align="center">
                <th bgcolor="pink">1-3</th>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>MENTOR MEET</td>
                <td>FWAD</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>FREE SLOT</td>

                

            </tr>
            <tr align="center">
                <th bgcolor="pink">3-5</th>
                <td>COMMUNICATE ENGLISH</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>COMMUNICATE ENGLISH</td>
                <td>PYTHON PROGRAMMING</td>
                <td>FWAD</td>                
            </tr>
        </table>
        <br>
        <table align="center" border="5" cellspacing="2" cellpadding="4" width="540">
            <tr align="center">
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
                
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            

            </tr>
            <tr>
                <td>2</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMMING</td>
            </tr>

            
 
        </table>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (16).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
