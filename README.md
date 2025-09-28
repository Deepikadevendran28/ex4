# Ex04 Places Around Me
## Date: 28.09.2025

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
~~~
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="violet"></b>Karur</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Deepika D (25016783)</b></font>
</h3>
<center>
<img src="map.png" usemap="#My City" height="610" width="1450">
<map name="My City">
<area target="_blank" alt="A.P.NAGAR" title="A.P.NAGAR" href="Home.html" coords="572,91,786,240" shape="rect">
<area target="_blank" alt="Sachin Badminton Club" title="Sachin Badminton Club" href="club.html" coords="170,304,365,333" shape="rect">
<area target="_blank" alt="CP Farms" title="CP Farms" href="farm.html" coords="931,520,1039,552" shape="rect">
<area target="_blank" alt="HOTEL CHOLA" title="HOTEL CHOLA" href="hotel.html" coords="759,269,884,320" shape="rect">
<area target="_blank" alt="Krishnamoorthy Mulberry Garden" title="Krishnamoorthy Mulberry Garden" href="garden.html" coords="949,407,1096,452" shape="rect">
</map>
</center>
</body>
</html>

Home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="centre">
<font color="orange"><b>My Home Town</b></font>
</h1>
<h3 align="centre">
<font color="violet"><b>A.P.NAGAR - Karur</b></font>
</h3>
<hr size=3 color="blue">
<p align="justify">
<font face="Georgia" size="5">
A.P. Nagar in Karur
A.P. Nagar is identified as a locality within the Karur area, and specifically appears 
to be a real estate and residential hub.
Key points about A.P. Nagar:
Location: It is located near Puliyur, which is one of the Town Panchayats in the Karur District, Tamil Nadu.
Property Type: The area is noted for the availability of Residential Lands & Plots for sale.
Investment Potential: The area offers various land options, including plots suitable for residential 
development, as well as commercial and agricultural use, which can be purchased with consideration 
for legal verification and proximity to essential services.
Rental Market: The locality also features listings for flats and apartments for rent, 
indicating it is an active residential area.</font>
</p>
</body>
</html>

garden.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="centre">
<font color="green"></b></font>
</h1>
<h3 align="centre">
<font color="cyan"><b>Krishnamoorthy Mulberry Garden  - Famous Mulberry Garden</b></font>
</h3>
<hr size=3 color="purple">
<p align="justify">
<font face="Georgia" size="5">
The "Krishnamoorthy Mulberry Garden" in Karur likely refers to the agricultural or research work 
related to mulberry cultivation (sericulture) in the region, rather than a specific commercial garden
open to the public. It is strongly associated with mulberry cultivation and likely the related field of 
sericulture (silkworm rearing). Mulberry leaves are the primary food for silkworms.The work 
associated with the name contributes to the local agricultural science and the optimization of 
silkworm rearing, which is a significant component of the textile and handloom industry for
which Karur is famous.</font>
</p>
</body>
</html>

hotel.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="white">
<h1 align="centre">
<font color="light ash"></b></font>
</h1>
<h3 align="centre">
<font color="violet"><b>HOTEL CHOLA - Famous Hotel</b></font>
</h3>
<hr size=3 color="purple">
<p align="justify">
<font face="Georgia" size="5">
Name Variation: It is most frequently listed as Cholaa Inn or Hotel Cholaa Inn.
Location: The hotel is centrally located on Kovai Road in Karur, often noted to
be Opposite Ajantha Theatre and close to the Karur Bus Stand (about 1 km)
and Karur Railway Station (about 2 km), making it convenient for travellers.Type 
of Accommodation: It is generally considered a budget to mid-range hotel that 
provides clean and comfortable stay options. It's often recommended for both 
business travellers and families.</font>
</p>
</body>
</html>

farm.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="orange">
<h1 align="centre">
<font color="light ash"></b></font>
</h1>
<h3 align="centre">
<font color="blue"><b>CP FARMS - Agri Farm</b></font>
</h3>
<hr size=3 color="red">
<p align="justify">
<font face="Georgia" size="5">
 The name "CP Farms" is not exclusively a single farm in Puliyur.
It is widely associated with Charoen Pokphand (CP) Group, a major 
global agribusiness and food conglomerate that has extensive operations
in India.Probable Business Activity: If the facility is related to the 
international CP Group, its activity in Puliyur is highly likely to be
in the Livestock and Feed sector, specializing in:
Poultry Farming (broilers and layers)
Animal Feed Production
Using advanced techniques like Environmentally Controlled (EC) Smart Farms
for efficient and high-quality production.
Integrated Model: The CP Group operates on a "Feed-to-Fork" concept, meaning 
they manage every stage from animal feed to the final 
processed meat or egg product.</font>
</p>
</body>
</html>

club.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="dark pink">
<h1 align="centre">
<font color="light ash"></b></font>
</h1>
<h3 align="centre">
<font color="violet"><b>Sachin Badminton Club</b></font>
</h3>
<hr size=3 color="purple">
<p align="justify">
<font face="Georgia" size="5">
Establishment: The club was established relatively recently, around 2022. 
It is primarily known as a Badminton Club with court facilities. Some 
sources also list it under general "Sports Clubs" and occasionally mention 
other types of classes.The club is noted for organizing tournament matches 
and may provide opportunities for skilled players to 
participate in interstate games.</font>
</p>
</body>
</html>
~~~
## OUTPUT

<img width="1366" height="768" alt="1" src="https://github.com/user-attachments/assets/08c0cc55-ba07-4da2-b870-6962beb03312" />

<img width="1366" height="768" alt="2" src="https://github.com/user-attachments/assets/16eaed5f-1af0-4622-9df9-df0e1e68615f" />

<img width="1366" height="768" alt="3" src="https://github.com/user-attachments/assets/067d06cc-5107-4d79-8c6c-f6bdb215549d" />

<img width="1366" height="768" alt="4" src="https://github.com/user-attachments/assets/b13db296-855b-46f7-b821-dba95909a522" />

<img width="1366" height="768" alt="5" src="https://github.com/user-attachments/assets/5d160bc4-533c-413f-a950-366e826e3888" />

<img width="1366" height="768" alt="6" src="https://github.com/user-attachments/assets/5feff8a5-3e6f-4921-9dcc-e77dcc4f98a5" />

## RESULT
The program for implementing image maps using HTML is executed successfully.
