# Ex03 Time Table
# Date:25/11/2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
    <head>
        <title>timetable</title>
        <style>
            th {
                background-color:beige;
                color:black;
            }
            td{
                background-color:rgba(245, 245, 245, 0.811);
                color: black;
                text-align: center;
                border: 5px black;
                padding: 10px;
                border-style:inset;
                

            }
            body {
               background-image: url(https://img.freepik.com/premium-photo/abstract-hexagon-pattern-with-neon-lights_110373-9070.jpg?semt=ais_incoming&w=740&q=80);
               background-repeat: no-repeat;
               background-size: cover;
            }
            caption {
                color:rgb(255, 242, 0);
                font-weight: bold;
                font-size:larger;
                font-display: block;
                font-size-adjust: inherit;

            }

        </style>
    <body>
        <center>
        <img src="https://github.com/dr-pvijayan/slot_timetable/blob/main/logo.png?raw=true" height="100px" width="750px">
        </center>
    </body>
    <body>
        <center>
        <table>
            <caption> SLOT TIME TABLE - JEEVAAPRIYAN M (25011749)</caption>
            <tr>
                <th style="background-color:rgb(0, 255, 242);">Day/Time</th>
                <th style="background-color:rgb(0, 255, 242);">Monday</th>
                <th style="background-color:rgb(0, 255, 242);">Tuesday</th>
                <th style="background-color:rgb(0, 255, 242);">Wednesday</th>
                <th style="background-color:rgb(0, 255, 242);">Thursday</th>
                <th style="background-color:rgb(0, 255, 242);">Friday</th>
                <th style="background-color:rgb(0, 255, 242);">Saturday</th>
            </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">8-10</td>
                <td colspan="3">Fundamentals of WEB application</td>
                <td colspan="2">Introduction to ML</td>
                <td>FREE</td>
             </tr>
             <tr>
                 <td style="background-color:rgb(0, 255, 242);">10-12</td>
                 <td>FREE</td>
                 <td colspan="2">Introduction to ML</td>
                 <td>English</td>
                 <td colspan="2">FREE</td>
             </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">1-3</td>
                <td>Fundamentals of WEB apllication</td>
                <td>FREE</td>
                <td>MENTOR MEET</td>
                <td>FREE</td>
                <td>Fundamentals of WEB apllication</td>
                <td>Introduction to ML</td>
             </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">3-5</td>
                <td>ENGLISH</td>
                <td>FREE</td>
                <td>ENGLISH</td>
                <td colspan="2">FREE</td>
                <td>ENGLISH</td>
             </tr>
        </table>
        </center>
        <center>
        <table>
            <caption>TimeTable</caption>
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">1</td>
                <td>19AI414</td>
                <td>Fundamental of WEB application Development(FWAD)</td>
             </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">2</td>
                <td>19AI410</td>
                <td>Introduction to Machinne Learning (ML)</td>
             </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">3</td>
                <td>19EN101</td>
                <td>Communicative English</td>
             </tr>
             <tr>
                <td  style="background-color:rgb(0, 255, 242);">4</td>
                <td>ECA-M</td>
                <td>Mentor Meet</td>
             </tr>
        </table>
        </center>

    </body>
</html><html>
    <head>
        <title>timetable</title>
        <style>
            th {
                background-color:beige;
                color:black;
            }
            td{
                background-color:rgba(245, 245, 245, 0.811);
                color: black;
                text-align: center;
                border: 5px black;
                padding: 10px;
                border-style:inset;
                

            }
            body {
               background-image: url(https://img.freepik.com/premium-photo/abstract-hexagon-pattern-with-neon-lights_110373-9070.jpg?semt=ais_incoming&w=740&q=80);
               background-repeat: no-repeat;
               background-size: cover;
            }
            caption {
                color:rgb(255, 242, 0);
                font-weight: bold;
                font-size:larger;
                font-display: block;
                font-size-adjust: inherit;

            }

        </style>
    <body>
        <center>
        <img src="https://github.com/dr-pvijayan/slot_timetable/blob/main/logo.png?raw=true" height="100px" width="750px">
        </center>
    </body>
    <body>
        <center>
        <table>
            <caption> SLOT TIME TABLE - JEEVAAPRIYAN M (25011749)</caption>
            <tr>
                <th style="background-color:rgb(0, 255, 242);">Day/Time</th>
                <th style="background-color:rgb(0, 255, 242);">Monday</th>
                <th style="background-color:rgb(0, 255, 242);">Tuesday</th>
                <th style="background-color:rgb(0, 255, 242);">Wednesday</th>
                <th style="background-color:rgb(0, 255, 242);">Thursday</th>
                <th style="background-color:rgb(0, 255, 242);">Friday</th>
                <th style="background-color:rgb(0, 255, 242);">Saturday</th>
            </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">8-10</td>
                <td colspan="3">Fundamentals of WEB application</td>
                <td colspan="2">Introduction to ML</td>
                <td>FREE</td>
             </tr>
             <tr>
                 <td style="background-color:rgb(0, 255, 242);">10-12</td>
                 <td>FREE</td>
                 <td colspan="2">Introduction to ML</td>
                 <td>English</td>
                 <td colspan="2">FREE</td>
             </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">1-3</td>
                <td>Fundamentals of WEB apllication</td>
                <td>FREE</td>
                <td>MENTOR MEET</td>
                <td>FREE</td>
                <td>Fundamentals of WEB apllication</td>
                <td>Introduction to ML</td>
             </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">3-5</td>
                <td>ENGLISH</td>
                <td>FREE</td>
                <td>ENGLISH</td>
                <td colspan="2">FREE</td>
                <td>ENGLISH</td>
             </tr>
        </table>
        </center>
        <center>
        <table>
            <caption>TimeTable</caption>
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">1</td>
                <td>19AI414</td>
                <td>Fundamental of WEB application Development(FWAD)</td>
             </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">2</td>
                <td>19AI410</td>
                <td>Introduction to Machinne Learning (ML)</td>
             </tr>
             <tr>
                <td style="background-color:rgb(0, 255, 242);">3</td>
                <td>19EN101</td>
                <td>Communicative English</td>
             </tr>
             <tr>
                <td  style="background-color:rgb(0, 255, 242);">4</td>
                <td>ECA-M</td>
                <td>Mentor Meet</td>
             </tr>
        </table>
        </center>

    </body>
</html>
```
# OUTPUT

![alt text](<Screenshot (119).png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
