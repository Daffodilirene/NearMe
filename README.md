# Ex03 Places Around Me
## Date: 27.11.2025

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
        <title>My city</title>
    </head>
    <body bgcolor="lavender">  
        <h1 align="center">DINDIGUL</h1>
        <h4 align="center">DAFFODIL IRENE.S(25002685)</h4>
        <img src="map.png.png" usemap="#image-map" alt="Dindigul Map" >

<map name="image-map">
    <area target="" alt="Dindigul Fort" title="Dindigul Fort" href="dindigulfort.html" coords="426,406,688,520" shape="rect">
    <area target="" alt="Aarthi Grand cineplax" title="Aarthi Grand cineplax" href="cineplax.html" coords="1284,334,84" shape="circle">
    <area target="" alt="Venu Biriyani Hotel Dindigul" title="Venu Biriyani Hotel Dindigul" href="venuhotel.html" coords="796,460,712,513,717,581,866,572,866,500" shape="poly">
    <area target="" alt="Hotel Vales Park" title="Hotel Vales Park" href="valespark.html" coords="1126,540,1140,636,1231,665,1324,617,1324,543,1277,496,1183,496" shape="poly">
    <area target="" alt="Royaloak Furniture Dindigul" title="Royaloak Furniture Dindigul" href="furniture.html" coords="675,220,572,260,579,348,662,392,804,378,858,314,825,254,781,195" shape="poly">
</map>
    </body>
</html>


cineplax.html

<html>
    <head>
        <title>Cineplax</title>
    </head>
    <body bgcolor="lightgreen">  
        <h1  align="center"><font color="darkpink">DINDIGUL</font></h1>
        <h3 align="center">Aarthi Grand Cineplax</h3>
        <hr size="6" color="darkgreen">
        <p align="center"><b>
            Aarthi Grand Cineplax is a popular cinema complex located in Dindigul, Tamil Nadu. It offers a modern movie-watching experience with multiple screens, comfortable seating, and advanced sound systems. The cineplex showcases a variety of films, including the latest Tamil, Telugu, and Hindi releases. It is a favorite destination for locals and visitors alike to enjoy entertainment and leisure time.
            </b>
      
        </p>

      
    </body>
</html>


dindigulfort.html


<html>
    <head>
        <title>Dindigul Fort</title>
    </head>
    <body bgcolor="lightpink">  
        <h1  align="center"><font color="darkpink">DINDIGUL</font></h1>
        <h3 align="center">Dindigul Fort</h3>
        <hr size="6" color="purple">
        <p align="center"><b>
            Dindigul Fort is a historic hill fort built on a large rock in Dindigul, Tamil Nadu. It was constructed by the Madurai Nayakas in the 17th century and later strengthened by Hyder Ali and Tipu Sultan. The fort was used as a military base because of its strong structure and high viewpoint. Today, it is maintained by the Archaeological Survey of India and is a popular tourist attraction.
            </b>
      
        </p>

      
    </body>
</html>



furniture.html

<html>
    <head>
        <title>furniture</title>
    </head>
    <body bgcolor="goldenrod">  
        <h1  align="center"><font color="saddlebrown">DINDIGUL</font></h1>
        <h3 align="center">Royaloak Furniture</h3>
        <hr size="6" color="saddlebrown">
        <p align="center"><b>
            Royaloak Furniture is a prominent furniture store located in Dindigul, Tamil Nadu. Known for its wide range of high-quality furniture products, Royaloak offers everything from stylish sofas and elegant dining sets to functional office furniture and cozy bedroom collections. The store emphasizes modern designs, durability, and customer satisfaction, making it a popular choice for residents looking to furnish their homes and offices with premium furniture pieces.
            </b>
      
        </p>

      
    </body>
</html>


valespark.html


<html>
    <head>
        <title>valespark</title>
    </head>
    <body bgcolor="lightblue">  
        <h1  align="center"><font color="darkblue">DINDIGUL</font></h1>
        <h3 align="center">Hotel Vales Park </h3>
        <hr size="6" color="darkblue">
        <p align="center"><b>
            Hotel Vales Park is a well-known hotel located in Dindigul, Tamil Nadu. It offers comfortable accommodations and a range of amenities for both business and leisure travelers. The hotel features spacious rooms, a restaurant serving delicious local and international cuisine, and conference facilities for events and meetings. Its convenient location makes it a popular choice for visitors to the area.
            </b>
      
        </p>

      
    </body>
</html>


venushotel.html


<html>
    <head>
        <title>venushotel</title>
    </head>
    <body bgcolor="yellow">  
        <h1  align="center"><font color="darkpink">DINDIGUL</font></h1>
        <h3 align="center">Venus Biriyani Hotel </h3>
        <hr size="6" color="red">
        <p align="center"><b>
            Venus Biriyani Hotel is a well-known dining establishment in Dindigul, Tamil Nadu, famous for its delicious biriyani and South Indian cuisine. The hotel offers a variety of flavorful dishes, including mutton biriyani, chicken biriyani, and vegetarian options, all prepared with traditional spices and cooking methods. It is a popular spot for both locals and tourists looking to enjoy authentic Dindigul flavors in a comfortable setting.
            </b>
      
        </p>

      
    </body>
</html>


```

## OUTPUT
![alt text](<Screenshot (20).png>)

![alt text](<Screenshot (21).png>)

![alt text](<Screenshot (22).png>)

![alt text](<Screenshot (23).png>)

![alt text](<Screenshot (24).png>)

![alt text](<Screenshot (25).png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
