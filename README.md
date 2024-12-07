# Ex03 Time Table
# Date:11/10/2024
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
    <title>SLOT TIME TABLE</title>
    <link rel="icon" href="sec logo.jpg">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #0056b3;
            size: 1000px;

        }
        img {
            display: block;
            margin: 20px auto;
            border: 3px solid #ccc;
            border-radius: 8px;
            width: 1200px;
            height: auto;
        }
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #ff7043;
            color: white;
            text-transform: uppercase;
        }
        td {
            background-color: #e3f2fd;
        }
        td:hover {
            background-color: #bbdefb;
        }
        tr:nth-child(even) td {
            background-color: #f1f1f1;
        }
        tr:hover td {
            background-color: #ffe0b2;
        }
        .table-title {
            margin: 10px auto;
            text-align: center;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <img src="sec logo.jpg" alt="Sec Logo">
    <h1>SLOT TIME TABLE - KARTHIKRAJ C (24901034)</h1>
    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <th>8-10</th>
            <td>FREE SLOT</td>
            <td>BEEM</td>
            <td>CRYPTOCURRENCY</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>MATHS</td>
        </tr>
        <tr>
            <th>10-12</th>
            <td>CRYPTOCURRENCY</td>
            <td>MATHS</td>
            <td>BEEM</td>
            <td>CAREER DEVELOPMENT</td>
            <td colspan="2">WEB DEVELOPMENT</td>
        </tr>
        <tr>
            <th>12-1</th>
            <td colspan="6">LUNCH</td>
        </tr>
        <tr>
            <th>1-3</th>
            <td>WEB DEVELOPMENT</td>
            <td>C PROGRAMMING</td>
            <td>MENTOR MEET</td>
            <td>DIGITAL ELECTRONICS</td>
            <td>HUMAN VALUES</td>
            <td>C PROGRAMMING</td>
        </tr>
        <tr>
            <th>3-5</th>
            <td>FREE SLOT</td>
            <td>DIGITAL ELECTRONICS</td>
            <td colspan="4">FREE SLOT</td>
        </tr>
    </table>
    <h2 class="table-title">Subject Details</h2>
    <table>
        <tr>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19MA211</td>
            <td>Statistics and Numerical Methods</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19A1414</td>
            <td>Fundamentals of Web Development</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS547</td>
            <td>Fundamentals of Cryptocurrency</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EE305</td>
            <td>Basic Electrical, Electronics and Measurement Engineering</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>SH7801</td>
            <td>Human Values and Professional Ethics</td>
        </tr>
        <tr>
            <td>9.</td>
            <td>ECA-M-Scoft</td>
            <td>Mentor Meet</td>
        </tr>
    </table>
</body>
</html>
```
# OUTPUT
![image](https://github.com/user-attachments/assets/5e22594e-d3b6-4815-80f2-ece65de5d541)

![Screenshot 2024-12-07 112121](https://github.com/user-attachments/assets/790c5cd4-370a-4cc7-8089-117c22c88a66)



# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
