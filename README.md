# Ex.06 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
restaraunt.html

<html>
    <head>
        <title>Madras Suvai</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
        <h1>MADRAS SUVAI </h1>
        <div class="navigation">
            <a href="restaraunt.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administration.html">ADMINISTRATION</a>
        </div>
        <br>
        <br>
        <h2>From Chennai Streets to Your Plate</h2>
        <br><br>
        <h3>
            Time-honoured South Indian recipes, cooked the traditional way.
        <br>Every meal tells a story of Tamil Nadu.
        </h3>
    </body>
    <br><br>
    <footer>
        <p>&copy;SRIRAM.S (25006750)</p>
    </footer>
<html>

styles.css

body{
    background-image: url('rest2.webp');
    background-repeat: no-repeat;
    background-size:cover;
    margin: auto;
}
h1{
    font-style: initial;
    text-align: center;
    color: rgb(157, 3, 3);
}
.navigation{
    text-align: center;
    margin-left: 10px;
}
a{
    color: black;
    display: inline;
    font-size:larger;
    padding: 10px 10px;
}
h2{
    font-style: italic;
    font-size: 60px;
    margin-left: 10px;
}
h3{
    font-style: italic;
    font-size: 30px;
    margin-bottom: 250px;
    margin-left: 10px;
}
footer{
    text-align: center;
    color: brown;
    background-color: cyan;
}

menu.html

<html>
    <head>
        <title>MENU</title>
        <link href="menu.css" rel="stylesheet">
    </head>
    <body>
        <h1>MENU</h1>
        <div class="navigation">
            <a href="restaraunt.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administration.html">ADMINISTRATION</a>
            <br><br><br><br>
        </div>
        <div class="menubar">
            <div class="food">
            <img src="appam.jpeg">
                <h3>APPAM</h3>
                <h4> Price=Rs-60</h4>
            </div>
            <div class="food">
                <img src="dosa.jpeg">
                <h3>DOSA</h3>
                <h4> Price=Rs-50</h4>
            </div>
            <div class="food">
                <img src="idli.webp">
                <h3>IDLI</h3>
                <h4> Price=Rs-40</h4>
            </div>
            <div class="food">
                <img src="meals.jpeg">
                <h3>MEALS</h3>
                <h4> Price=Rs-130</h4>
            </div>
            <div class="food">
                <img src="parotta.avif">
                <h3>PAROTTA</h3>
                <h4> Price=Rs-50</h4>
            </div>
            <div class="food">
                <img src="pongal.avif">
                <h3>PONGAL</h3>
                <h4> Price=Rs-60</h4>
            </div>
            <div class="food">
                <img src="poori.jpeg">
                <h3>POORI</h3>
                <h4> Price=Rs-50</h4>
            </div>
        </div>
    </body>
    <br><br><br><br><br><br>
    <footer>
        <p>&copy;SRIRAM.S (25006750)</p>
    </footer>
</html>

menu.css

body{
    background-image: url('rest4.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
h1{
    text-align: center;
    font-style: normal;
    color: cadetblue;
    margin-top: 20px;
    font-size: 40px;
}
.navigation{
    text-align: center;
    margin-left: 10px;
}
a{
    color: rgb(195, 177, 177);
    display: inline;
    font-size:larger;
    padding: 10px 10px;
    font-style: normal;
    font-size: 25px;
}
h1{
    background: none;
}
.menubar {
    display: flex;
    gap: 35px;
    width: 150%;
    margin: 100px;
}
.food {
    background-color: rgb(182, 162, 17);
    padding: 10px;
    text-align: center;
    border-radius: 8px;
    
}
.food img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}
footer{
    text-align: center;
    font-size: larger;
    background-color: aqua;
}


contact.html

<html>
    <head>
        <title>CONTACT</title>
        <link href="contact.css" rel="stylesheet">
    </head>
    <body>
        <h1>CONTACT</h1>
        <div class="navigation">
            <a href="restaraunt.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administration.html">ADMINISTRATION</a>
            <br><br><br><br>
        </div>
        <h2>Location</h2>
        <p><b>Madras Suvai</b>
        <br>
        poonamalle main road
        <br>
        chennai-56
        <br>
        TamilNadu
        </p>
        <h2>Email</h2>
        <p>madrassuvai@gmail.com</p>
        <h2>Telephone No</h2>
        <p>9535454545<br>6383284341</p>
    </body>
    <footer>
        <p>&copy;SRIRAM S(25006750)</p>
    </footer>
</html>

contact.css

body{
    background-image: url('rest5.webp');
    background-repeat: no-repeat;
    background-size: cover;
}
h1{
    font-style: initial;
    text-align: center;
    color: rgb(21, 152, 222);
}
.navigation{
    text-align: center;
    margin-left: 10px;
}
a{
    color: rgb(26, 1, 1);
    display: inline;
    font-size:larger;
    padding: 10px 10px;
}
h2{
    text-align: center;
    font-style: inherit;
    font: size 40px;
    color: blue;
    margin-bottom: 15px;
}
p{
    text-align: center;
    font-style: italic;
    color: rgb(213, 10, 183);
}
footer{
    text-align: center;
    background-color: aquamarine;
    margin-top: 85px;
}

administration.html

<html>
    <head>
        <title>administration</title>
        <link href="administration.css" rel="stylesheet">
    </head>
    <body>
        <h1>ADMINISTRATION</h1>
        <div class="navigation">
            <a href="restaraunt.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administration.html">ADMINISTRATION</a>
            <br><br><br><br>
        </div>
        <div class="admin">
            <div class="members">
                <img src="sriram.1.jpeg">
                <h3>SRIRAM</h3>
                <h3>CEO</h3>
            </div>
            <div class="members">
                <img src="ajith2.avif">
                <h3>AJITH KUMAR</h3>
                <h3>CHAIRPERSON</h3>
            </div>
            <div class="members">
                <img src="dhoni.jpg">
                <h3>DHONI</h3>
                <h3>DIGITAL MANAGER</h3>
            </div>
            <div class="members">
                <img src="messi4.jpg">
                <h3>MESSI</h3>
                <h3>ASSISTANT MANAGER</h3>
            </div>
            <div class="members">
                <img src="kolhi5.webp">
                <h3>KOLHI</h3>
                <h3>SENIOR MANAGER</h3>
            </div>
            <div class="members">
                <img src="rohit6.jpg">
                <h3>ROHIT</h3>
                <h3>EXECUTIVE</h3>
            </div>
        </div>
    </body>
    <footer>
        <p>&copy;SRIRAM S(25006750)</p>
    </footer>
</html>

administration.css

body{
    background-image: url('rest6.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
h1{
    text-align: center;
    color: bisque;
    font-style:normal ;
}
.navigation{
    text-align: center;
    margin-left: 10px;
}
a{
    color: rgb(219, 6, 6);
    display: inline;
    font-size:larger;
    padding: 10px 10px;
}
.admin{
    display: flex;
    gap: 20px;
    width: 150%;
    margin: 100px;
}
.members{
    background-color:rgb(74, 110, 120);
    padding: 10px;
    text-align: center;
    border-radius: 8px;
}
.members img{
    width: 100%;
    height: 230px;
    object-fit: cover;
}
footer{
    text-align: center;
    background-color: aquamarine;
    margin-top: 85px;
}
```
## OUTPUT:
Include the Screenshot
![alt text](<Screenshot 2025-12-27 131504.png>)
![alt text](<Screenshot 2025-12-27 131448.png>)
![alt text](<Screenshot 2025-12-27 131434.png>)
![alt text](<Screenshot 2025-12-27 131422.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
