# Project Responsive Web Design using Bootstrap
# Date:23/12/2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<html>
<head>
    <title>Pastel Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="{% static 'style.css' %}">
    <style>
        body {
    margin: 0;
    background-color: #fff6f8;
    font-family: "Segoe UI", sans-serif;
}

.pastel-nav {
    background-color: #e0ff70;
    padding: 12px 24px;
}

.navbar {
    display: flex;
    align-items: center;
    position: relative;
}

.navbar-brand {
    font-size: 18px;
    z-index: 1;
}

.navbar-nav {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    gap: 18px;
}

.nav-link {
    font-size: 14px;
    color: #333;
    padding: 4px 6px;
}

.navbar form {
    margin-left: auto;
}

.pastel-search {
    width: 150px;
    border-radius: 16px;
    border: none;
    padding: 4px 10px;
    font-size: 13px;
}

.hero {
    background: linear-gradient(90deg, #ff4080, #4fffff);
    padding: 18px 0;
    text-align: center;
    color: white;
}

.hero h2 {
    font-size: 30px;
    margin-bottom: 2px;
}

.hero p {
    font-size: 24px;
    margin-bottom: 6px;
}

.pastel-btn {
    background-color: white;
    color: #555;
    border-radius: 16px;
    padding: 4px 14px;
    font-size: 12px;
}

.filter-bar {
    display: flex;
    gap: 18px;
    font-size: 14px;
    color: #777;
}

.col-md-3 {
    width: 16.66%;
}

.shot-card {
    background: white;
    border-radius: 14px;
    padding: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.06);
}

.shot-card img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    border-radius: 10px;
}

.card-info {
    margin-top: 24px;
}

.title {
    font-size: 26px;
    font-weight: 600;
}

.stats {
    font-size: 22px;
    color: #ff2525;
}
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg pastel-nav px-4">
    <a class="navbar-brand fw-bold" href="#">Dribbble</a>

    <ul class="navbar-nav ms-4">
        <li class="nav-item"><a class="nav-link" href="#">Fashion</a></li>
        <li class="nav-item"><a class="nav-link" href="#">History</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Music</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Brands</a></li>
    </ul>

    <form class="d-flex ms-auto">
        <input class="form-control pastel-search" type="search" placeholder="Search">
    </form>
</nav>

<section class="hero text-center">
    <h2>creative works</h2>
    <button class="btn pastel-btn">Continue</button>
</section>

<div class="container my-4 filter-bar">
    <span>Now</span>
    <span>Yours</span>
    <span>Popular</span>
</div>

<div class="container">
    <div class="row g-4">

        <div class="col-md-2">
        <div class="shot-card">
            <img src="c:\Users\acer\Downloads\demon slayer infinity castle.avif" width="200px" height="150px">
                <div class="card-info">
                <div class="title">anime</div>
                <div class="stats">1.5k views · 1.5k likes · 1.5k shares</div>
            </div>
        </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
            <img src="c:\Users\acer\Downloads\lofigirl1.jpg" width="200px" height="150px">
            <div class="card-info">
            <div class="title">lofigirl</div>
            <div class="stats">5k views · 2.5k likes · 2k shares</div>
        </div>
        </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="200px" height="150px">
                <div class="card-info">
                <div class="title">Ambur-Chicken-Biriyani</div>
                <div class="stats">50k views · 27k likes · 10k shares</div>
            </div>
        </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-23 121014.png" width="200px" height="150px">
                <div class="card-info">
                <div class="title">blue</div>
                <div class="stats">500k views · 500k likes · 500k shares</div>
            </div>
        </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="c:\Users\acer\Downloads\ef0b5ef61eaf79fbc12d5343b9088b89.jpg" width="200px" height="150px">
                <div class="card-info">
                <div class="title">you have reached sam</div>
                <div class="stats">1m views · 1m likes · 1m shares</div>
            </div>
        </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-23 121602.png" width="200px" height="150px">
                <div class="card-info">
                <div class="title">Dance</div>
                <div class="stats">100k views · 77k likes · 36k shares</div>
            </div>
        </div>
        </div>

        
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-12-23 123647" src="https://github.com/user-attachments/assets/0c492901-c1d7-4448-a4fb-bd4562053815" />
# RESULT:


The Project for responsive web design using Bootstrap is completed successfully.
