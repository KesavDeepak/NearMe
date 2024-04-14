# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
``` python

Developed by :KESAV DEEPAK SRIDHARAN
Register Number :212223230104
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            background-color: aqua;
        }
        
    </style>
</head>
<body>
    <img src="d2.png" alt="" height = "530" usemap = "#MapNew" onmousemove = "coordinate(event)">
    <map name="MapNew">
        <area shape="RECT" coords="214,177,240,204" href="https://www.careerindia.com/colleges/c-t-m-college-of-arts-and-science-chennai-tamil-nadu-cp2816/" alt="ctm college">
        <area shape="RECT" coords="339,211,367,246" href="https://www.sreesasthaarts.in/" alt="sree sasthaa">
        <area shape="rect" coords="221,296,230,319" href="https://dmice.ac.in/" alt="dmice">
        <area shape="rect" coords="40,213,64,239" href="https://www.apolloartsandsciencecollegechennai.ac.in/about.aspx" alt="apollo arts and science">
        <area shape="rect" coords="190,453,216,473" href="https://lakeviewlifecentre.org/" alt="lakeview">
    </map><br>
    
    
   
</body>
</html>
```
## OUTPUT
![alt text](map.png)
![alt text](ctm.png)
![alt text](apollo.png)
![alt text](<sree sastha.png>)
![alt text](lakeview.png)
![alt text](dmi.png)
## RESULT
The program for implementing image maps using HTML is executed successfully.
