# Ex04 Places Around Me
## Date: 02.04.2024

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
MAP.HTML:
<html>
    <head>
        <title>My city </title>
        </head>
        <body>
                <h1 align="center">
                <font color="red"><b>Namakkal</b></font>
                </h1>
                <h3 align="center">
                    <font color="blue">
                    <b> PRAJAN P (212223240121)</b></font>
                </h3>
                <center>
                    <img src="map.png" usemap="#image-map">

                    <map name="image-map">
                        <area target="" alt="Hotel sree Saravana Bhavan" title="Hotel sree Saravana Bhavan" href="hotel.html" coords="798,722,973,765" shape="rect">
                        <area target="" alt="Namakkal Anjaneyar Temple" title="Namakkal Anjaneyar Temple" href="temple.html" coords="511,558,49" shape="circle">
                        <area target="" alt="Hotel Sanu International" title="Hotel Sanu International" href="residency.html" coords="597,396,818,432" shape="rect">
                        <area target="" alt="TVS sarathy motors" title="TVS sarathy motors" href="automobiles.html" coords="816,622,49" shape="circle">
                        <area target="" alt="Sun Travels Namakkal" title="Sun Travels Namakkal" href="travels.html" coords="356,459,561,474" shape="rect">
                    </map>
                    
                    </center>
                    </body>
                    </html>


HOTEL.HTML:
<html>
    <head>
        <title>HOTEL</title>
    </head>
    <body bgcolor="BLUE">
        <h1 align="center">
            <font face="algerian" color="WHITE"><b>HOTEL SREE SARAVANA BHAVAN</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="WHITE"><b>TASTE MATTERS</b></font>
        </h3>
        <hr size="3" color="red">
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="WHITE">
                Hotel Sree Saravana Bhavan in Namakkal is a popular choice for travelers seeking comfortable accommodation. Here are some details about the hotel:
                Location: The hotel is situated at 6/922, Trichy Road, Namakkal, Tamil Nadu.
                Price Range: Rooms start from ₹1,5711.
                Facilities and Amenities: The rooms are spacious, well-appointed, and clean. The hotel staff is friendly and accommodating. There is a vegetarian restaurant on the ground floor that serves delicious South Indian cuisine. However, the hot water supply may be less than lukewarm
            </font>
        </p>
        <hr size="3" color="red">
        <hr size="3" color="red">
        </body>
        </html>

TEMPLE.HTML:

<html>
    <head>
        <title>TEMPLE</title>
    </head>
    <body bgcolor="gold">
        <h1 align="center">
            <font face="algerian" color="black"><b>SREE ANJANEYAR TEMPLE</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="BLACK"><b>ASIA's FIRST LARGESTEST ANJANEYAR STATUE</b></font>
        </h3>
        <hr size="3" color="GREEN">
        <hr size="3" color="GREEN">
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                The Namakkal Anjaneyar Temple, dedicated to the Hindu god Hanuman, is a remarkable place in Namakkal, Tamil Nadu, India. Here are some fascinating details about this sacred temple:

                Location: Situated in Namakkal, the temple follows the Dravidian style of architecture. It stands on the road from Namakkal to Salem, nestled in the downhill of the Namakkal hill   
            </font>
        </p>
        <hr size="3" color="GREEN">
        <hr size="3" color="GREEN">
        </body>
        </html>

RESIDENCY.HTML:
<html>
    <head>
        <title>RESIDENCY</title>
    </head>
    <body bgcolor="PURPLE">
        <h1 align="center">
            <font face="algerian" color="GOLD"><b>HOTEL SANU INTERNATIONAL</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="GOLD"><b>LEISURE WITH LUXSURY</b></font>
        </h3>
        <hr size="3" color="WHITE">
        <hr size="3" color="WHITE">
        <p align="justify">
            <font face="Georgia" size="5" color="WHITE">
                Hotel Sanu International in Namakkal is a 3-star hotel that offers a comfortable and convenient stay experience. Here are some details about this establishment:

                Location: Situated at 280/158 Salem Main Road, Namakkal, Tamil Nadu 6370011.
                Amenities:
                Lavishly Furnished Air-Conditioned Rooms: The hotel provides well-appointed rooms for guests.
                CCCTV With Satellite Channels: Ensures security and entertainment.
                Wi-Fi Internet Zone: Stay connected during your visit.
                Doctor on Call: Immediate medical assistance if needed.
                24-Hour Room Service: Convenient for guests.
                Coffee Shop: A place to relax and enjoy a cup of coffee.
                Restaurant: Serves delicious meals.
                Free Breakfast: Start your day with a complimentary meal.
                Free Parking: Convenient for travelers with vehicles.    
            </font>
            
        </p>
        <hr size="3" color="WHITE">
        <hr size="3" color="WHITE">
        </body>
        </html>

AUTOMOBILES.HTML:
<html>
    <head>
        <title>AUTOMOBLES</title>
    </head>
    <body bgcolor="maroon">
        <h1 align="center">
            <font face="algerian" color="SKY BLUE"><b>TVS SARATHY MOTORS</b></font>
        </h1>
        <h3 align="center">
            <font face="algerian" color="SKY BLUE"><b>BIKES IN HORSE POWER</b></font>
        </h3>
        <hr size="3" color="BLACK">
        <hr size="3" color="BLACK">
        <p align="justify">
            <font face="Georgia" size="5" color="SKY BLUE">
                Sarathy Motor, an authorized TVS Motor Company dealer, is located in Namakkal, Tamil Nadu. Here are the details:

                Address: 143, Salem Main Road, Opposite To Psk Petrol Bunk, Namakkal, Tamil Nadu, 637001.
                Contact Number: +91 98422 58269
                Email: sarathy.velur@tvsmdealers.co.in
                If you are looking for TVS bikes or need any assistance related to TVS vehicles, feel free to visit Sarathy Motor. They will be happy to assist you!     
            </font>
            
        </p>
        <hr size="3" color="BLACK">
        <hr size="3" color="BLACK">
        </body>
        </html>

TRAVELS.HTML:
<html>
    <head>
        <title>TRAVELS</title>
    </head>
    <body bgcolor="LIGHT GREEN">
        <h1 align="center">
            <font face="algerian" color="RED"><b>  SUN TRAVELS NAMAKKAL</b></font>
        </h1>
        <h2 align="center">
            <font face="algerian" color="RED"><b>MAKES YOU REACH YOUR DESTINATION</b></font>
        </h2>
        <hr size="3" color="YELLOW">
        <hr size="3" color="YELLOW">
        <p align="justify">
            <font face="Georgia" size="5" color="RED">
                Sun Travels in Namakkal has been serving travelers since 1995. Here are some details about their services:

                Services Offered:
                Travels, Taxi & Cabs Service: Sun Travels provides reliable taxi and cab services.
                Outstation Rentals: Whether you are traveling from or to Namakkal, they offer convenient outstation rental services  
            </font>
            
        </p>
        <hr size="3" color="YELLOW">
        <hr size="3" color="YELLOW">
        </body>
        </html>

```



## OUTPUT
MAP.HTML:
![alt text](<Screenshot (13).png>)
 
 HOTEL.HTML:
![alt text](<mapapp/static/Screenshot (14).png>)

TEMPLE.HTML:
![alt text](<mapapp/static/Screenshot (15).png>)

RESIDENCY.HTML:
![alt text](<mapapp/static/Screenshot (16).png>)

AUTOMOBILES.HTML:
![alt text](<mapapp/static/Screenshot (17).png>)

TRAVELS.HTML:
![alt text](<mapapp/static/Screenshot (18).png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
