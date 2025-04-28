# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
<head>
<meta name="veiwport"
content="width=device-width,initial-sacale=1.0">
<style>
.bookpage{
width:400px;
height:600px;
color: white;
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: 'Franklin Gothic Medium','Arial Narrow',Arial,sans-serief;
background-image: url(bg.jpeg);
background-size: cover;
}

.insight{
color:cyan;
}

.hrstyle{
width: 100px;
}

.author{
display: inline;
position: relative;
color:violet;
top: 190px;
font-family: Georgia;
font-size: medium;
}


.booktitle{
font-family:'Courier New',Courier,manospace;
color:gold;
font-size: larger;
text-align: center;
position: relative;
top: 30px;
}

.id{
width:400px;
position: relative;
top:180px;
}

.pub{
font-size:medium;
position: relative;
color:plum;
top:155px;
left:330px;
}

.ed{
color:yellowgreen;
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
}

.subtitle{
font-family:Tahoma;
font-size:large;
position: relative;
top: 40px;
}


.mypic{
position:relative;
top:135px;
left:260px;
width:100px;
height:100px;
background-size:cover;
}

</style>
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="insight">
  SEC INSIGHT
</div>
<div class="booktitle">
<h1>THE WORLD WITHOUT WEB DEVOLOPMENT</h1></div>
<div class="subtitle">
FROM TODAY TO TOMORROW
</div>
<div class="mypic">
<img src="pho.jpg" width="130" height="145" alt="">
</div>
<div class="id">
<hr style="color:orange;">
</div>
<div class="author">
<p><b>P Manasa</b></p>
</div>
<div class="pub">
    SEC
</div>
<div class="ed">
<b>FIRST Edition</b>
</div>
</div>
</body>
</html>
```


## OUTPUT:
![Screenshot 2025-04-28 234244](https://github.com/user-attachments/assets/d7e1d0ee-9d94-43c1-843b-fceeafd4608f)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
