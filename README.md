# Ex04 Time Table
## Date:21.11.26

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
<html>
     <head>
        <title>Student timetable</title>
     </head>
     <body>
    <center>
        <img src="logo.png" height ="150" width="1000">
        <h1>Student Timetable-Sangamithra.R (26001739)</h1>
        <table border ="5" bgcolor="light pink" >

        <tr bgcolor ="lightpink">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr bgcolor="powderblue">
            <th bgcolor="lightpink">8-9:30</th>
            <th>free slot</th>
            <th>CA</th>
            <th>Calculus</th>
            <th>free slot</th>
            <th>EDM</th>
            <th>calculus</th>
        </tr>

        <tr bgcolor="powderblue">
            <th bgcolor="lightpink">9:45-11:15</th>
            <th>CA</th>
            <th>PY</th>
            <th>free slot</th>
            <th>PY</th>
            <th>PY</th>
            <th>FWAD</th>
        </tr>
        <tr bgcolor="powderblue" allign="center">
            <th bgcolor="lightpink">11:15-1:15</th>
            <td colspan="10">Lunch</td>
        </tr>

        <tr bgcolor ="powderblue">
            <th bgcolor="lightpink">1:15-2:45</th>
            <th>free slot</th>
            <th>free slot</th>
            <th>free slot</th>
            <th>EDM</th>
            <th>FWAD</th>
            <th>FWAD</th>
        </tr>
        
        <tr bgcolor ="powderblue">
            <th bgcolor="lightpink">3-4:30</th>
            <th>free slot</th>
            <th>free slot</th>
            <th>free slot</th>
            <th>free slot</th>
            <th>BEEE</th>
            <th>free slot</th>
        </tr>

        </table>
    
        <br></br>

        <table border ="2">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>

            <tr>
                <th>1</th>
                <td>19CS305</td>
                <td>Computer Architecture(CA)</td>
            </tr>

            <tr>
                <th>2</th>
                <td>19AI301</td>
                <td>Python Programming(PY)</td>
            </tr>

            <tr>
                <th>3</th>
                <td>19MA201</td>
                <td>Matrix and Calculus</td>
            </tr>

            <tr>
                <th>4</th>
                <td>19AI302</td>
                <td>Engineering Design and Modelling(EDM)</td>
            </tr>

            <tr>
                <th>5</th>
                <td>19AI414</td>
                <td>Fundamentals of Web Application and Development(FWAD)</td>
            </tr>

            <tr>
                <th>6</th>
                <td>19EE305</td>
                <td>Basic Electrical, Electronics and measurement Engineering(BEEE)</td>
            </tr>

        </table>

    </center>
    </body>

</html>

## OUTPUT
![alt text](<Screenshot (43).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
