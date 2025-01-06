# bootstrap


/* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

h1, h2, h3 {
    color: #333;
}

/* Hero Section */
.hero {
    background: url('hero-dish.jpg') center/cover no-repeat;
    color: white;
    height: 70vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero .btn {
    background-color: #d9534f;
    color: white;
    padding: 0.75rem 1.5rem;
    border-radius: 5px;
    font-size: 1.2rem;
}

/* Menu Section */
.menu-item {
    text-align: center;
    margin-bottom: 2rem;
}

.menu-item img {
    max-width: 100%;
    border-radius: 10px;
    margin-bottom: 1rem;
}

.menu-item h3 {
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
}

.menu-item p {
    color: #555;
}

/* About Us Section */
.about-img {
    border-radius: 10px;
    max-width: 100%;
}

/* Contact Section */
.contact-form {
    max-width: 600px;
    margin: 0 auto;
}

.contact-form .form-control {
    margin-bottom: 1rem;
}

.contact-form .btn {
    background-color: #5bc0de;
    color: white;
    border-radius: 5px;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}

footer a {
    color: #5bc0de;
    margin: 0 0.5rem;
}

html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fictional Restaurant</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <a class="navbar-brand" href="#">Restaurant Name</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#menu">Menu</a></li>
                        <li class="nav-item"><a class="nav-link" href="#about">About Us</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container text-center">
            <h1>Welcome to Our Restaurant</h1>
            <a href="#menu" class="btn btn-primary">View Menu</a>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Our Menu</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="menu-item">
                        <img src="dish1.jpg" alt="Dish 1">
                        <h3>Dish 1</h3>
                        <p>A delicious description of Dish 1.</p>
                        <p><strong>$12.99</strong></p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="menu-item">
                        <img src="dish2.jpg" alt="Dish 2">
                        <h3>Dish 2</h3>
                        <p>A delicious description of Dish 2.</p>
                        <p><strong>$15.99</strong></p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="menu-item">
                        <img src="dish3.jpg" alt="Dish 3">
                        <h3>Dish 3</h3>
                        <p>A delicious description of Dish 3.</p>
                        <p><strong>$18.99</strong></p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-5 bg-light">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <img src="restaurant.jpg" alt="Restaurant" class="about-img">
                </div>
                <div class="col-md-6">
                    <h2>About Us</h2>
                    <p>We are a fictional restaurant serving the best dishes in town. Our chefs use the freshest ingredients to create mouthwatering meals just for you.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form class="contact-form">
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" id="name" class="form-control" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" id="email" class="form-control" required>
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea id="message" class="form-control" rows="5" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Fictional Restaurant. All Rights Reserved.</p>
            <p>
                <a href="#">Facebook</a> |
                <a href="#">Twitter</a> |
                <a href="#">Instagram</a>
            </p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


