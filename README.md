# Ex04 Places Around Me
## Date: 22/03/2024

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
mappapp.html

<html>
    <head> 
        <title>Sample</title>
    </head>
    <body bgcolor="#9FE2BF">
    <h1 align="center">CHENNAI</h1>
    <h2 align="center">Harsshitha Lakshmanan (212223230075)</h2>
<img src="chennai.png" height="650" width="1500" usemap="#image-map">

<map name="image-map">
    <area target="" alt="guindy" title="guindy" href="place.html" coords="977,511" shape="rect">
    <area target="" alt="t nagar" title="t nagar" href="place.html" coords="999,432" shape="rect">
    <area target="" alt="porur" title="porur" href="place.html" coords="863,448" shape="rect">
    <area target="" alt="thandalam" title="thandalam" href="place.html" coords="796,518" shape="rect">
    <area target="" alt="sholinganallur" title="sholinganallur" href="place.html" coords="983,702" shape="rect">
</map>

guindy.html

<html>
    <head>
        <title>Guindy</title>
    </head>
    <body bgcolor="#9FE2BF">
        <h1 align="center"><b>Chennai</b></h1>
        <h2 align="center"><b>Guindy</b></h2>
        <hr width="100%" size="4" color="black">
        <br>
        <h2 align="center">
            Guindy is a neighborhood located in the southern part of Chennai,
             which is the capital city of the Indian state of Tamil Nadu. 
             It is known for several landmarks including the Guindy National Park, 
             one of the smallest national parks in India, covering an area of about 2.82 square kilometers.
        </h2>
        </br>
    </body>
</html>

porur.html

<html>
    <head>
        <title>Porur</title>
    </head>
    <body bgcolor="#df9191">
        <h1 align="center"><b>CHENNAI</b></h1>
        <h2 align="center"><b>PORUR</b></h2>
        <hr width="100%" size="4" color="black">
        <br>
        <h2 align="center">
            Porur is known for the expansive lake of the same name and the small, waterside Porur Lake Shiva Temple.
             Nearby, the centuries-old Sri Ramanaadheswarar Temple has an ornately carved gopura gateway tower. Clothing and appliances stores, Indian restaurants, 
            and the N.S.N. produce and fish markets cluster at the busy junction of Kundrathur Main Road and Mount Poonamalle High Road.
        </br>
        </h2>
        </br>
    </body>
</html>

tnagar.html

<html>
    <head>
        <title>T Nagar</title>
    </head>
    <body bgcolor="#CCCCFF">
        <h1 align="center"><b>CHENNAI</b></h1>
        <h2 align="center"><b>T NAGAR</b></h2>
        <hr width="100%" size="4" color="black">
        <br>
        <h2 align="center">
            T Nagar, short for Thyagaraya Nagar, is a prominent commercial and residential locality situated in Chennai, Tamil Nadu, India.
             It is known for its bustling streets lined with shops, restaurants, markets, and commercial establishments.
             It is surrounded by Nungambakkam in the North, Teynampet in the East, Nandanam in the South-East,
              C.I.T. Nagar (a part of Greater Nandanam region) in the South and West Mambalam and Kodambakkam in the West.
        </br>
        </h2>
        </br>
    </body>
</html>

thandalam.html

<html>
    <head>
        <title>Thandalam</title>
    </head>
    <body bgcolor="#a8cdf7">
        <h1 align="center"><b>CHENNAI</b></h1>
        <h2 align="center"><b>THANDALAM</b></h2>
        <hr width="100%" size="4" color="black">
        <br>
        <h2 align="center">
            Thandalam is an emerging location of the Chennai city in the Sriperumbudur taluk of Kancheepuram district, Tamil Nadu, India. 
            It is in the National Highway 4 or State Highway 84 at Sira Bypass. It is the village near the Chembarambakkam lake. 
            The Chembarambakkam Lake is close to the locality. Some of the reputed colleges in the locality are Saveetha Engineering College,
             Rajalakshmi Engineering College and Shakthi Mariamman Engineering College. Sri Krishna International School, Chennai Public school are some of the renowned schools near this locality
        </br>
        </h2>
        </br>
    </body>
</html>

sholinganallur.html

<html>
    <head>
        <title>sholinganallur</title>
    </head>
    <body bgcolor="#ffff66">
        <h1 align="center"><b>CHENNAI</b></h1>
        <h2 align="center"><b>SHOLINGANALLUR</b></h2>
        <hr width="100%" size="4" color="black">
        <br>
        <h2 align="center">
            Sholinganallur is known as an IT hub, with sleek offices and modern apartment complexes,
             plus a cluster of upscale Indian restaurants around Old Mahabalipuram Road. The neighborhood is also home to lakes and reservoirs, and the Sholinganallur Marsh Lands, a birdwatching area that attracts pelicans and storks.
             Devotees gather at the popular Sri Prathyangira Devi Temple, with its ornate, 4-story gateway tower.Sholinganallur is situated along the Old Mahabalipuram Road (OMR), also known as Rajiv Gandhi Salai, which is a major IT corridor in Chennai.
              It is approximately 15 kilometers from the city center.
        </br>
        </h2>
        </br>
    </body>
</html>


```

## OUTPUT
![alt text](<Screenshot 2024-03-22 094725.png>)
![alt text](<Screenshot 2024-04-04 224421.png>)
![alt text](<Screenshot 2024-04-04 224510.png>)
![alt text](<Screenshot 2024-04-04 224601.png>)
![alt text](<Screenshot 2024-04-04 224720.png>)
![alt text](<Screenshot 2024-04-04 225148.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
