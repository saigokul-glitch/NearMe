# Ex03 Places Around Me
## Date: 22.11.2025

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
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Chengalpattu</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>saigokul k (25004959)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="595,337,750,384" href="home.html" title="My Home Town">
                <area shape="rect" coords="1031,396,1198,440" href="park.html" title="wonderla amusement park">
                <area shape="rect" coords="511,487,582,593" href="lake.html" title="kolavai lake">
                <area shape="rect" coords="605,421,663,461" href="city.html" title="Mahendra World City">
                <area shape="rect" coords="1072,243,1231,299" href="temple.html" title="Swarnakarshana Bhairavar Temple">
            </map>
        </center>
    </body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="cyan">

<h1 align="center">
<font color="red"><b>Singaperumal Koil</b></font>
</h1>

<h3 align="center">
<font color="blue"><b>My Home Town - Singaperumal Koil</b></font>
</h3>

<hr size="3" color="red">

<p align="justify">
<font face="Georgia" size="5">
Singaperumal Koil is a well-known town in Tamil Nadu, famous for the Sri Padalathri Narasimhar Temple situated on a small hill. It is located between Chennai and Chengalpattu, making it an important stop along the GST Road. The town has good transport facilities, schools, markets, and peaceful residential areas. Singaperumal Koil pincode is 603204, and it is close to major places like Maraimalai Nagar and Chengalpattu.
</font>
</p>

</body>
</html>
 
 city.html

<html>
<head>
<title>My City</title>
</head>

<body bgcolor="violet">

<h1 align="center">
<font color="red"><b>Mahindra World City</b></font>
</h1>

<h3 align="center">
<font color="yellow"><b>Mahindra World City - popular city </b></font>
</h3>

<hr size="3" color="red">

<p align="justify">
<font face="Georgia" size="5">
Mahindra World City (MWC) is a well-planned integrated business city located near Chengalpattu in Tamil Nadu. It is one of India's first operational SEZ-based townships, offering a clean, green, and modern living environment. The city includes industrial zones, IT parks, residential areas, schools, and retail centers.  
<br><br>
MWC is known for its excellent infrastructure, peaceful surroundings, and strong connectivity through the GST Road and nearby railway station. Many international companies and industries operate here, making it an important economic hub. The area is also known for its eco-friendly development and beautiful greenery.
</font>
</p>

</body>
</html>

lake.html

<html>
<head>
<title>Kolavai Lake</title>
</head>

<body bgcolor="lightyellow">

<h1 align="center">
<font color="darkgreen"><b>Kolavai Lake</b></font>
</h1>

<h3 align="center">
<font color="brown"><b>Kolavai Lake - The Beautiful Lake</b></font>
</h3>

<hr size="3" color="green">

<p align="justify">
<font face="Georgia" size="5">
Kolavai Lake, located near Chengalpattu, is one of the largest natural lakes in Tamil Nadu. It is known for its scenic views, calm atmosphere, and the beautiful sunset that attracts visitors every day.  
<br><br>
The lake plays an important role in supporting local wildlife and is a major water source for the surrounding areas. Its peaceful surroundings make it a favorite spot for morning walks, photography, and relaxation.
</font>
</p>

</body>
</html>

park.html

<html>
<head>
<title>Wonderla Amusement Park</title>
</head>

<body bgcolor="lightblue">

<h1 align="center">
<font color="purple"><b>Wonderla Amusement Park</b></font>
</h1>

<h3 align="center">
<font color="darkblue"><b>Fun & Thrill at Wonderla</b></font>
</h3>

<hr size="3" color="purple">

<p align="justify">
<font face="Georgia" size="5">
Wonderla Amusement Park is one of the most exciting entertainment destinations in India, known for its thrilling rides, water games, and family attractions. The park features high-adrenaline roller coasters, relaxing pools, and kid-friendly sections, making it a perfect place for all age groups.  
<br><br>
With clean surroundings, modern facilities, and well-maintained rides, Wonderla offers a fun-filled experience for visitors seeking adventure and enjoyment. It is a popular weekend hangout spot for families and friends.
</font>
</p>

</body>
</html>

temple.html

<html>
<head>
<title>My City</title>
</head>

<body bgcolor="violet">

<h1 align="center">
<font color="gold"><b>Swarnakarshana Bhairavar Temple</b></font>
</h1>

<h3 align="center">
<font color="pale green"><b>Swarnakarshana Bhairavar temple - Devotional place</b></font>
</h3>

<hr size="3" color="yellow">

<p align="justify">
<font face="Georgia" size="5">
    The Swarnakarshana Bhairavar Temple, located in Kelambakkam/Thaiyur near Chengalpattu, is dedicated to Swarnakarshana Bhairava, a revered form of Bhairava known for attracting prosperity and removing obstacles. Devotees visit the temple seeking blessings for wealth, protection, and spiritual upliftment. The temple, with its serene atmosphere, serves as a center for devotion and rituals, offering a space for both material and spiritual growth.


</font>
</p>

</body>
</html>

## OUTPUT
<img width="1914" height="876" alt="map" src="https://github.com/user-attachments/assets/d6801191-fc40-4307-9314-4153f809a1bb" />

![1](https://github.com/user-attachments/assets/194b731e-fb24-47a6-9369-5b004d549cd9)





## RESULT
The program for implementing image maps using HTML is executed successfully.
