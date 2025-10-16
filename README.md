# Project Responsive Web Design using Bootstrap
## Date:15.10.2025

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
        <title>dribble</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-inverse">
            <div class="container-fluid">
                <div class="navbar-header">
                    <a class="navbar-brand" href="#">Dribble</a>
                </div>
                <ul class="nav navbar-nav">
                    <li><a href="#">Shots</a></li>
                    <li><a href="#">Designers</a></li>
                    <li><a href="#">Teams</a></li>
                    <li><a href="#">Community</a></li>
                    <li><a href="#">Jobs</a></li>
                </ul>
                <ul class="nav navbar-nav navbar-right">
                    <li><a href="#">login</a></li>
                    <li><a href="#">Sign in</a></li>
                </ul>
                
            </div>
        </nav>
        <div class="bg-dark text-center">
            <p>New update ! , click here and learn more .</p>
                <button type="button" class="btn btn-success">read</button></p>
        </div>
        <nav class="navbar navbar-default">
            <div class="container-fluid">
                <ul class="nav navbar-nav">
                    <li class="dropdown"><a href="#">Page</a>
                        <ul class="dropdown-menu" >
                			<li><a href="#">page 1</a></li>
                			<li><a href="#">Page 2</a></li>
                			<li><a href="#">Page 3</a></li>
                        </ul>
                    </li>
                    </ul>
            </div>
        </nav>
        <div class="container">
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="vvv.jpg" class="card-img-top" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Kim Taehyung</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="jkkk.jpg" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Joen Jungkook</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="jiminn.jpg" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Park jimin</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="rmmmm.jpg" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Kim Namjoon</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="suga.jpg" class="card-img-top" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Min yoongi</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="jinn.jpg" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Kim soek jin</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="hpoe.jpg"img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Jhope</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="bts.jpg" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">Worlds Biggest Band</p>
                </div>
            </div>
        </div>
                </div>
        </div>
        </div>
        <footer class="copyrights text-center">
            &copy; Samantha Shree S.V (25017585)
        </footer>
    </body>
</html>

  
```

## OUTPUT:
![alt text](<Screenshot (71).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
