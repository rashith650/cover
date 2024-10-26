# Ex.06 Book Front Cover Page Design
## Date:26-10-2024

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Styles.css">
    <title>Book Cover Page</title>
</head>
<body>
    <div class="cover" >
        <img src="logo.png" alt="Logo" class="logo">
        <h1 class="book-title">The Elite Personality</h1>
        <p class="description">Better version of yourself</p><br><br><br><br><br><br><br><br><br>
        <h2 class="author">Michael</h2>
    </div>
</body>
</html>
```
Styles.css
```
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: gainsboro;
    font-family: Arial, sans-serif;
}

.cover {
    text-align: center;
    padding: 140px;
    border: 5px solid #35424a;
    border-radius: 15px;
    background-color:lightblue;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    width: 160px; 
    background-image: url('cover.jpeg');
    background-size: cover; 
    background-position: center; 
}

.logo {

    width: 100px; 
    margin-bottom: 20px;
    border-radius: 50px;
}

.book-title {
    font-size: 24px;
    color: #0d0d0d;
    margin: 10px 0;
}

.author {
    font-size: 18px;
    color: #0c0c0c;
    margin: 5px 0;
}

.genre, .publication-date, .isbn {
    font-size: 14px;
    color: #555;
    margin: 5px 0;
}

.description {
    font-size: 14px;
    color:black;
    margin-top: 15px;
}

.buy-button {
    margin-top: 20px;
    padding: 10px 15px;
    background-color: #28a745; /* Green color */
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.buy-button:hover {
    background-color: #218838; /* Darker green on hover */
}
```
## OUTPUT:

![Uploading Screenshot 2024-10-26 094148.png…]()

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
