# Ex04 Places Around Me
## Date: 

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
### mapapp.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAP</title>
</head>
<body bgcolor="cyan">
    <h1>kanya kumari-God's own country</h1>
    <h2>212223100001</h2>
    <img src="map.png.png"  usemap="#image-map">

<map name="image-map">
    <area target="" alt="Mangrove forest" title="Mangrove forest" href="Mangrove.html" coords="300,254,106" shape="circle">
    <area target="" alt="Arockiapuram chruch" title="Arockiapuram chruch" href="Arockiapuram.html" coords="1310,197,1028,128" shape="rect">
    <area target="" alt="Kanniyakumari" title="Kanniyakumari" href="Kanniyakumari.html" coords="1132,598,1345,633" shape="rect">
    <area target="" alt="Vattakottai Fort" title="Vattakottai Fort" href="Vattakottai.html" coords="1565,58,114" shape="circle">
    <area target="" alt="Themthamaraikulam" title="Themthamaraikulam" href="Thenthamaraikulam.html" coords="639,446,169" shape="circle">
</map>
</body>
</html>
```
### Thenthamaraikulam.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thenthamarai</title>
</head>
<body bgcolor="blue">
    <center><h1>Thenthmarai is a panchayat town in Kanniyakumari district</h1></center>
    <p>Thenthamaraikulam had a population of 11,068. Males constitute 49% of the population and females 51%. Thenthamaraikulam has an average literacy rate of 82%, higher than the national average of 59.5%: male literacy is 84%, and female literacy is 81%. In Thenthamaraikulam, 10% of the population is under 6 years of age.</p>
    
</body>
</html>
```
### Vattakottai.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vattakottai</title>
</head>
<body bgcolor="yellow">
    <center><h1>Vattakottai Fort is a seaside fort near Kanyakumari,</h1></center>
    <p>It was constructed in the 18th century by Punachal/Elakkara Valiyaveetil Marthandan Chempakaraman Pillai for the kings of Travancore. Marthanda Pillai was born in an aristocratic house in Punachal Elakkara near Kuzhikode near Palliyadi in Kanyakumari district. (Then South Travancore). The house was a house that was associated with the royal family. Marthanda Pillai was born in the month of May 903 in Bharani Nakshatra, the son of Neelamma Pillai, a member of the said house, and Iravikurup, the bodyguard of Marthanda Varma. Later it was modified under the supervision of Captain Eustachius De Lannoy, an ex-Dutch naval officer of the Dutch East India Company, who became commander of the Travancore Army (the very army that defeated him in the Battle of Colachel) in the 18th century, after he earned the trust of the Travancore King Marthanda Varma. De Lannoy reconstructed Vattakottai, as part of the defence-fortifications he undertook throughout Travancore.</p>
</body>
</html>
```
### Kanniyakumari.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kanniyakumari</title>
</head>
<body bgcolor="grey">
    <center><h1>Cape Comorin</h1></center>
    <p>Kanyakumari is a popular tourist destination and pilgrimage centre in India. Notable tourist spots include its unique sunrise and sunset points, the 41-metre (133 ft) Thiruvalluvar Statue, and Vivekananda Rock Memorial off the coast.[1] Lying at the tip of peninsular India, the town is bordered on the west, south, and east by the Laccadive Sea.[2] It has a coastline of 71.5 kilometres (44.4 mi) stretched along these three sides.[3]

        On the shores of the city is a temple dedicated to the Hindu goddess Kanya Kumari (the virgin goddess), after which the town is named.[4] Kanyakumari has been a town since the Sangam period and was referred to in old Malayalam literature and in the accounts of Ptolemy and Marco Polo</p>
</body>
</html>
```
### Arockiapuram.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kanniyakumari</title>
</head>
<body bgcolor="grey">
    <center><h1>Cape Comorin</h1></center>
    <p>Kanyakumari is a popular tourist destination and pilgrimage centre in India. Notable tourist spots include its unique sunrise and sunset points, the 41-metre (133 ft) Thiruvalluvar Statue, and Vivekananda Rock Memorial off the coast.[1] Lying at the tip of peninsular India, the town is bordered on the west, south, and east by the Laccadive Sea.[2] It has a coastline of 71.5 kilometres (44.4 mi) stretched along these three sides.[3]

        On the shores of the city is a temple dedicated to the Hindu goddess Kanya Kumari (the virgin goddess), after which the town is named.[4] Kanyakumari has been a town since the Sangam period and was referred to in old Malayalam literature and in the accounts of Ptolemy and Marco Polo</p>
</body>
</html>
```
### Mangrove.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kanniyakumari</title>
</head>
<body bgcolor="grey">
    <center><h1>Cape Comorin</h1></center>
    <p>Kanyakumari is a popular tourist destination and pilgrimage centre in India. Notable tourist spots include its unique sunrise and sunset points, the 41-metre (133 ft) Thiruvalluvar Statue, and Vivekananda Rock Memorial off the coast.[1] Lying at the tip of peninsular India, the town is bordered on the west, south, and east by the Laccadive Sea.[2] It has a coastline of 71.5 kilometres (44.4 mi) stretched along these three sides.[3]

        On the shores of the city is a temple dedicated to the Hindu goddess Kanya Kumari (the virgin goddess), after which the town is named.[4] Kanyakumari has been a town since the Sangam period and was referred to in old Malayalam literature and in the accounts of Ptolemy and Marco Polo</p>
</body>
</html>
```

## OUTPUT
![Screenshot 2024-03-22 094331](https://github.com/Aaron-0111/NearMe/assets/149347631/e1c41bb4-4cea-4db5-8b2a-d8f4452b4d3f)
![Screenshot 2024-03-22 094347](https://github.com/Aaron-0111/NearMe/assets/149347631/62e823d8-da55-4fc2-aa02-9c423d1badf1)
![Screenshot 2024-03-22 094448](https://github.com/Aaron-0111/NearMe/assets/149347631/3793c723-cfd7-46e7-9f26-d3243cc033f1)
![Screenshot 2024-03-22 094410](https://github.com/Aaron-0111/NearMe/assets/149347631/460b59da-781b-42ad-9663-395083c916a5)
![Screenshot 2024-03-22 094433](https://github.com/Aaron-0111/NearMe/assets/149347631/1f93cc40-30fd-4df5-a5aa-95e7f715f353)
![Screenshot 2024-03-22 094502](https://github.com/Aaron-0111/NearMe/assets/149347631/b59e6a0d-6995-4166-9623-778153fb88dc)







## RESULT
The program for implementing image maps using HTML is executed successfully.
