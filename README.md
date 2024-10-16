# Ex04 Places Around Me
### Name : Loshini.G
### Reg no : 212223220051
### Department: IT
### Date: 

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

## CODE:
### Map.html:
```html
<doctype! html>
<html>
    <head>
        <title>my city</title>
    </head>
    <body>
        <h1 align = "center">
          <font color="red"<b>Pammal</b></font>
        </h1>
        <h3 align = "center">Loshini G (212223220051)</h3>
        <center> 
            <img src="c:\Pictures\Screenshots\map1.png" usemap="#mycity" height ="550" width ="1300">
        <map name = "mycity">
            <area shape="rect" coords="511,243,536,264" href="mahal.html" title="SS Mahal GB party hall ">
            <area shape="rect" coords="1147,214,1178,234" href="apartment.html" title="CM stays & Service Apartment">
            <area shape="rect" coords="167,393,190,412" href="school.html" title="Sri Sankara Vidyalaya">
            <area shape="rect" coords="446,309,479,333" href="pharmacy.html" title="Medplus Pammal">
            <area shape="rect" coords="1242,415,1274,440" href="restaurant.html" title="Cake Walk">
        </map>
    </center>
    </body>
</html>
```
### Mahal.html:
```html
<doctype! html>

<html>
    <head><title>ss mahal</title></head>
    <style>
        *{background-color: aliceblue;}
        h1{text-align: center;color: brown;}
        h2{text-align: center;color: blueviolet;}
    </style>
    <body>
        <h1>Pammal</h1>
        <h2>SS Mahal GB party hall </h2>
        <hr color="red">
        <h3><p>
            SS Mahal:
Facilities: SS Mahal is known for its spacious banquet hall, suitable for hosting weddings, receptions, and various other celebrations. The venue is equipped with modern amenities, including ample parking, air conditioning, and catering services.
Ambiance: The decor typically features traditional Indian aesthetics, making it a popular choice for cultural events.
Location: Conveniently situated in Pammal, it is easily accessible for guests.
      GB Mahal:
Facilities: GB Mahal also offers a large event space designed for weddings and gatherings, with similar amenities as SS Mahal, including sound systems and seating arrangements.
Catering: They provide catering services, specializing in South Indian cuisine, which is a significant attraction for local celebrations.
Reputation: Known for its excellent service and accommodating staff, GB Mahal has received positive reviews from previous clients.
        </p></h3>
    </body>
</html>

```
### Pharmacy.html:
```html
<doctype! html>

<html>
    <head><title>Medplus Pammal</title></head>
    <style>
        *{background-color: lavender;}
        h1{text-align: center;color: indigo;}
        h2{text-align: center;color: mediumvioletred;}
    </style>
    <body>
        <h1>Pammal</h1>
        <h2>Medplus Pammal </h2>
        <hr color="red">
        <h3><p>
            MedPlus is one of India's leading pharmacy retail chains, established in 2006 by Madhukar Gangadi and headquartered in Hyderabad. As of 2024, it operates over 4,230 stores across more than 600 cities, making it the second-largest pharmacy network in the country. MedPlus offers a wide range of products, including prescription and over-the-counter medications, fast-moving consumer goods (FMCG), and optical products. In addition to its physical stores, MedPlus has a robust online presence through platforms like MedPlusMart for e-commerce and MedPlusLab for diagnostic services.The company focuses on providing genuine pharmaceutical products at competitive prices, coupled with a customer loyalty program called "FlexiRewards".
            
        </p></h3>
    </body>
</html>
```
### Restaurant.html:
```html
<doctype! html>

<html>
    <head><title>Cake Walk</title></head>
    <style>
        *{background-color: mistyrose;}
        h1{text-align: center;color: navy;}
        h2{text-align: center;color: tomato;}
    </style>
    <body>
        <h1>Pammal</h1>
        <h2>Cake Walk </h2>
        <hr color="red">
        <h3><p>
            Cake Walk is a popular cake shop located in Pammal, Chennai, known for its wide variety of freshly baked cakes. They offer an assortment of flavors and designs, making it a go-to destination for celebrations and special occasions. The shop provides options for customized cakes, allowing customers to create unique designs tailored to their needs. Cake Walk is appreciated for its quality ingredients and attention to detail in cake decoration.

In addition to cakes, they may also offer pastries and other baked goods, making it a sweet spot for dessert lovers in the area
        </p></h3>
    </body>
</html>
```
### School.html:
```html
<doctype! html>

<html>
    <head><title>Sri Sankara Vidyalaya</title></head>
    <style>
        *{background-color: floralwhite;}
        h1{text-align: center;color: lightcoral;}
        h2{text-align: center;color: hotpink;}
    </style>
    <body>
        <h1>Pammal</h1>
   <h2>Sri Sankara Vidyalaya </h2>
        <hr color="red">
        <h3><p>
            Sri Sankara Vidyalaya Matriculation Higher Secondary School in Pammal was established in 1983 under the guidance of His Holiness Jagadguru Sri Jayendra Saraswathi. Starting with 135 students, it has grown to over 2,000 students, supported by a dedicated management and 90 qualified teachers. The school offers computer education from classes I to X and has extensive sports facilities for student participation. The premises include a three-story building for primary classes and a 35,000 sq. ft. area for classes from L.K.G to XII.
        </p></h3>
    </body>
</html>
```
### Apartment:
```html
<doctype! html>

<html>
    <head><title>CM stays & Service Apartment</title></head>
    <style>
        *{background-color: khaki;}
        h1{text-align: center;color: indianred;}
        h2{text-align: center;color: indigo;}
    </style>
    <body>
        <h1>Pammal</h1>
        <h2>CM stays & Service Apartment </h2>
        <hr color="red">
        <h3><p>CM Stays & Service Apartment in Chennai offers a comfortable two-bedroom accommodation near the airport. Guests appreciate its cleanliness, friendly staff, and convenient location. The apartment features amenities like free WiFi, air conditioning, a private bathroom, and a balcony. With a score of 9.1, it’s ideal for families and provides services like free parking and airport shuttles. The property has received positive reviews for its hospitality and proximity to local attractions. More details can be found on their official site.

            
        </p></h3>
    </body>
</html>
```

## OUTPUT:
### Map:
![map](https://github.com/user-attachments/assets/d5fe048a-9c14-4235-834d-6a19ce778151)
### Mahal:
![mahal](https://github.com/user-attachments/assets/99900810-d157-440f-93cd-4e6b120aa053)
### Restaurant:
![restaurant](https://github.com/user-attachments/assets/c5aeaea1-c000-4276-98b8-490ec8e2682a)
### Pharmacy:
![pharmacy](https://github.com/user-attachments/assets/591195ae-8fc0-4c6c-9f99-af02858e8b4a)
### School:
![school](https://github.com/user-attachments/assets/2272788f-f5a3-4177-b128-0f6a27ee2a63)
### Apartment:
![apartment](https://github.com/user-attachments/assets/5a53fc4d-9d6e-4dcd-a936-af94b3728c0c)



## RESULT
The program for implementing image maps using HTML is executed successfully.
