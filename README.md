# Ex03 Places Around Me
## Date: 10.02.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title>My Place</title>
    </head>
    <body>
        <h1 align="center">Puzhal-Chennai</h1>
        <h3 align="center">Harini M 25001011</h3>
        <img src="Map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Puzhal Gym" title="Puzhal Gym" href="Gym.html" coords="643,205,928,99" shape="rect">
    <area target="" alt="ID Mahal" title="ID Mahal" href="Mahal.html" coords="425,137,98" shape="circle">
    <area target="" alt="Jain School" title="Jain School" href="School.html" coords="1133,354,1308,352,1306,441,1141,444,1071,412" shape="poly">
    <area target="" alt="J Club" title="J Club" href="Club.html" coords="1247,149,1084,219" shape="rect">
    <area target="" alt="Police Station" title="Police Station" href="Station.html" coords="521,661,97" shape="circle">
</map>
<map>

</map>

        
    </body>
</html>

Gym.html

<html>
    <head>
        <title>Puzhal Gym</title>
    </head>
    <body bgcolor="red">
         <h1 align="center">Puzhal-Chennai</h1>
        <h3 align="center">Harini M 25001011</h3>
        <h4>Unique Sportz Lifestyle & Fitness Studio in Puzhal is a premier 8,500 sq. ft. facility offering spacious, two-floor workout areas with high-tech cardio and strength machines.
             It features certified trainers providing personalized coaching in CrossFit and Zumba to help members achieve their body transformation goals. 
             Located on Gandhi Main Road, this unisex gym is highly rated for its clean, motivating, and professional environment. </h4>
    </body>
</html>

Mahal.html

<html>
    <head>
        <title> ID Mahal</title>
    </head>
    <body bgcolor="cyan">
       <h1 align="center">Puzhal-Chennai</h1>
        <h3 align="center">Harini M 25001011</h3> 
        <h4>ID Mahal is an air-conditioned, budget-friendly banquet hall located in Puzhal, Chennai, ideal for weddings, receptions, and small family functions. 
            It features a modern, pillarless design with a floating capacity of up to 200-300 people, along with a separate dining area and parking. 
            The venue permits outside decor and is well-regarded for hosting various events near Redhills. </h4>
        
    </body>
</html>

School.html

<html>
    <head>
        <title>Jain School</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">Puzhal-Chennai</h1>
        <h3 align="center">Harini M 25001011</h3>
        <h4>Jain Vidyaashram in Puzhal, Chennai, established in 1996, is a renowned co-educational senior secondary school affiliated with CBSE, focusing on holistic education, moral values, and academic excellence.
             Situated on a spacious campus, it provides a nurturing environment for students from Nursery to Class XII, combining modern learning with traditional Indian culture</h4>
        
    </body>
</html>

Club.html

<html>
    <head>
        <title>J Club</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">Puzhal-Chennai</h1>
        <h3 align="center">Harini M 25001011</h3>
        <h4>J Club in Puzhal, Chennai, established around 2022-2024, is a premier recreational hub offering a blend of luxury and leisure, including a well-maintained swimming pool, high-end badminton courts, and a kids' zone. 
            It features a restaurant, cafe, and a popular restobar, making it a versatile destination for dining and entertainment.</h4>
        
    </body>
</html>

Station.html

<html>
    <head>
        <title>Puzhal M3 Police Staion</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">Puzhal-Chennai</h1>
        <h3 align="center">Harini M 25001011</h3>
        <h4>The M3 Puzhal Police Station is located near the Puzhal Camp on the Chennai-Kolkata National Highway (NH 16), operating 24/7 to serve the local community.
             As part of the Madhavaram Police Sub-division, it handles law and order in the area surrounding the Puzhal Central Jail. </h4>
        
    </body>
</html>

```
## OUTPUT
![alt text](<Web Map.png>)
![alt text](<Puzhal Gym.png>)
![alt text](<ID Mahal.png>)
![alt text](<Jain School.png>)
![alt text](<J Club.png>)
![alt text](<Police Station.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
