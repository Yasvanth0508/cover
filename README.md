# Ex.06 Book Front Cover Page Design
## Date:15/05/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bookcover</title>
     <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
     <style>
        .bg img{
            width: 40%;
            margin-left: 27%;
            height: 750px;
            position: relative;
        }
        .content{
            position: absolute;
            color:  aliceblue;
            left: 36%;
            top: 3%;
        }
        .content h1{
            font-size: 51px;
        }
        .content h2{
            font-size: 36px;
            position: absolute;
            right: 5%;
            margin-top: 0px;
        }
        .c1{
            display: inline;
            position: absolute;
            top: 30%;
            left: 30%;
            margin-top: 0px;
            font-size: 20px;
            color: aliceblue;
        }
        .c2{
            top: 34%;
            position: absolute;
            left: 51%;
        }
        .c3{
            position: absolute;
            top: 55%;
            left: 30%;
            font-size: 20px;
            color: aliceblue;
        }
        .c4{
            position: absolute;
            top: 60%;
            left: 51%;
            font-size: 29px;
            color: aliceblue;
        }
    </style>
</head>
<body>
    <div class="bg">
        <img src="back.jpeg"> 
    </div>

    <div class="content">
        <h1>Art Of Code</h1>
        <h2>Part - 1</h2>
    </div>
    <div class="c1">
        <h3>"Approach code like a quest:<br>
             every bug is a boss fight,<br>
             a every concept a power-up.<br>
             and Level up daily—your final<br>
             the form is a software wizard."</h3>
    </div>
    <div class="c2">
        <img src="myphoto.png" width="40%">
    </div>
    <div class="c3">
        <h2>Author</h2>
        <h3> - Yasvanth RD</h3>
    </div>
    <div class="c4">
        <h2>Let's Craft <br>Your Code</h2>
    </div>
</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot 2025-05-15 105615.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
