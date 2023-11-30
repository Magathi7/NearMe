# Ex04 Places Around Me
## Date: 29/11/2023

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
<title>MAP</title>
</head>
<body bgcolor="lavender">
<center>
<font size="6" color="red"><b>Mannargudi</b></font>
<br>
<h3 text="black">MAGATHI (23008030)</h3>
<img src="map.png" usemap="#MAP" width="1500" height="600" border="2">
<map name="MAP">
<area shape="rect" coords="1000,270,900,900" href="MrGvntclg.html" title="COLLEGE">
<area shape="rect" coords="1500,200,800,800" href="theatre.html" title="THEATRE">
<area shape="rect" coords="2000,300,700,700" href="school.html" title="SCHOOL">
<area shape="rect" coords="1600,100,850,850" href="mahall.html" title="MAHALL">
<area shape="rect" coords="1000,200,750,750" href="railway.html" title="RAILWAY">
</map>
</center>
</body>
</html>

mahall.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PP Mahall</title>
</head>
<body bgcolor="green">
    <h1 align="center">PP Mahall </h1>
    <p>PP Mahall is one of best mahall in mannargudi . It is located in nearby driving school.A "mahall" typically refers to a neighborhood or local community. In many cultures, the mahall embodies a sense of belonging and shared identity among its residents. It is often characterized by close-knit relationships, where neighbors become an extended family. Within the mahall, communal bonds are strengthened through shared traditions, celebrations, and everyday interactions. The streets and local establishments become familiar landmarks, and the mahall serves as a backdrop for the everyday rhythms of life. It is in these neighborhoods that one can witness the tapestry of diverse lives woven together, creating a unique and vibrant mosaic that contributes to the rich fabric of a city or town.</p>
</body>
</html>

MrGvntclg.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MR GOVERNMENT ARTS COLLEGE</title>
</head>
<body bgcolor="blue">
    <h3 align="center">Welcome to MR Government Arts College<br><hr>

        The rural and underprivileged people of Mannargudi region found it difficult to pursue higher education as there was no college in this area. So, a few good people whoe were interested in social welfare decided to found a college in Mannargudi. Many philanthropists of this area helped establish a college and thereby educate the youth of this rural and underdeveloped area.
        <br>
              A committee was formed to collect fund to achieve the end of founding a government college in Mannargudi. While the District Collector of Tanjore presided over the Comkittee, The Revenue Divisional Officer was its Secretary and Mr. T.G. Chandrasekaran Chettiyar was its Treasurer. Many philanthropists, religious and other organisations of Mannargudi and its nearby places helped enormously to construct the college building. The notable ones of them are:
        <br><br><br>
        Mannargudi Rajagopalaswamy Temple<br>
        The Muslim League of Koothanallur<br>
        K.R.M. Estate Charity<br>
        Kottur Kozhundheeswaraswamy Temple<br>
        Mr. T. Partharasarathi Naidu</h3>
</body>
</html>

railway.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAILWAY STATION</title>
</head>
<body bgcolor="purple">
    <h1>MANNARGUDI RAILWAY STATION</h1>
    <p>Mannarkudi railway station is one of the old railway station.The railway station is a bustling hub that pulsates with the energy of travelers embarking on journeys or returning home. It stands as a gateway to exploration, connecting distant places through a network of tracks and trains. Commuters hustle along platforms, vendors offer snacks and newspapers, and the rhythmic clatter of departing and arriving trains permeates the air. There's a sense of anticipation and farewell, as families bid adieu and reunite on the platforms. The station, with its distinct blend of diverse faces and destinations, encapsulates the essence of mobility and the continuous flow of life. As the locomotives arrive and depart, the railway station serves as a dynamic crossroads where stories begin and intertwine, echoing the constant movement inherent in the world of railways.</p>
</body>
</html>

school.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri Bharathidhasan School</title>
</head>
<body bgcolor="yellow">
    <h1>Sri Bharathidhasan Martriculation Hr.Sec.School</h1>
    <p align="center">Sri Bharathidhasan Marticulation School is one of the Best school in mannargudi.School is a crucial institution where students embark on a journey of learning and personal growth. Beyond the classroom, it serves as a microcosm of society, fostering friendships, collaboration, and the development of essential life skills. The curriculum spans a diverse range of subjects, from mathematics to literature, shaping well-rounded individuals. Teachers play a pivotal role, imparting knowledge and guidance, while extracurricular activities contribute to a holistic education. As students navigate the halls, they encounter challenges that build resilience and problem-solving abilities. In essence, school is not just a place of education; it's a foundation for the future, shaping minds and character.
    </p>
</body>
</html>

theatre.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LA cinema shanthi</title>
</head>
<body bgcolor="red",align="center">
    <h2>LA Cinema Shanthi</h2><br><hr>
    <p>LA cinema  is the best cinema theatre.It runs successfully in 15 years.One of the theatre in Mannarkudi.The theatre, a timeless art form, serves as a captivating medium for storytelling, weaving narratives that transcend time and culture. From the ancient amphitheaters of Greece to the modern stages of Broadway, theatre has evolved but retained its essence as a powerful means of expression. It brings characters to life, explores complex emotions, and delves into the human experience with an immediacy that resonates with audiences. The threatre is a space where creativity flourishes, where actors, directors, and playwrights collaborate to craft a unique, immersive experience for spectators. It serves not only as entertainment but also as a mirror reflecting societal values, challenging norms, and fostering empathy. The threatre, though often perceived as a safe haven for artistic expression, faces challenges such as changing audience preferences and financial constraints. Yet, its ability to connect people through shared stories ensures its continued relevance and significance in the cultural landscape.</p>

</body>
</html>
```

## OUTPUT!
![Alt text](<Screenshot (31).png>)
![Alt text](<Screenshot (32).png>)
![Alt text](<Screenshot (33).png>)
![Alt text](<Screenshot (34).png>)
![Alt text](<Screenshot (35).png>)
![Alt text](<Screenshot (36).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
