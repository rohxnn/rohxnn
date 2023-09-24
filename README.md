# My Portfolio

![Logo](https://path-to-your-logo.com/logo.png)

## Navigation

- [Home](#home)
- [Resume](#resume)
- [Work](#work)
- [About](#about)
- [Contact](#contact)

## Introduction

Welcome to my portfolio! I'm Rohan, a Java Full Stack Developer.

## Navbar

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js" integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+" crossorigin="anonymous"></script>
    <style>
        body {
            background: black;
        }
        .Fone {
            background: -webkit-linear-gradient(90deg, rgb(108, 123, 200) 29%, rgb(180, 115, 184) 85%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-size: 128px;
            padding-left: 78px;
        }
        .Ftwo {
            background: -webkit-linear-gradient(90deg, rgba(63,94,251,1) 3%, rgba(252,70,107,1) 96%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-size: 128px;
            padding-left: 78px;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#">
                <img src="C:\Users\LENOVO\Pictures\Screenshots\R.png" alt="Logo" height="30" style="width: 40px; height: 40px;">
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav" style="margin-left: 78%;">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Resume</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Work</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div style="margin-top: 98px;">
        <h1 class="Fone">Hii..I'm <span style="color: white;">Rohan</span></h1>
        <h1 class="Fone">I'm A</h1>
        <h1 class="Ftwo"> JAVA FULL STACK</h1>
        <h1 class="Ftwo">Developer</h1>
    </div>
</body>
</html>
