# Ex04 Places Around Me
## Date: 24-10-2025

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
```
map.html
<html>
<head>
    <title>My City</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>Gingee</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>JAGADEESH.A(212224230098)</b></font>
    </h3>
    <center>
        <img src="Screenshot 2025-10-24 111130.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">
        <area shape="rect" coords="100,50,800,350" href="Gingee.html" title="Gingee">
        <area shape="rect" coords="854,246" href="perumpugai.html" title="perumpugai">
        <area shape="circle" coords="425,299" href="Gingee_fort.html" title="gingee fort">
        <area shape="circle" coords="1245,601" href="mayura_residency.html" title="mayura residency">
        <area shape="circle" coords="222,712" href="anganeyar_temple.html" title="anganeyar temple">
        </map>
    </center>
</body>
</html>

anganeyar.html

<html>
    <head>
        <title>Anganeyar Temple</title>
        <style>
            body {
                background: linear-gradient(to bottom right, #f5f3e7, #e0d8c3);
                font-family: "Verdana", sans-serif;
                color: #333;
                margin: 40px;
                line-height: 1.8;
            }
            h1 {
                text-align: center;
                color: #5b3924;
                font-size: 32px;
                text-shadow: 1px 1px 2px #d1bfa3;
            }
            p {
                background-color: rgba(255, 255, 255, 0.7);
                padding: 20px;
                border-radius: 10px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
                max-width: 800px;
                margin: auto;
                font-size: 18px;
            }
        </style>
    </head>
    <body>
        <h1>Anganeyar Temple</h1>
        <p>
            The Anganeyar Temple is a beautiful and historic temple located in Gingee, Viluppuram District, Tamil Nadu. 
            It is one of the most important temples in the region and is dedicated to Lord Vishnu, who is worshipped here 
            as Sri Anganeyar (a form of Lord Krishna or Narayana).<br><br>

            This ancient temple stands as a fine example of Dravidian architecture, featuring beautifully carved stone pillars, 
            tall gopurams (temple towers), and traditional mandapams (halls). The temple is surrounded by peaceful natural 
            scenery, creating a calm and spiritual atmosphere for visitors.
        </p>
    </body>
</html>


Gingee_fort.html

<html>
    <head>
        <title>Gingee</title>
        <style>
            body {
                background: linear-gradient(to bottom right, #d0f0fd, #a0d4f7); /* soft blue theme */
                font-family: "Arial", sans-serif;
                color: #1a1a1a;
                margin: 40px;
                line-height: 1.7;
            }
            h1 {
                text-align: center;
                color: #05445e;
                font-size: 32px;
                text-shadow: 1px 1px 2px #aad4f5;
            }
            p {
                background-color: rgba(255, 255, 255, 0.85);
                padding: 20px;
                border-radius: 12px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
                max-width: 800px;
                margin: auto;
                font-size: 18px;
            }
        </style>
    </head>
    <body>
        <h1>Gingee Town</h1>
        <p>
            Gingee (also called Senji) is a small historic town located in the Villupuram district of Tamil Nadu, India. 
            It’s famous for its ancient fort, known as the Gingee Fort, which is one of the most beautiful and strongest forts in South India.
        </p>
    </body>
</html>

Mayura_residency

<html>
    <head>
        <title>Mayura Residency</title>
        <style>
            body {
                background: linear-gradient(to bottom right, #ffe5b4, #ffd699); /* warm, cozy colors */
                font-family: "Tahoma", sans-serif;
                color: #3a2f1c;
                margin: 40px;
                line-height: 1.7;
            }
            h1 {
                text-align: center;
                color: #b85c00;
                font-size: 32px;
                text-shadow: 1px 1px 2px #f5d6a0;
            }
            p {
                background-color: rgba(255, 255, 255, 0.85);
                padding: 20px;
                border-radius: 12px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
                max-width: 800px;
                margin: auto;
                font-size: 18px;
            }
        </style>
    </head>
    <body>
        <h1>Mayura Residency</h1>
        <p>
            Maurya Residency is a popular hotel located in Gingee, Villupuram District, Tamil Nadu. 
            It provides comfortable and affordable accommodation for travelers visiting the famous Gingee Fort and nearby tourist spots. 
            The hotel is situated on Tindivanam Road, offering easy access to transport and local markets.
        </p>
    </body>
</html>
<html>

perumpugai.html

<html>
    <head>
        <title>Perumpugai</title>
        <style>
            body {
                background: linear-gradient(to bottom right, #d0f5d0, #a0d9a0); /* fresh green gradient */
                font-family: "Verdana", sans-serif;
                color: #2f3e2f;
                margin: 40px;
                line-height: 1.7;
            }
            h1 {
                text-align: center;
                color: #2a5934;
                font-size: 32px;
                text-shadow: 1px 1px 2px #b5e0b5;
            }
            p {
                background-color: rgba(255, 255, 255, 0.85);
                padding: 20px;
                border-radius: 12px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
                max-width: 800px;
                margin: auto;
                font-size: 18px;
            }
        </style>
    </head>
    <body>
        <h1>Perumpugai</h1>
        <p>
            Perumpugai is a village located near Gingee in the Viluppuram district of Tamil Nadu. 
            It’s a rural area surrounded by farmlands, small hills, and greenery. 
            The main occupation of the people here is agriculture, and they usually grow crops like paddy (rice), groundnut, sugarcane, and millets depending on the season.
        </p>
    </body>
</html>





## OUTPUT
jaga/mapapp/static/Screenshot 2025-10-24 111130.png
jaga/mapapp/static/1.png
jaga/mapapp/static/2.png
jaga/mapapp/static/3.png
jaga/mapapp/static/4.png
jaga/mapapp/static/5.png
## RESULT
The program for implementing image maps using HTML is executed successfully.
