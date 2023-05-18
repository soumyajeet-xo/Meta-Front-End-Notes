Notes by Soumyajeet Bal

# Intro to UI Frameworks and Libraries

### Video 1 : Working with libraries
- library helps to reuse efficient piece of codes
- link bootstrap and rel attribute for stylesheet
- script and src to add javascript library
- dependency tree and package manager
- node package manager (npm)
- bundling tool - automatically compine dependencies into a single file; 
- gulp and webpack


### Video 2 : Introduction to responsive design
- Responsive design - automatically change visuals based on the device it is viewed on.
- flexible grids - gutter and margin
- css media queries - Display Size, Aspect Ratio, Orientation
- css fluid
- breakpoint 
- fixed grid
- fluid grid
- hybrid grid
- resolution : no. of horizontal pixel * no. of vertical pixel

Bootstrap is often described as a way to "build fast, responsive sites" and it is a "feature-packed, powerful, and extensible frontend toolkit". 

https://www.coursera.org/learn/introduction-to-front-end-development/supplement/EZ1Eu/bootstrap


### Video 3 :  Getting started with Bootstrap
- link to bootstap
- class container, row, col, img-fluid

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Page</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col">
                <h1>Our Menu</h1>
                <h2>Falafel</h2>
                <p>Chickpea, herbs, and spices</p>
                <img src="dale.png" alt="elephant" class="img-fluid">
                <h2>Pasta Salad</h2>
                <p>Lettuce, vegetables and mozzarella.</p>
                <img src="zaynn.jpg" alt="zaynn" class="img-fluid">
            </div>
        <div class="col">
            <h2>Prices</h2>
            <table class="table">
                <tr>
                    <td>Falafel</td>
                    <td>$12.00</td>
                </tr>
                <tr>
                    <td>Pasta Salad</td>
                    <td>$10.00</td>
                </tr>
            </table>
        </div>
    </div>
    </div>
</body>
</html>
```

### Video 4 : Using Bootstrap styles
- bootstrap css class in fixes modifiers
- breakpoint are trigger where visuals changes for different resolution
- breakpoint sm , md , lg , xl , xxl... bootstrap is mobile first
- primary, secondary, success, info, warning, danger
- alert alert-primary

### Video 5 : Bootstrap grid
- bootstrap grid system always has a container, row, coloumn
- ``` <div class="col-12 col-lg-6"> ``` to make breakpoints and reponsive
```
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <h1>Our Menu</h1>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6">
                <h2>Falafel</h2>
                <p>Chickpea, herbs, spices.</p>
                <h2>Fried Calamari</h2>
                <p>Squid, buttermilk.</p>
            </div>
            <div class="col-12 col-lg-6">
                <h2>Pasta Salad</h2>
                <p>Lettuce, vegetables, mozzarella.</p>
                <h2>Greek Salad</h2>
                <p>Cucumbers, onion, feta cheese.</p>
            </div>
        </div>
    </div>
</body>
```
### Bootstrap is basically a css framework. class can be used to import bootstrap various properties

### Video 6 : Bootstrap components
-  alert alert-info
-  


# Intro to UI Frameworks and Libraries

### Static and Dynamic content : 
- dynamic content are shown to users using application server
- application server have limitations on the number of request it can process in a given instance of time.
- thus we have web server and caching - web server keeps a copy of dynamic content.

### Single Page Applications (SPA): 
- Multipage website are resource intensive to web servers. i.e cpu time and high bandwidth.
- spa doesnt means website have 1 page. it means that one page is sent to from server to the browser and that page will update as the user interacts
- bundling and lazy loading
- 

### What is React? : 
- react help combine components
- reusable components

https://react.dev/

### Video 2 : 



