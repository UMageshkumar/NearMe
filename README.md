# Ex04 Places Around Me
## Date: 25.11.2024

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
<font color="red"><b>Ariyalur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>MAGESHKUMAR U (24005417)</b></font>
</h3>
<center>
<img src="map.jpg" usemap="#image-map">
<map name="image-map">
    <area target="" alt="poorvika" title="poorvika" href="poorivika.html" coords="991,742,84" shape="circle">
    <area target="" alt="hospital" title="hospital" href="hospital.html" coords="388,260,618,356" shape="rect">
    <area target="" alt="hotel" title="hotel" href="hotel.html" coords="945,297,106" shape="circle">
    <area target="" alt="aswins" title="aswins" href="aswins.html" coords="553,603,749,685" shape="rect">
    <area target="" alt="stadium" title="stadium" href="stadium.html" coords="1028,97,91" shape="circle">
</center>
</map>
</body>
</html>

stadium.html

<!DOCTYPE html>
<html>
    <body style="background-color: rgb(213, 26, 54);">
        <h1 align="center">ARIYALUR-STADIUM</h1>
        <h3 align="center">STADIUM</h3>
        <hr>
        <h3>This stadium is most famous in ariyalur.
            District Sports Stadium have been established with the facilities of 400m Athletic Track, Gallery, Football Field, Hockey Field, Skating Ring,, Multipurpose Indoor Stadium, Ball badminton court, Tennis (Synthetic), Volleyball Court, Basketball Court, Swimming Pool and Baby Swimming Pool at District Sports Stadium, Ariyalur.
        </h3>
    </body>
</html>

hotel.html

<!DOCTYPE html>
<html>
    <body style="background-color: rgb(71, 197, 8);">
        <h1 align="center">ARIYALUR-HOTEL</h1>
        <h3 align="center">HOTEL</h3>
        <hr>
        <h3>
            Located in the vibrant heart of Kamarajar Nagar, Hotel Shree Venkateshwara is a cherished culinary haven where tradition meets innovation. Known for its commitment to quality ingredients, delightful flavors, and exceptional service, Hotel Shree Venkateshwara invites you to savor a dining experience like no other

        </h3>
    </body>
</html>

aswins.html

<!DOCTYPE html>
<html>
    <body style="background-color: rgb(246, 233, 47);">
        <h1 align="center">ARIYALUR-STADIUM</h1>
        <h3 align="center">STADIUM</h3>
        <hr>
        <h3>
            Located in the vibrant heart of Ariyalur, Aswins Home Special is a cherished culinary haven where tradition meets innovation. Known for its commitment to quality ingredients, delightful flavons, and
            exceptional service, Aswins Home Special invites you to savor a dining experience like no other
        </h3>
    </body>
</html>

hospital.html

<!DOCTYPE html>
<html>
    <body style="background-color: rgb(1, 90, 117);">
        <h1 align="center">ARIYALUR-HOSPITAL</h1>
        <h3 align="center">HOSPITAL</h3>
        <hr>
        <h3>
            The Government Medical College & Hospital Ariyalur caters to both urban as well as rural parts of Ariyalur and nearby districts, covering approximately 9,60,000 people from marginalized backgrounds. These people suffered the most during the pandemic due to acute shortage of oxygenated beds at various government hospitals. Even though Government Medical College & Hospital Ariyalur had allocated 400 general beds for COVID-19 patients, the lifesaving critical care equipment available at the hospital was not adequate.
        </h3>
    </body>
</html>

poorivika.html

<!DOCTYPE html>
<html>
    <body style="background-color: lightpink;">
        <h1 align="center">ARIYALUR-POORVIKA</h1>
        <h3 align="center">POORVIKA</h3>
        <hr>
        <h3>
            Poorvika Mobiles Pvt Ltd in Ariyalur is one of the leading businesses in the Data Card Dealers. Also known for Mobile Phone Dealers, TV Dealers, Mobile Phone Accessory Dealers, LED TV Dediers, Mobile Phone Dealers-Poco, Mobile Phone Dealers-Sony, Mobile Phone Dealers-Vivo, Mobile Phone Dealers-Tecno and much more. Find Address, Contact Number, Reviews & Ratings, Photos, Maps of Poorvilka Mobiles Pvt Ltd, Ariyalur
        </h3>
    </body>
</html>
```


## OUTPUT

![alt text](<Screenshot 2024-11-20 145001.png>)
![alt text](<Screenshot 2024-11-20 145025.png>)
![alt text](<Screenshot 2024-11-20 145044.png>)
![alt text](<Screenshot 2024-11-20 145102.png>)
![alt text](<Screenshot 2024-11-20 145127.png>)
![alt text](<Screenshot 2024-11-20 145147.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
