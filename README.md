# Ex.06 Book Front Cover Page Design
## Date:24/12/2025
## REFNO:25003242

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
~~~

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: #f0f0f0;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 350px;
      height: 500px;
      background: linear-gradient(to bottom right, #3a6186, #89253e);
      color: white;
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
      padding: 40px 20px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      border-radius: 10px;
      text-align: center;
      position: relative;
    }

    .book-title {
      font-size: 2em;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .book-subtitle {
      font-size: 1.2em;
      font-style: italic;
      margin-bottom: 40px;
    }

    .author {
      font-size: 1em;
      font-weight: 600;
      margin-bottom: 5px;
    }

    .footer {
      font-size: 0.8em;
      opacity: 0.8;
    }

    .author-photo {
      position: absolute;
      bottom: 20px;
      right: 20px;
      width: 80px;
      height: 80px;
      border-radius: 50%;
      border: 3px solid white;
      object-fit: cover;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>

<div class="book-cover">
  <div>
    <div class="book-title">The Journey Beyond</div>
    <div class="book-subtitle">A Tale of Dreams and Courage</div>
  </div>
  <div>
    <div class="author">by R K NIKKIL VARSHAN </div>
    <div class="footer">Published 2025</div>
  </div>
  <img src="your-photo.jpg" alt="Author Photo" class="author-photo">
</div>

</body>
</html>

~~~

## OUTPUT:
![temp1](https://github.com/user-attachments/assets/1393850b-ec8a-4fdf-9992-55f0afe7b531)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
