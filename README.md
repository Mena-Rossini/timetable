# Experiment_Time_Table

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
<html lang="en">
    <head>
        <title>SAVEETHA ENGINEERING COLLEGE </title>
        <style>
        table{
            width: 750px;
            border-spacing: 10px;
            border: 3px solid;
        }
        td,th {
            border: 3px solid;
            padding: 10px;
        }
        </style>
    </head>
    <body>
        <img src="/static/images/logo.png" alt="saveethalogo" height="150" width ="1000"/>
         <table>
            <tr>
                <td colspan="10">Time-Table</td>
            </tr>
            <tr>
                <td colspan="5">REG NUMBER : 22002079</td>
                <td colspan="5">NAME : MENA</td>
            </tr>
            <tr>
                <td>DAYS</td>
                <td>1</td>
                <td>2</td>
                <td>3</td>
                <td>4</td>
                <td>5</td>
                <td>6</td>
                <td>7</td>
                <td>8</td>
                <td>9</td>   
            </tr>
            <tr>
                <td>MONDAY</td>
                <td>-</td>
                <td>-</td>
                <td>19AI414 - Obed Otto</td>
                <td>19AI414 - Obed Otto</td>
                <td>LUNCH</td>
                <td>19EN614-Ananda Kumar</td>
                <td>19EN614-Ananda Kumar</td>
                <td>-</td>
                <td>-</td>
                
            </tr>
            <tr>
                <td>TUESDAY</td>
                <td>19CS301-Maha Lakshimi</td>
                <td>19CS301-Maha Lakshimi</td>
                <td>-</td>
                <td>-</td>
                <td>LUNCH</td>
                <td>19AI414-Obed Otto</td>
                <td>19AI414-Obed Otto</td>
                <td>19PH205-Saveetha</td>
                <td>19PH205-Saveetha</td>
            </tr>
            <tr>
                <td>WEDNESDAY</td>
                <td>19PH205-Saveetha</td>
                <td>19PH205-Saveetha</td>
                <td>19CS301-Maha Laksmi</td>
                <td>19CS301-Maha Laksmi</td>
                <td>LUNCH</td>
                <td>19AI414-Obed Otto</td>
                <td>19AI414-Obed Otto</td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>THURSDAY</td>
                <td>19EN101-Subhashini</td>
                <td>19EN101-Subhashini</td>
                <td>19AI302-Muthu Kumar</td>
                <td>19AI302-Muthu Kumar</td>
                <td>LUNCH</td>
                <td>-</td>
                <td>-</td>
                <td>19EY701-Saranya</td>
                <td>19EY701-Saranya</td>
            </tr>
            <tr>
                <td>FRIDAY</td>
                <td>19EN614-Anand Kumar</td>
                <td>19EN614-Anand Kumar</td>
                <td>19EN101-Subhashini</td>
                <td>19EN101-Subhashini</td>
                <td>LUNCH</td>
                <td>-</td>
                <td>-</td>
                <td>19AI302-Muthu Kumar</td>
                <td>19AI302-Muthu Kumar</td>
            </tr>
        </table>


        <ol type="I">
            <li>19AI414 - Fundamentals Of Web Application Development</li>
            <li>19EN614-Japanese Basic</li>
            <li>19CS301-Problem Solving And Python Programming</li>
            <li>19PH205-Computational Physics</li>
            <li>19EN101-Communicative English</li>
            <li>19AI302-Engineering Design and Modelling</li>
            <li>19EY701-Soft Skill</li>

        </ol>
    </body>
</html>
```
# OUTPUT :
## webpage :

![timetable](https://user-images.githubusercontent.com/102855266/213179019-4b173e96-05ff-478e-a1f3-4acf989b1d37.jpg)


## html validator :

![html validator](https://user-images.githubusercontent.com/102855266/213178955-744bfe89-8290-4c1d-8d8b-86b62eba9349.jpg)


