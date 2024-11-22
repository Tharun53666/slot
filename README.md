# Ex03 Time Table
## Date:19/11/2024

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

<html>
     <head>
        <title>slot timetable</title>
     </head>
    <body>
     <center>
        <img src="C:\Users\admin\slot\kani\slotapp\static\logo.png" height="100" width="540">
         </center>
     <br>
     <table align="center" width="540" cellspacing="4" border="5" bgcolor="cyan">
      <caption><b>SLOT TIME TABLE - THARRUN(24900893)</b></caption>
      <tr align="center">
        <th bgcolor="yellow">Day/time</th>
        <th bgcolor="yellow">Monday</th>
        <th bgcolor="yellow">Tuesday</th>
        <th bgcolor="yellow">Wednesday</th>
        <th bgcolor="yellow">Thursday</th>
        <th bgcolor="yellow">Friday</th>
      </tr>  
      <tr align="center">
        <th bgcolor="yellow">8-10</th>
        <td>FUNDAMENTAL OF WEB APPLICATION AND DEVELOPMENT</td>
        <td>STATISTICS</td>
        <td>FUNDAMNETALS OF C PROGRAMMING</td>
        <td>PHYSICS FOR QUANTUM COMPUTING</td>
        <td>DIGITAL ELECTRONICS</td>
      </tr>
      <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td>FREE SLOT</td>
        <td>DIGITAL ELECTRONICS</td>
        <td>PHYSICS FOR QUANTUM COMPUTING</td>
        <td>FUNDAMNETALS OF C PROGRAMMING</td>
        <td>STATISTICS</td>
      </tr>
      <tr align="center">
        <th bgcolor="yellow">12-1</th>
        <td colspan="5" align="center">LUNCH</td>
      </tr>
      <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>DIGITAL ELECTRONICS</td>
        <td>STATISTICS/td>
        <td>FREE SLOT</td>
      </tr>
      <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td> CAREER DEVELOPMENT</td>
        <td>FREE SLOT</td>
        <td>BEEE</td>
        <td>FUNDAMNETALS OF WEB APPLICATION AND DEVELOPMENT</td>
        <td>FREE SLOT</td>
      </tr>
     </table>
    <br>
<table align="center" cellspacing="2" cellspacing="4" border="2">
<tr align="center">
    <th>S.NO.</th>
    <th>subject code</th>
    <th>subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19A1304</td>
<td align="center">fundamentals of web application and development</td> 
</tr>  
<tr>
    <td align="center">1.</td>
    <td align="center">19A1305</td>
    <td align="center">career development</td> 
    </tr> 
    <tr>
        <td align="center">1.</td>
        <td align="center">19A1306</td>
        <td align="center">statistics</td> 
        </tr> 
        <tr>
            <td align="center">1.</td>
            <td align="center">19A1307</td>
            <td align="center">digital electronics</td> 
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19A1308</td>
                <td align="center">physics for quantum computing</td> 
                </tr> 
                <tr>
                    <td align="center">1.</td>
                    <td align="center">19A1309</td>
                    <td align="center">fundamentals of c programming</td> 
                    </tr> 
                    <tr>
                        <td align="center">1.</td>
                        <td align="center">19A1310</td>
                        <td align="center">BEEE</td> 
                        </tr> 
</table>  
 </body>
</html>

## OUTPUT

![alt text](<Screenshot (2)-1.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
