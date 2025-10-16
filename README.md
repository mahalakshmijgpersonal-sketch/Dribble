# Project Responsive Web Design using Bootstrap
## Date:16.10.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Dribble Landing Page</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>

    <body>
        <h1>Dribbble</h1>
        <nav class="navbar navbar-inverse">
            <div class="container-fluid">
               
                <ul class="nav navbar-nav">
                    <li><a href="#">Shots </a>
                    <a href="#">Designers </a>
                    <a href="#">Teams </a>
                    <a href="#">Community </a>
                    <a href="#">Jobs </a>
                    <a href="#">...</a></li>
                </ul>
                <ul class="nav navbar-nav navbar-right">
                    <li><a href="#">Sign up</a>
                    <a href="#">Sign in</a></li>
                </ul>
                
            </div>
        </nav>
        <div class="bg-dark text-center text-white">
            <p>What are you working on? Dribble is show and tell for designers.
                <button type="button" class="btn btn-secondary">Learn more</button>
                <button type="button" class="btn btn-danger">Sign up</button></p>
        </div>
        <nav class="navbar navbar-default">
            <div class="container-fluid text-center">
                <ul class="nav navbar-nav">
                    <li><a href="#">Popular</a>
                        
                    <a href="#">Shots</a>
                        
                    <a href="#">Now</a>
                        
                    </li>
                </ul>
            </div>
        </nav>
        <div class="container">
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="cafe.png" class="card-img-top" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Cafe</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="coconut.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Coconut</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="chocolate.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Chocolate</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="citrus.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Citrus</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="frause.png" class="card-img-top" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Frause</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="gascar.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Gascar</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="mandarine.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Mandarine</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="menthe.png"class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Menthe</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="passion.png" class="card-img-top" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Passion</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="tramphorse.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Tramphorse</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="violette.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Violette</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="caramel.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Caramel</p>
                </div>
            </div>
        </div>
        </div>
        <footer class="copyrights text-center">
            &copy;J Mahalakshmi (25008001)
        </footer>
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-10-16 154839.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
