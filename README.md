# Ex.06 Book Front Cover Page Design
## Date:26/12/2025

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
Create a new HTML file in the bodystatic folder.

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
HTML code:

<html>
<head>
    <title>Book Cover</title>
    <link href="bb.css" rel="stylesheet">
</head>

<body>

<div class="box">
    <h2>About the Book</h2>
    <hr>

    <p>
        This book,<b>"Journey Through the Galaxy,"</b> offers a clear and inspiring introduction to the wonders of our universe. 
        It explores how galaxies form, the life cycle of stars, cosmic structures, and the mysteries hidden in deep space. 
        With simple explanations and stunning concepts, the book helps readers understand the beauty, science, and secrets of the cosmos.
         Perfect for anyone curious about space and the infinite world beyond our planet.
    </p>

    <div class="quote">
        "The galaxy isn't just out there ~~~ it's a journey our curiosity begins."
    </div>

    
    <div class="author">
        <img src="Vijay.jpg" alt="Author Photo">

        <p>
            <b>VIJAY D(25015213)</b><br>
            <br>
            As a student of Saveetha Engineering College and studying b.tech in AIDS department.
            

        </p>
    </div>

    <div class="footer">
        <div>Jananayagan Publishers<br>Printed in India</div>
        <div><b>Price: ₹599</b></div>
    </div>

</div>

</body>
</html>

CSS code:


 body {
            font-size: Arial;
            background:linear-gradient(to bottom,black,green);
        }
        .box {
            height: 700px;
            width: 500px;
            background-image:url(image1.jpg);
            background-size: cover;
            background: darkmagenta;
            color:white;
            padding: 20px;
            margin: 30px auto;
            border: 2px solid white;
            border-radius: 10px;
        }
        .quote {
            background: goldenrod;
            padding: 10px;
            border-left: 4px solid blue;
            margin: 20px 0;
            font-style: italic;
            text-align: center;
            border-end-end-radius: 10px;
        }
        .author {
            display: flex;
            gap: 15px;
            background:navy;
            padding: 10px;
            border-start-end-radius: 8px;
        }
        .author b{
            color:cyan;
        }
        .author img {
            width: 100px;
            height: 100px;
            border-radius: 5px;
        }
        .footer {
            background: darkblue;
            color: white;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            margin-top: 250px;
            border-end-end-radius: 5px;
        }
```

## OUTPUT:

![alt text](<Screenshot 2025-12-26 155521.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
