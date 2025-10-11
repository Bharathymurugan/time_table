# Ex03 Time Table
# Date:29.09.2025
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        table{
            border-collapse: collapse;
            margin: auto;

        }
        th, td{
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        .no-border{
            border: none;
            background-color: #F93943;
           
        }
        .border-le{
            border-left: none;
            background-color: #F93943;
        }
    
    </style>
    <title>TIME TABLE</title>
</head>
<body bgcolor="#D3C4E3">
    <center><img src="/static/logo.png" height="150px" style="border-radius: 10px;"></center>
    <center><p style="font-family: algerian;font-size: larger;">TIME TABLE</p></center>
    <table >
        <tr bgcolor="#1C0221" style="color:beige">
            <th>
                
            </th>
            <th>
                MONDAY
            </th>
            <th>
                TUESDAY
            </th>
            <th>
                WEDNESDAY
            </th>
            <th>
                THURSDAY
            </th>
            <th>
                FRIDAY
            </th>
            <th>
                SATURDAY
            </th>
        </tr>
        
        <tr>
            <td bgcolor="#1C0221" style="color:beige">
                8-10
            </td>
            <td bgcolor="#FCB0B3">
                -
            </td>
            <td bgcolor="#7B5E7B">
                Web
            </td>
            <td bgcolor="#FCB0B3">
                -
            </td>
            <td rowspan=2 bgcolor="#B15E6C">
                C
            </td>
            <td bgcolor="#DABECA">
                Public
            </td>
            <td bgcolor="#7B5E7B">
                Web
            </td>
        </tr>
        <tr>
            <td bgcolor="#1C0221" style="color:beige">
                10-12
            </td>
            <td bgcolor="#7B5E7B">
                Web
            </td>
            <td bgcolor="#FCB0B3">
                -
            </td>
            <td bgcolor="#B15E6C">
                C
            </td>
        
            <td bgcolor="#FCB0B3">
                -
            </td>
            <td bgcolor="#B15E6C">
                C
            </td>
        </tr>

        <tr>
            <td bgcolor="#1C0221" style="color:beige">
                12-1
            </td>
            <td class="no-border">

            </td>
            
            <td class="no-border">
                L
            </td>
            <td class="no-border">
                U
            </td>
            <td class="no-border">
                N
            </td>
            <td class="no-border">
                C
            </td>
            <td class="border-le" >
                H
            </td>
            
            
        </tr>

        <tr>
            <td bgcolor="#1C0221" style="color:beige">
                1-3
            </td>
            <td bgcolor="#DABECA">
                Public
            </td>
            <td bgcolor="#7B5E7B">
                Web
            </td>
            <td bgcolor="#DA4167">
                Mentor meet
            </td>
            <td bgcolor="#DABECA">
                Public
            </td>
            <td bgcolor="#7B5E7B">
                Web
            </td>
            <td rowspan="2" bgcolor="#DABECA">
                Public
            </td>
        </tr>
        <td bgcolor="#1C0221" style="color:beige">
            3-5
        </td>
        <td bgcolor="#FCB0B3">
            -
        </td>
        <td bgcolor="#DABECA">
            Public
        </td>
        <td bgcolor="#B15E6C">
            C
        </td>
        <td bgcolor="#FCB0B3">
            -
        </td>
        <td bgcolor="#FCB0B3">
            -
        </td>

    </table>

    <table style="position: absolute; top: 500px; right:35%">
        <tr>
            <th bgcolor="#1C0221" style="color:beige">
                SUBJECT CODE
            </th>
            <th bgcolor="#1C0221" style="color:beige">
                SUBJECT
            </th>
        </tr>
        <tr>
            <td bgcolor="#7B5E7B">
                19AI414
            </td>
            <td bgcolor="#7B5E7B">
                Fundamentals of Web Application development
            </td>
        </tr>
        <tr>
            <td bgcolor="#B15E6C">
                19AI304
            </td>
            <td bgcolor="#B15E6C">
                Fundamentals of C Programming
            </td>
        </tr>
        <tr>
            <td bgcolor="#DABECA">
                19EN105
            </td>
            <td bgcolor="#DABECA">
                Public speaking
            </td>
        </tr>
        <tr>
            <td bgcolor="#DA4167">
                ECA-M
            </td>
            <td bgcolor="#DA4167">
                Mentor meet
            </td>
        </tr>
    </table>
</body>
</html>
```
# OUTPUT!
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/518a7dcb-e973-45bc-aa00-2872322b751c" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
