# Ex.06 Book Front Cover Page Design
## Date:08/10/2025

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
<html>
<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color : black
      background-size: cover;
      background-position: center;
      color: black;
      background-color: cyan;
    }
    .cover {
      width: 700px;
      height: 1000px;
      margin: 50px auto;
      padding: 30px;
      position: relative;
      background: rgba(255, 250, 240, 0.9); 
      border: 5px solid blueviolet; 
      border-radius: 2%;
      background-image:url(bg1.jpeg);
    }
    .top {
      font-size: 40px;
      font-weight: bold;
      color: red;
      text-align: left;
      letter-spacing: 2px;
    }
    .title {
      font-size: 60px;
      font-weight: bold;
      text-align: center;
      margin-top: 80px;
      color: limegreen;
      font-family: 'Times New Roman', serif;
    }
    .subtitle {
      font-size: 40px;
      text-align: center;
      margin-top: 30px;
      font-style: italic;
      color: violet;
    }
    .special {
      font-size: 40px;
      font-weight: bold;
      margin-top: 480px;
      color: orangered;
      text-align: left;
    }
    .author {
      font-size: 30px;
      font-weight: bold;
      color: white;
      margin-top: 25px;
      text-align: left;
    }
    .sec {
      position: absolute;
      bottom: 30px;
      right: 20px;
      font-size: 18px;
      color: white;
    }
    .photo {
      width: 150px;
      height: 200px;
      position: absolute;
      bottom: 60px;
      right: 100px;
      border-radius: 8px;
      border: 2px dotted yellow;
      box-shadow: 0 0 10px black
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="top">SEC Insights</div>
    
    <div class="title">
      SHAPING THE FUTURE<br>
        WITH TECHNOLOGY
    </div>
    
    <div class="subtitle">
      Technology drives progress<br>
      innovation shapes tomorrow
    </div>
    
    <div class="special">SPECIAL EDITION</div>
    
    <img src="mypic.jpg" class="photo" alt="Author Photo">
    
    <div class="author">VIVEK CHRISTO A(25013444)</div>
    
    <div class="sec">SEC</div>
  </div>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (55).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
