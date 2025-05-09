# Ex.06 Book Front Cover Page Design
## Date:09.05.2025

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
`````
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      height: 100%;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      position: relative;
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1507842217343-583bb7270b66?auto=format&fit=crop&w=1050&q=80') no-repeat center center/cover;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
    }

    .overlay {
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.6);
    }

    .content {
      position: relative;
      text-align: center;
      padding: 20px;
      max-width: 90%;
    }

    .title {
      font-size: 3.5em;
      font-weight: bold;
      margin-bottom: 0.2em;
    }

    .subtitle {
      font-size: 1.5em;
      margin-bottom: 1em;
      font-style: italic;
    }

    .author {
      font-size: 1.2em;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="overlay"></div>
    <div class="content">
      <h1 class="title">The Edge of Tomorrow</h1>
      <p class="subtitle">A Journey Beyond Imagination</p>
      <p class="author">by Jane Doe</p>
    </div>
  </div>
</body>
</html>
`````


## OUTPUT:
![image](https://github.com/user-attachments/assets/16bcf4b6-99e1-4d51-bc13-43bc9f34454a)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
