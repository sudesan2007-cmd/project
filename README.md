# Date:11/10/2025
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
```<html>
<head>
    <meta charset="UTF-8">
    <title>Dribble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Jobs</a></li>
                </ul>
            </div>
            <a class="btn btn-outline-light me-2" href="#">Sign in</a>
            <a class="btn btn-outline-light me-2" href="#">Sign Up</a>
            <input type="search" class="form-control w-auto" placeholder="Search" style="margin: 20px;">
        </div>
    </nav>

    <section id="home" class="bg-white py-5"  style="height: 45vh;" >
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-middle">
                    <h1 class="display-4 fw-bold">What are you working on?</h1>
                    <p class="my-3">Dribbble is a show-and-tell platform for designers.</p>
                    <button class="btn btn-secondary me-2">Learn More</button>
                    <button class="btn btn-primary">Sign up</button>
                </div>
                <div class="col-md-6 text-center">
                    <img src="home.png" class="img-fluid" alt="Design Work" style="height: 45vh;">
                </div>
            </div>
        </div>
    </section>

    <section class="py-5">
        <div class="container">
            <div class="row mb-4">
                <div class="col-md-4">
                    <h2 class="fw-bold">Popular</h2>
                </div>
                <div class="col-md-4 text-center">
                    <button class="btn btn-light btn-secondary btn-outline-dark">Now</button>
                    <button class="btn btn-light btn-secondary btn-outline-dark">Shots</button>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img4.jpeg" width="300" height="225">
                      
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Awe Design Studio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img7.jpg" width="300" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Russlan silz</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img6.jpeg" width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Alfrey Davilla</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/users/1739084/screenshots/4448965/kyzzlj.jpg?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                       
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 MakeReign</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/users/140043/screenshots/9106916/dribbble_4_compressed.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Mattias Johannson</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img2.jpg" width="300" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Jan Losert</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img3.jpeg"width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Wkio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="https://cdn.dribbble.com/userupload/10964296/file/original-ffa83431e0b8639f6d1036a0f80c76ae.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Romain Tystramm</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p class="mb-0">Designed and developed by SUDESAN T (25018208)</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
# OUTPUT:
<img width="1436" height="820" alt="Screenshot 2025-10-12 003506" src="https://github.com/user-attachments/assets/c475febb-1bf2-4323-a78d-534fd2f3accd" />
<img width="1440" height="778" alt="Screenshot 2025-10-12 003610" src="https://github.com/user-attachments/assets/ec176e66-72cf-48d4-9431-d058ebff6c68" />





# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
