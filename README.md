# Ex03 Time Table
## Date:14/11/2023

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
<html>
    <title> image map </title>
     <body>
          <center>
           <img src="/static/logo.png"  
           height="150" width="500">
          </center>
          <table border="5" cellspacing="10" cellspacing="5">
            <caption="centre"> SLOT TIME TABLE-Bakkiyalakshmi E (23013603) </caption>
           <bgcolor="pink">
             <tr>
                 <th bgcolor="yellow">Day/Time</th>
                 <th bgcolor="cyan">8-9 am</th>
                 <th bgcolor="cyan">9-10 am</th>
                 <th bgcolor="cyan">10-11 am</th>
                 <th bgcolor="cyan">11-12 am</th>
                 <th bgcolor="cyan">12-1 pm</th>
                 <th bgcolor="cyan">1-2 pm</th>
                 <th bgcolor="cyan">2-3 pm</th>
                 <th bgcolor="cyan">3-4 pm</th>
                 <th bgcolor="cyan">4-5 pm</th>

             </tr>
             <tr>
                 <th bgcolor="yellow">Monday</th>
                 <td bgcolor="green">communicative english</td>          
                 <td bgcolor="green">communicative english</td>
                 <td bgcolor="red">Free</td>
                 <td bgcolor="red">Free</td>          
                 <td bgcolor="green">Lunch</td>          
                 <td bgcolor="green">Calculus and matrix</td>          
                 <td bgcolor="green">Calculas and matrix</td>
                 <td bgcolor="red">Free</td>
                 <td bgcolor="red">Free</td>                    
              </tr>
              <tr>
                 <th bgcolor="yellow">Tuesday</th>
                 <td bgcolor="green">Communicate English</td>             
                 <td bgcolor="green">Communicate English</td>
                 <td bgcolor="green">Calculus and matrix</td>             
                 <td bgcolor="green">Calculus and matrix</td>             
                 <td bgcolor="green">Lunch</td>             
                 <td bgcolor="green">Engineering Design and Modelling</td>             
                 <td bgcolor="green">Engineering Design and Modelling</td>             
                 <td bgcolor="green">Physics</td>
                 <td bgcolor="red">Free</td>                          
              </tr>
              <tr>
                 <th bgcolor="yellow">Wednesday</th>
                 <td bgcolor="green">Web</td>          		
                 <td bgcolor="green">Web</td>
                 <td bgcolor="green">Computer Architecture</td>
                 <td bgcolor="green">Computer Architecture</td>
                 <td bgcolor="green">Lunch</td>
                 <td bgcolor="red">Free</td>
                 <td bgcolor="red">Free</td>
                 <td bgcolor="red">Free</td>
                 <td bgcolor="red">Free</td>                                                                                 
              </tr>
              <tr>
                 <th bgcolor="yellow">Thurday</th>
                 <td bgcolor="green">Engineering Design and Modelling</td>
                 <td bgcolor="green">Engineering Design and Modelling</td>
                 <td bgcolor="green">Web</td> 
                 <td bgcolor="green">Web</td> 
                 <td bgcolor="green">Lunch</td> 
                 <td bgcolor="green">Physics</td> 
                 <td bgcolor="green">Physics</td> 
                 <td bgcolor="green">Phython</td> 
                 <td bgcolor="green">Phython</td>  
              </tr>
                  <th bgcolor="yellow">Friday</th>
                  <td bgcolor="red">Free</td>
                  <td bgcolor="red">Free</td>
                  <td bgcolor="green">Computer architecture</td>
                  <td bgcolor="green">Free</td>
                  <td bgcolor="green">Lunch</td>
                  <td bgcolor="green">Web</td>
                  <td bgcolor="green">Web</td>
                  <td bgcolor="green">Phython</td>
                  <td bgcolor="green">Phython</td>
              </tr>
             </table border>
   <br>
          <table border="3" cellspacing="1" cellspacing="2">
              <tr>
                 <th>S.no</th>
                 <th>Subject Code</th>
                 <th>Subject Name</th>
               </tr>
               <tr>
                 <th>1</th>
                 <td>22HS101</td>
                 <td>Heritage of Tamil</td>
               </tr>
               <tr>
                 <th>2</th>
                 <td>19AI414</td>
                 <td>Fundamental of Web Application</td>
               </tr>
               <tr>
                 <th>3</th>
                 <td>19A1302</td>
                 <td>Engineering Design and Modelling</td>
               </tr>
               <tr>
                 <th>4</th>
                 <td>19CS305</td>
                 <td>Computer Architecture</td>
               </tr>
               <tr>
                 <th>5</th>
                 <td>19EN101</td>
                 <td>Communicative Communication</td>
               </tr>
               <tr>
                 <th>6</th>
                 <td>19MA201</td>
                 <td>Calculus and Matrix</td>
                </tr>
               <tr> 
                 <th>7</th>
                 <td>19PH214</td>
                 <td>Physics</td>
                </tr>
                <tr>
                 <th>8</th>
                 <td>19AI301</td>
                 <td>Phython</td>
                </tr> 
       </body>
</html>              	                    
```

## OUTPUT
![Alt text](<Screenshot (2).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
