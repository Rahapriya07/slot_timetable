# Ex03 Time Table
## Date:21-09-25

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
  <title>Weekly Timetable</title>
</head>
<body>
    <center>
         <img src="/static/logo.png" height="100" width="540">
    </center>
  <h2>Weekly Timetable</h2>
  <table border="1" cellpadding="8" cellspacing="0">
    <tr>
      <th>Day / Time</th>
      <th>8 - 10</th>
      <th>10 - 12</th>
      <th>1 - 3</th>
      <th>3 - 5</th>
    </tr>
    <tr>
      <td>MONDAY</td>
      <td>STATISTICS AND NUMERICAL METHODS<br>4X6 - 8</td>
      <td>SOFTWARE ENGINEERING<br>414 - 2</td>
      <td>FWAD<br>4X1 - 2</td>
      <td>FREE </td>
    </tr>
    <tr>
      <td>TUESDAY</td>
      <td>COMPUTER NETWORKS<br>4R3 - 2</td>
      <td>ADVANCE C<br>4K1 - 2</td>
      <td>FREE</td>
      <td>HUMAN VALUES<br>2X2 - H2</td>
    </tr>
    <tr>
      <td>WEDNESDAY</td>
      <td>FREE</td>
      <td>FWAD</td>
      <td>MENTOR MEET</td>
      <td>FREE</td>
    </tr>
    <tr>
      <td>THURSDAY</td>
      <td>FREE</td>
      <td>STOCK MARKET<br>3Z3 - 1</td>
      <td>QAI<br>2H1 - 8</td>
      <td>COMPUTER NETWORKS</td>
    </tr>
    <tr>
      <td>FRIDAY</td>
      <td>ADVANCE C</td>
      <td>FREE</td>
      <td>SOFTWARE ENGINEERING</td>
      <td>STATISTICS AND NUMERICAL METHODS</td>
    </tr>
    <tr>
      <td>SATURDAY</td>
      <td>STOCK MARKET<br>3Z3 - 1</td>
      <td>FREE</td>
      <td>FREE</td>
      <td>FREE</td>
    </tr>
  </table>
</body>
</html>
```


## OUTPUT
![alt text](<Screenshot (184)-1.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
