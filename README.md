# Ex.06 Book Front Cover Page Design
## Date: 14/5/25

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #1e5f41; /* Purple background */
      font-family: 'Courier New', monospace;
      color: #80d4ff; /* Light blue text */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .cover {
      width: 400px;
      height: 600px;
      padding: 50px 30px;
      box-sizing: border-box;
      background-color: #3c1e5f;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .top-label {
      color: #aaffaa;
      font-size: 14px;
    }

    .line {
      height: 2px;
      background-color: #80d4ff;
      margin: 10px 0;
    }

    .title {
      font-size: 26px;
      font-weight: bold;
      line-height: 1.4;
    }

    .subtitle {
      font-size: 16px;
    }

    .edition {
      font-size: 16px;
    }

    .author {
      font-size: 22px;
      font-weight: bold;
      color: #80d4ff;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div>
      <div class="top-label">SEC INSIGHT</div>
      <div class="line"></div>
    </div>

    <div>
      <div class="title">Fundamentals of<br>Web Application<br>Development</div>
      <div class="subtitle">HTML and CSS Combined with<br>Django Architecture</div>
    </div>

    <div>
      <div class="edition">First Edition</div>
      <div class="line"></div>
      <div class="author">Harshavarthini</div>
    </div>
  </div>
</body>
</html>
~~~

## OUTPUT:
![image](https://github.com/user-attachments/assets/5ede05a0-4654-44bd-ad60-0d085509731f)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
