# Ex.08 Design of Interactive Image Gallery
## Date: 20.05.25

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body {
            font-family:cursive;
            background-color:rgb(32, 28, 28);
            display:flex;
            justify-content: center;
            align-items: center;
            margin: 0;
            flex-direction: column;
            
        }
        .photo-container {
            text-align: center;
            color:aquamarine;
            font-size:medium;
        }

        .photo {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px; 
        }

        .photo-item {
            width: 350px; 
            height:500px;
                }
        footer {
            text-align: center;
            font-size: 25px;
            background-color:darkolivegreen;
            margin-top: 250px; 
            color:black;
        }

    </style>
</head>
<body>
    <div class="photo-container">
        <h1 >GALLERY OF NATURE</h1>
        <div class="photo">
            <img src="image.avif" alt="Image 1" class="photo-item" id="image" onmouseover="zoomIn()" onmouseout="zoomOut()">
            <img src="a-view-from-treasure.jpg" alt="Image 2" class="photo-item">
            <img src="North-East.jpg" alt="Image 3" class="photo-item">
            <img src="Gangotri-Glacier-Shivaling-Peak-lake-Himalayas-India.webp" alt="Image 4" class="photo-item">
            <img src="peru-rainbow-mountain-main.jpg  " alt="Image 5" class="photo-item">
            
        </div>
        <footer>
            Designed and developed by Abisha Linu &copy 2024
        </footer>
    </div>
    <script> 
    function zoomIn() { 
    document.getElementById("image").style.width = "600px";
      document.getElementById("image").style.height = "700px";

    } 
    function zoomOut() { 
      document.getElementById("image").style.width = "350px"; 
      document.getElementById("image").style.height = "500px";
      

    } 
    </script>
</body>
</html>

```

## OUTPUT:
![alt text](image-1.png)
![alt text](image.png)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
