# Ex03 Places Around Me
## Date: 01-12-2025

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
        <title>map</title>
    </head>
    <body>
        <h1 align="center">chennai</h1>
        <br>
        <h2 align="center">snajay babu.m (25003400)</h2>
        <hr>
        <img src="map.2.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="meenakshi Cinemas" title="meenakshi Cinemas" href="meenakshi.html" coords="709,205,909,261" shape="rect">
    <area target="" alt="OCF FOOTBALL GROUND" title="OCF FOOTBALL GROUND" href="OCF" coords="1064,69,69" shape="circle">
    <area target="" alt="krishna Menon hall" title="krishna Menon hall" href="Krishna.html" coords="700,66,904,58,928,132,818,170,719,147" shape="poly">
    <area target="" alt="sb reddiyar" title="sb reddiyar" href="SB babu.html" coords="244,349,408,366" shape="rect">
    <area target="" alt="best salon avadi" title="best salon avadi" href="virtue salon.html" coords="1129,148,1318,141,1328,240,1183,281,1091,255" shape="poly">
</map>
    </body>
</html>
<html>
    <head>
        <title>
            cinema
        </title>
    </head>
    <body bgcolor="While" style="color: rgb(146, 234, 39);">
        <h1 align="center" style="color: rgb(235, 11, 7);">meenakshi cinema</h1>
        <h1 align="center" style="color: rgb(236, 248, 9);"><b>avadi</b></h1>
        <hr>
It’s a well-frequented spot for moviegoers in the Avadi area, offering a comfortable viewing experience with decent amenities. If you're planning a visit, checking their website for showtimes and ticket availability is a good idea</body>
</html>
<html>
    <head>
        <title>
            ground
        </title>
    </head>
    <body bgcolor="While" style="color: rgb(146, 234, 39);">
        <h1 align="center" style="color: rgb(235, 11, 7);">ocf ground</h1>
        <h1 align="center" style="color: rgb(236, 248, 9);"><b>avadi</b></h1>
        <hr>
- A popular spot for football enthusiasts, known for its accessibility and open hours.
</html>
<html>
    <head>
        <title>
            hall        </title>
    </head>
    <body bgcolor="While" style="color: rgb(146, 234, 39);">
        <h1 align="center" style="color: rgb(235, 11, 7);">meeron hall</h1>
        <h1 align="center" style="color: rgb(236, 248, 9);"><b>avadi</b></h1>
        <hr>
        Located in OCF Estate, GiriNagar, Avadi, this banquet hall is well-rated with a 4.1-star average from over 270 reviews. It's a popular venue for weddings, receptions, and comm

        html>
    <head>
        <title>
            path
        </title>
    </head>
    <body bgcolor="While" style="color: rgb(146, 234, 39);">
        <h1 align="center" style="color: rgb(235, 11, 7);">arjun path</h1>
        <h1 align="center" style="color: rgb(236, 248, 9);"><b>avadi</b></h1>
        <hr>
Arjun Path is located in Bhaktavatsala Puram, Avadi, Tamil Nadu 600054. It's a local street in the Avadi area, often used as a residential and transit route. If you're looking for directions, nearby landmarks, or services around Arjun Path
</html>
<html>
    <head>
        <title>
            saloon
        </title>
    </head>
    <body bgcolor="While" style="color: rgb(146, 234, 39);">
        <h1 align="center" style="color: rgb(235, 11, 7);">vitrue saloon</h1>
        <h1 align="center" style="color: rgb(236, 248, 9);"><b>avadi</b></h1>
        <hr>
Virtue Salon Avadi is a top-rated beauty salon located near the Avadi Bus Stand in Bhaktavatsala Puram. With a stellar rating of 4.9 stars from over 740 reviews, it's known for its professional services and customer satisfaction.
</html>

````

## OUTPUT
![alt text](<Screenshot (15).png>)

![alt text](<Screenshot (16).png>)

![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
