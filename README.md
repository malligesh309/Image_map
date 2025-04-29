# Ex04 Places Around Me
# Date:29/4/2025
# Name:Malligesh M
# register no:212223230119
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
``` 
map.html
html
Copy
Edit
<html>
<head>
<title>My City</title>
</head>
<body bgcolor="lightgray">
<h1 align="center"><font color="yellow"><b>Porur</b></font></h1>
<h3 align="center"><font color="red"><b>Malligesh MR(212223230119)</b></font></h3>
<center>
<img src="map.png" usemap="#image-map" height="610" width="1450">
<map name="image-map">
    <area target="" alt="DLF IT Park" title="DLF IT Park" href="dlf.html" coords="960,521,743,442" shape="rect">
    <area target="" alt="Sri Ramachandra Medical College" title="Sri Ramachandra Medical College" href="ramachandra.html" coords="870,395,1113,429" shape="rect">
    <area target="" alt="MIOT Hospital" title="MIOT Hospital" href="miot.html" coords="727,297,117" shape="circle">
    <area target="" alt="Porur Junction" title="Porur Junction" href="junction.html" coords="915,232,1122,322" shape="rect">
    <area target="" alt="L&T Headquarters" title="L&T Headquarters" href="lt.html" coords="800,300,110,400" shape="rect">
</map>
</center>
</body>
</html>


dlf.html
html
Copy
Edit
<html>
<head>
<title>Porur</title>
</head>
<body bgcolor="lightblue">
<h1 align="center"><font color="blue"><b>Porur</b></font></h1>
<h3 align="center"><font color="red"><b>DLF IT Park</b></font></h3>
<hr size="3" color="black">
<p align="justify"><font face="Georgia" size="5">
DLF IT Park is one of the largest IT hubs in Porur, housing top IT firms like Cognizant, Barclays, and IBM. It serves as a significant contributor to Chennai's IT industry, offering world-class office spaces, high-end facilities, and infrastructure. The park plays a pivotal role in boosting the region’s employment opportunities while providing a perfect environment for business and technology-related growth. The area also enjoys easy accessibility to major transport routes and public transport.
</font></p>
</body>
</html>


miot.html
html
Copy
Edit
<html>
<head>
<title>Porur</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center"><font color="blue"><b>Porur</b></font></h1>
<h3 align="center"><font color="red"><b>MIOT International Hospital</b></font></h3>
<hr size="3" color="navy">
<p align="justify"><font face="Georgia" size="5">
MIOT International Hospital in Porur is a premier multi-specialty hospital known for offering world-class medical care across a wide range of specialties. It provides advanced healthcare services, including critical care, surgery, and organ transplantation, along with state-of-the-art technology. MIOT is known for its commitment to patient care and is recognized as one of the leading healthcare institutions in Chennai.
</font></p>
</body>
</html>


ramachandra.html
html
Copy
Edit
<html>
<head>
<title>Porur</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center"><font color="blue"><b>Porur</b></font></h1>
<h3 align="center"><font color="red"><b>Sri Ramachandra Medical College & Research Institute</b></font></h3>
<hr size="3" color="navy">
<p align="justify"><font face="Georgia" size="5">
Sri Ramachandra Medical College & Research Institute (SRMC) in Porur is one of the premier healthcare institutions in India. Known for its state-of-the-art medical facilities and academic excellence, SRMC offers undergraduate and postgraduate courses in medicine, dentistry, nursing, and allied health sciences. The institute is also recognized for its extensive research programs and world-class healthcare services. SRMC’s hospital provides comprehensive medical care and is equipped with advanced technology, making it a leader in the healthcare sector.
</font></p>
</body>
</html>


junction.html
html
Copy
Edit
<html>
<head>
<title>Porur</title>
</head>
<body bgcolor="lightyellow">
<h1 align="center"><font color="blue"><b>Porur</b></font></h1>
<h3 align="center"><font color="purple"><b>Porur Junction</b></font></h3>
<hr size="3" color="brown">
<p align="justify"><font face="Georgia" size="5">
Porur Junction is a busy intersection that connects major roads, including Mount-Poonamallee Road, Arcot Road, and Kundrathur Road. It serves as a crucial hub for commuters, with high traffic volumes and constant flow of vehicles. The junction is currently undergoing improvements to enhance traffic management, and its strategic location makes it an important node for connectivity to the rest of Chennai, making it vital for both locals and travelers.
</font></p>
</body>
</html>


lt.html
html
Copy
Edit
<html>
<head>
<title>Porur</title>
</head>
<body bgcolor="beige">
<h1 align="center"><font color="blue"><b>Porur</b></font></h1>
<h3 align="center"><font color="green"><b>Larsen & Toubro Headquarters</b></font></h3>
<hr size="3" color="white">
<p align="justify"><font face="Georgia" size="5">
Larsen & Toubro (L&T) Headquarters, located near Porur, is a major industrial center in Chennai. As one of India's leading engineering and construction companies, L&T plays a key role in executing large-scale projects across sectors such as infrastructure, power, and technology. The L&T campus in Porur is home to cutting-edge facilities and supports numerous global initiatives, contributing to the region's economic growth and development.
</font></p>
</body>
</html>
```
# OUTPUT
![Screenshot 2025-04-29 134032](https://github.com/user-attachments/assets/f5a8a0d9-8e08-4005-a589-2b7f5e8f79e3)

![Screenshot 2025-04-29 135012](https://github.com/user-attachments/assets/83d59e4b-4619-43ff-869e-9bf68ef73d45)

![Screenshot 2025-04-29 135030](https://github.com/user-attachments/assets/b4bfc612-0154-4c6e-9582-30390f8b54a0)

![Screenshot 2025-04-29 135046](https://github.com/user-attachments/assets/5ecb24dd-d9b7-42b5-9bb5-86d254f1d765)

![Screenshot 2025-04-29 135107](https://github.com/user-attachments/assets/5a183911-f8ed-4401-b672-e07f2fdb6c11)

![Screenshot 2025-04-29 135122](https://github.com/user-attachments/assets/4cdef194-d499-4f06-a502-183af2d1868e)



# RESULT
The program for implementing image maps using HTML is executed successfully.
