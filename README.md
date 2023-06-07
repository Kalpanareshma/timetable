# EX-03 Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            SEC TimeTable
        </title>
    </head>
    <body>
        <h1> timetable</h1>
        <table border="3">
            <TR bgcolor="yellow">
                <TD>Day/Time</TD>
                <TD>Monday</TD>
                <TD>Tuesday</TD>
                <TD>Wednesday</TD>
                <TD>Thursday</TD>
                <TD>Friday</TD>

            </TR>
            <TR bgcolor="cyan">
                <TD bgcolor="yellow">8-10</TD>
                <TD colspan="3" align="center">FREE SLOT</TD>
                <TD>PHY</TD>
                <TD>CHE</TD>
                
            </TR>
            <TR bgcolor="cyan">
                <TD bgcolor="yellow">10-12</TD>
                <TD>GER</TD>
                <TD>FREE SLOT</TD>
                <TD>FWAD</TD>
                <TD>FWAD</TD>
                <TD>PHY</TD>
                
            </TR>
            <TR bgcolor="cyan">
                <TD bgcolor="yellow">12-1</TD>
                <TD colspan="5" align="center">LUNCH</TD>
                
            </TR>
            <TR bgcolor="cyan">
                <TD bgcolor="yellow">1-3</TD>
                <TD colspan="2" align="center">FREE SLOT</TD>
                <TD>MAT</TD>
                <TD>MAT</TD>
                <TD>SS</TD>
                
            </TR>
            <TR bgcolor="cyan">
                <TD bgcolor="yellow">3-5</TD>
                <TD colspan="2" align="center">FREE SLOT</TD>
                <TD>GER</TD>
                <TD>CHE</TD>
                <TD>FWAD</TD>
                
            </TR>
        </table>
        </table>
             <table border="3">
            <TR>
                <TD> S.NO </TD>
                <TD>SUBJECT CODE</TD>
                <TD>SUBJECT NAME</TD>
            </TR>
            <TR>
                <TD> 1.</TD>
                <TD>19AI414</TD>
                <TD>Fundamental Of Web Development (FWAD)</TD>
            </TR>
            <TR>
                <TD> 2.</TD>
                <TD>19EN612</TD>
                <TD>German Basics (GER))</TD>
            </TR>
            <TR>
                <TD> 3.</TD>
                <TD>19PH206</TD>
                <TD>Physics (PHY)</TD>
            </TR>
            <TR>
                <TD> 4.</TD>
                <TD>19CY205</TD>
                <TD>Chemistry (CHEM)</TD>
            </TR>
            <TR>
                <TD> 5.</TD>
                <TD>19MA201</TD>
                <TD>Maths (MAT))</TD>
            </TR>
            <TR>
                <TD> 6.</TD>
                <TD>19EY701</TD>
                <TD>Soft Skills (SS)</TD>
            </TR>
        </table>
    </body>
</html>
```

# OUPUT
![image](https://user-images.githubusercontent.com/122040453/233246641-edeaa86e-cbf2-4430-b63f-d81cf1015739.png)
# RESULT
The webpage to display slot timetable has been displayed successfully.


