# Ex03 Time Table
## Date:28.04.25

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
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE - MOULIDHAR (212223240042)</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
    </style>
</head>
<body>
    <img src="logo.png">
    <div class="center-text">
        <p><strong>SLOT TIME TABLE - MOULIDHAR (212223240042) </strong></p>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Yellow">Day/Time</th>
            <th colspan="1" bgcolor="Yellow">Monday</th>
            <th colspan="1" bgcolor="Yellow">Tuesday</th>
            <th colspan="1" bgcolor="Yellow">Wednesday</th>
            <th colspan="1" bgcolor="Yellow">Thursday</th>
            <th colspan="1" bgcolor="Yellow">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">8-10</th>
            <th colspan="3" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">PHY</th>
            <th colspan="1" bgcolor="Cyan">CHE</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">GER</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">PHY</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="5" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
            <th colspan="1" bgcolor="Cyan">MAT</th>
            <th colspan="1" bgcolor="Cyan">SS</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">3-5</th>
            <th colspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">GER</th>
            <th colspan="1" bgcolor="Cyan">CHE</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI41</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19EN612</th>
            <th colspan="2" bgcolor="White">German Basic (GER)</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19PH206</th>
            <th colspan="2" bgcolor="White">Physics for Information Technology (PHY)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19CY205</th>
            <th colspan="2" bgcolor="White">Principles of Chemistry in Engineering (CHE)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19MA201</th>
            <th colspan="2" bgcolor="White">Calculus and Matrix Algebra (MAT)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19EY701</th>
            <th colspan="2" bgcolor="White">Soft Skills (SS)</th> 
        </tr>
    </table>
</body>
</html>
```


## OUTPUT
![IMAGE](https://github.com/moulidharyadav/slot/assets/147078316/4ec4776c-b353-423a-b3d7-4a5cc93ad18d)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
