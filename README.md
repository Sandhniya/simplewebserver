# EX01 Developing a Simple Webserver
## Date:29.03.24

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    from http.server import HTTPServer, BaseHTTPRequestHandler
content = """
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MUSIC</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        a{
            padding: 10px;
            text-decoration: none;
            color:navy;
            font-family: arial;
            font-size: px;
        }
        a:hover{
            color: rgb(105, 139, 165);
        }   
    </style>
</head>
<body style="background-color:whitesmoke;">
     <div style="display:flex">
        <div style="width: 30%"><img style="width: 70%" src="logo.webp"></div>
        <div style="width: 55%;padding-top: 13px    ">
            <a href="   ">Home</a>
            <a href="">About</a>
            <a href="">Music</a>
            <a href="">Concet</a>
            <a href="">My List</a>
            <a href="">Browse by language</a>
        </div>  
        <div style="width: 20%;padding-top: 8px">
        <input style="width: 80%;height: 30px;background-image: url('search.jpeg');background-color: white; background-size: contain;background-repeat: no-repeat;padding-left: 40px;" type="text" placeholder="search" >
        </div>
     </div>
     
     <h1 style="color:white;text-align: center;font-style: italic;font-size: 50px;">MUSIC IN BREATH</h1>
     <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="c:\Users\admin\Desktop\web img 1.jpg" class="d-block w-100" alt="..." width="50%">
          </div>
          <div class="carousel-item">
            <img src="c:\Users\admin\Desktop\web img 2.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="c:\Users\admin\Desktop\web img 3.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="c:\Users\admin\Desktop\web img 4.jpg" class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
     <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>  
</body>
</html>


## OUTPUT:

![Screenshot 2024-03-29 185704](https://github.com/Sandhniya/simplewebserver/assets/151395890/2cf6e9df-c3df-4bd6-8830-5e04b6813995)



## RESULT:
The program for implementing simple webserver is executed successfully.
