# Design of Responsive Website
## AIM:
To design a responsive website with two break points.

## DESIGN STEPS:
### Step 1: 
Requirement collection.
### Step 2:
Creating the layout using HTML and CSS.
### Step 3:
Updating the sample content.
### Step 4:
Choose the appropriate style and color scheme.
### Step 5:
Validate the layout in various browsers.
### Step 6:
Validate the HTML code.
### Step 7:
Create a database model and migrate the database.
### Step 8:
Retrieve data from database and display it in a dynamic webpage.
### Step 9:
Publish the website in the given URL.

## PROGRAM:

## productsresponsive.html:
```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Responsive Product Design</title>
  </head>
  <body>
    <div class="jumbotron"> 
        <div class="container text-center">                                                                    
        <h1 class="display-1">Silicone Private Limited</h1>
        <p class="lead">we manufacturing high quality electrinic products</p>
        </div>
    </div>
    <div>
    <div class="container">
        <div class="row text-center">
        <div class="col-12 col-md-3"><a href="#"> Home</a></div>
        <div class="col-12 col-md-3"><a href="#">Products</a></div>
        <div class="col-12 col-md-3"><a href="#">People</a></div>
        <div class="col-12 col-md-3"><a href="#">Contact Us</a></div>
        </div>
        <div>
            <div class="row text-center">
                <div class="col-12">
                <p class="lead">Our Premium Products</p>
                </div>
            </div>
            <div class="row text-center">
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c1.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">4GB DDRA4 laptop memory</h5>
                       <p class="card-text">Price: Rs.2000.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c2.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">1TB Laptop HDD</h5>
                       <p class="card-text">Price: Rs.5000.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c3.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">HP SSD EX900 M.2 250GB</h5>
                       <p class="card-text">Price: Rs.4000.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c4.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">Crucial P2 250GB 3D NAND</h5>
                       <p class="card-text">Price: Rs.50000.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c5.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">WD Blue PCIe NVMe SSD 250GB</h5>
                       <p class="card-text">Price: Rs.3485.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c6.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">Kingston 250GB A2000 M.2</h5>
                       <p class="card-text">Price: Rs.3400.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c7.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">Samsung 970 EVO Plus 250GB</h5>
                       <p class="card-text">Price: Rs.4600.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c8.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">WD Black PCIe NVMe SSD</h5>
                       <p class="card-text">Price: Rs.4900.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c9.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">Samsung 860 EVO 250GB SATA M.2</h5>
                       <p class="card-text">Price: Rs.3700.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c10.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">HP EX900 M.2 250GB PCIe 3.1</h5>
                       <p class="card-text">Price: Rs.4100.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c11.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">Seagate Barracuda 510 250GB SSD</h5>
                       <p class="card-text">Price: Rs.5300.00</p>
                       <a href="#" class="btn btn-primary">Order Now</a>
                   </div>
                </div>
                <div class="card col-12 col-md-3 col-lg-3">
                   <img class="card-img-top" src="/static/img/c12.jpg" alt="Card image cap">
                   <div class="card-body">
                       <h5 class="card-title">WD Blue 250GB M.2 Internal</h5>
                       <p class="card-text">Price: Rs.4700.00</p>
                       <a href="#" class="btn btn-primary btn-lg active" role="button" aria-pressed="true">Order Now</a>
                   </div>
                </div>
            </div>
        </div>
        <div class="row text-center">
            <div class="col-12">
                <p>Copyright © 2021 Silicon Private Limited, Developed by Tamil Venthan .</p>
            </div>
        </div>
    </div>    
    </div>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
```


## OUTPUT:
![output](./static/img/o1.jpg)
![output](./static/img/o2.jpg)
![output](./static/img/o3.jpg)
![output](./static/img/o4.jpg)
![output](./static/img/o5.jpg)
![output](./static/img/o6.jpg)
![output](./static/img/o7.jpg)


## RESULT:
Thus a website is designed for the chip manufacturing company and is hosted in the URL 
http://tamil.student.saveetha.in:8000/productsresponsive/. HTML code is validated.