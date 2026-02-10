# Ex03 Places Around Me
## Date:10/2/2026

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
map.html

<html>
    <head>
        <title>Mapping</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">Vijayawada</h1>
        <h2 align="center">Popuri Sahithya(25004681)</h2>
        <img src="Screenshot 2025-11-26 113600.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Alankar Theatre" title="Alankar Theatre" href="theatre.html" coords="489,205,656,258" shape="rect">
    <area target="" alt="Andhra Hospital" title="Andhra Hospital" href="hospital.html" coords="1034,541,116" shape="circle">
    <area target="" alt="Bapu Museum" title="Bapu Museum" href="museum.html" coords="770,637,600,762,907,766" shape="poly">
    <area target="" alt="Railway Station" title="Railway Station" href="station.html" coords="47,39,262,115" shape="rect">
    <area target="" alt="Durga Devi Temple" title="Durga Devi Temple" href="temple.html" coords="1238,106,104" shape="circle">
</map>
    </body>
</html>

temple.html

<html>
    <head>
        <title>Temple</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">Vijayawada-AP</h1>
        <h2 align="center">Kanaka Durga Temple</h2>
        <hr size="4" color="black">
        <p><b>The Kanaka Durga Temple is a famous Hindu temple dedicated to Goddess Durga, located on the Indrakeeladri hill in Vijayawada, Andhra Pradesh. It is one of India's most revered spiritual sites, situated on the banks of the Krishna River</b></p>
    </body>
</html>

station.html

<html>
    <head>
        <title>Railway Station</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">Vijayawada-AP</h1>
        <h2 align="center">Railway Station</h2>
        <hr size="4" color="black">
        <p><b>Vijayawada railway station is a major junction in South India, known for its efficiency, strategic importance, and high passenger traffic. It is the fourth busiest railway station in the country and features 10 platforms. The station is also notable for its accessibility features and a high volume of passengers, making it a crucial transportation hub for the region</b></p>
    </body>
</html>

theatre.html

<html>
    <head>
        <title>Alankar Theatre</title>
    </head>
    <body bgcolor="lightblue">
        <h1 align="center">Vijayawada-AP</h1>
        <h2 align="center">Alankar Theatre</h2>
        <hr size="4" color="black">
        <p><b>Alankar Theatre is a movie theater in Vijayawada located in Gandhi Nagar, known for its good sound quality with Dolby Atmos and 4K picture quality. While it offers a good viewing experience and has comfortable seating, some reviews mention inconsistent maintenance, poor AC performance, and limited snack options. It also has wheelchair-accessible entrances and parking. </b></p>
    </body>
</html>

museum.html

<html>
    <head>
        <title>Bapu Museum</title>
    </head>
    <body bgcolor="lightgreen">
        <h1 align="center">Vijayawada-AP</h1>
        <h2 align="center">Bapu Museum</h2>
        <hr size="4" color="black">
        <p><b>The Bapu Museum in Vijayawada is an archaeological museum located on M.G. Road that was formerly known as the Victoria Jubilee Museum</b></p>
    </body>
</html>

hospital.html

<html>
    <head>
        <title>Andhra Hospital</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">Vijayawada-AP</h1>
        <h2 align="center">Andhra Hospital And Brain Center</h2>
        <hr size="4" color="black">
        <p><b>Andhra Hospitals in Vijayawada is a super-specialty hospital established in 2004 that offers a wide range of medical and surgical services, including 24-hour urgent care, general surgery, orthopedic and joint replacement, neurosurgery, and more</b></p>
    </body>
</html>
```


## OUTPUT
![alt text](image.png)

![alt text](image-1.png)

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
