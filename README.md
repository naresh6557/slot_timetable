# Ex03 Time Table
## Date:21.04.2025

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

```python

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE</title>
    <center>
    <img src="C:\Users\admin\Downloads\sec-logo-01as.png" width="1500" height="200">
    </center>
    <title>TIME TABLE</title>
    <center>
    <h3> SLOT TIME TABLE - Nikshitha S(24900161)</h3>    
    </center>
    </head>    
    <style>
        body{
            font-family:
    Arial,sans-serif;
          margin:0
          padding:0
            background-colour: antiquewhite;
            border;2px solid 
        }
        table{
            border-collapse: collapse;
            margin: 20px  auto;
            background-color: rgb(112, 78, 224);
                 solid
            box-shadow: 0;
        }
        td{
            border: 20px
        solid
            padding:10px;
            text-align:
        }
    </style>
<table border="1" width="50%" height="25%" style="text-align: center;">
    <tr  style="background-color:rgb(112, 78, 224);text-align: center">
    <th>Day/Time</th>
    <th> 8-10 </th>
    <th> 10-12 </th>
    <th> 12-1 </th>
    <th> 1-2 </th>
    <th> 3-5 </th>
    </tr>
    <tr> 
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Monday</th>
        <td style="background-color:rgb(228, 30, 156);">OS</td> 
        <td style="background-color:rgb(228, 30, 156);"> RA</td>
        <td style="background-color:rgb(228, 30, 156);"> Lunch </td>
        <td style="background-color:rgb(228, 30, 156);"> DE</td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
    </tr>
    <tr>
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Tuesday</th>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
        <td style="background-color:rgb(228, 30, 156);"> ESS </td>
        <td style="background-color:rgb(228, 30, 156) ;"> Lunch </td>
        <td style="background-color:rgb(228, 30, 156);"> CDS </td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
    </tr>
    <tr>
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Wesdnesday</th>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
        <td style="background-color:rgb(228, 30, 156);"> DE </td>
        <td style="background-color:rgb(228, 30, 156);"> Lunch </td>
        <td style="background-color:rgb(228, 30, 156);"> Mentor Meet </td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
    </tr>  
    <tr>
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Thrusady</th>
        <td style="background-color:rgb(228, 30, 156);"> OS </td>
        <td style="background-color:rgb(228, 30, 156);"> Advance C </td>
        <td style="background-color:rgb(228, 30, 156);"> Lunch </td>
        <td style="background-color:rgb(228, 30, 156);"> CN </td>
        <td style="background-color:rgb(228, 30, 156);"> Web </td>
    </tr>
    <tr>
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Friday</th>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
        <td style="background-color:rgb(228, 30, 156);"> Web </td>
        <td style="background-color: rgb(228, 30, 156);"> Lunch </td>
        <td style="background-color: rgb(228, 30, 156);"> CN </td>
        <td style="background-color: rgb(228, 30, 156);"> Free slot </td>
    </tr>
    <tr>
        <th style="background-color: rgb(112, 78, 224);text-align: center;"></thstyle>Saturday</th>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>Free slot</td>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>Advance C</td>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>Lunch</td>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>Free slot</td>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>Free slot</td>
    </tr>    
</table>
</head>
<body>
<table border="4px" width="300" height="400" style="background-color:burlywood; text-align: center;">
        <tr>
            <th> S.NO </th>
            <th> Subject Name </th>
            <th> Subject Code </th>
        </tr>
        <tr>
            <th> 1. </th>
            <td> Fundamentals of web applications </td>
            <td> 19AI414 </td>
        </tr>
        <tr>
            <th> 2. </th>
            <td> Reasoning Ability </td>
            <td> 19EE404 </td>
        </tr>
        <tr>
            <th> 3. </th>
            <td> Career Development Skills </td>
            <td> 19EY708 </td>
        </tr>
        <tr>
            <th> 4. </th>
            <td> Digital Electronics</td> </td>
            <td> 19EE404 </td>
        </tr>
        <tr>
            <th> 5. </th>
            <td> ESS</td>
            <td> 19CY801 </td>
         </tr>   
         <tr>
            <th> 6. </th>
            <td>CN</td>
            <td> 19CS406 </td>
         </tr>
         <tr>
            <th> 7. </th>
            <td>OS</td>
            <td> 19CS405 </td>
         </tr>   
         <tr>
            <th> 8. </th>
            <td>Advanced C</td>
            <td> 19AI305 </td>
         </tr>
</table>
</body>
</html>
```

## OUTPUT

![nikshi time table](https://github.com/user-attachments/assets/22ea2895-3c93-4463-a1f2-38b5e6527654)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
