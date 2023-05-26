# Ex04 Places Around Me
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Clone the github repository into Theia IDE.

### STEP 2
Create a new Django project

### STEP 3
Write the needed HTML code.

### STEP 4
Run the Django server and execute the HTML files.

### STEP 5
Execute the programs and publish them.


## CODE
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Pudukkottai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>M.PRAKASH 212222100035</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/bus.html" title="Bus Stand">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/hotel.html" title="Restaurnts">
<area shape="circle" coords="400,350,50" href="/static/html/hospital.html" title="GH">
<area shape="circle" coords="400,200,75" href="/static/html/college.html" title="COLLEGE">

</map>
</center>
</body>
</html>

bus.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Pudukkottai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Pudukkottai Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
The Pudukkottai Bus Stand, also known as the Pudukkottai Mofussil Bus Stand, is situated in the heart of the city, making it easily accessible to both residents and tourists. It is the primary bus terminal in Pudukkottai, connecting the city with various other towns and cities in Tamil Nadu and neighboring states.
</b>
</font>
</p>
</body>
</html>

hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Restarunt</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Pudukkottai</b></font>
</h1>
<h3 align="center">
Periya Yeri<font color="blue"><b>Palaniappa Mess</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Palaniappa Mess is located in Pudukkottai, Tamil Nadu. This business is working in the following industry: Restaurants.
</font>
</p>
</body>
</html>


hospital.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>GH</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Pudukkottai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>>Pudukkottai GH</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
The college was sanctioned by late former Chief Minister Selvi J.Jayalalitha in August 2015[4] and she laid the foundation for the college and hospital on 1 March 2016.[5] It was inaugurated by the then Chief Minister of Tamil Nadu, Edappadi K. Palaniswami, on 9 June 2017.
</b>
</font>
</p>
</body>
</html>

college.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>COLLEGE</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Pudukkottai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Pudukkottai Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Government Arts College for Women, Pudukkottai, is a women's general degree college located in Pudukkottai, Tamil Nadu. It was established in the year 1965. The college is affiliated with Bharathidasan University. This college offers different courses in arts, commerce and science</b>
</font>
</p>
</body>
</html>
~~~


## OUTPUT

![out1](https://github.com/Prakashmathi2004/NearMe/assets/118350045/76a3f430-654a-474b-9e5b-17285c60e6fd)


![out2](https://github.com/Prakashmathi2004/NearMe/assets/118350045/443532d6-de2d-4899-8c89-22324cf0ab2a)

![out3](https://github.com/Prakashmathi2004/NearMe/assets/118350045/0f046d06-283a-4b1a-992c-da45373db2f0)

![out4](https://github.com/Prakashmathi2004/NearMe/assets/118350045/6be4673c-f031-4775-98d0-5c6c2494baa8)

![out5](https://github.com/Prakashmathi2004/NearMe/assets/118350045/0aff13f1-7e22-4ece-af74-ad1dbfbcfcf9)




## HTML VALIDATOR

![valid](https://github.com/Prakashmathi2004/NearMe/assets/118350045/3f07191d-d188-4d6f-bbc5-bae63756cc24)


## RESULT
The program for implementing image maps using HTML is executed successfully.
