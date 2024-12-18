# Ex03 Time Table
## Date:15-11-2024

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

<center>
    <img src="logo.png" height="200" width="1000" >
</center>
<center>
<table border="2">
    <center>
        <h1>SLOT TIMETABLE:SUSHMITHA GEMBUNATHAN(24001544)</h1>
    </center>
    <tr bgcolor="#fbff00">
        <th>TIME/DAY</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>
    <tr bgcolor="#33ffbe">
      <th>8-10</th>
      <td>Free Slot</td>
      <td>Web</td>
      <td>Python Prog</td>
      <td>German</td>
      <td>Calculus</td>
      <td colspan="2">Free slot</td>
    </tr>
    <tr bgcolor="#33ffbe">
       <th>10-12</th>
       <td>Python Prog</td>
       <td>German</td>
       <td>Human Values</td>
       <td>English</td>
       <td>German</td>
       <td>Calculus</td>
    </tr>
    <tr bgcolor="#33ffbe">
       <th>1-3</th>
       <td>Chemistry</td>
       <td>English</td>
       <td>Mentor Meet</td>
       <td>Chemistry</td>
       <td>Web</td>
       <td>Web</td>
    </tr>
    </table>
    <table border="2">
        <tr bgcolor="#fbff00">
            <th>S.no</th>
            <th>Couse code</th>
            <th>Course name</th>
        </tr>
        <tr bgcolor="#33ffbe">
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION</td>
        </tr>
        <tr bgcolor="#33ffbe">
            <td>2</td>
            <td>SH5605</td>
            <td>GERMAN LANGUAGE A1</td>
        </tr>
        <tr bgcolor="#33ffbe">
            <td>3</td>
            <td>19EN101</td>
            <td>COMMUNICATIVE ENGLISH</td>
        </tr>
        <tr bgcolor="#33ffbe">
            <td>4</td>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING</td>
        </tr>
        <tr bgcolor="#33ffbe">
            <td>5</td>
            <td>19MA201</td>
            <td>CALCULUS AND MATRIX ALGEBRA</td>
        </tr>
        <tr bgcolor="#33ffbe">
            <td>6</td>
            <td>19CY205</td>
            <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        </tr>
        <tr bgcolor="#33ffbe">
            <td>7</td>
            <td>SH7801</td>
            <td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
        </tr>
    </table>
</center>

```

## OUTPUT
![alt text](<Screenshot 2024-11-16 082429.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
