# PLP-FINAL-PROJECT

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Professional healthcare website for patient management and doctor scheduling.">
    <title>Healthcare Management</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Navigation Bar -->
    <header>
        <div class="container">
            <h1 class="logo">PLP HealthCare</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#register">Register</a></li>
                    <li><a href="#login">Login</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <div class="hero-content">
            <h2>Welcome to PLP HealthCare</h2>
            <p>Your health is our priority. Manage your appointments, doctors, and more!</p>
            <a href="#register" class="btn">Register Now</a>
        </div>
    </section>

    <!-- Patient Registration -->
    <section id="register" class="form-section">
        <h2>Patient Registration</h2>
        <form id="register-form" action="/register" method="POST">
            <input type="text" name="name" placeholder="Full Name" required>
            <input type="email" name="email" placeholder="Email Address" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit" class="btn">Register</button>
        </form>
    </section>

    <!-- Patient Login -->
    <section id="login" class="form-section">
        <h2>Patient Login</h2>
        <form id="login-form" action="/login" method="POST">
            <input type="email" name="email" placeholder="Email Address" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit" class="btn">Login</button>
        </form>
    </section>

    <!-- Services Section -->
    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="service">
                <h3>Doctor Consultation</h3>
                <p>Consult with a doctor based on your symptoms and needs.</p>
            </div>
            <div class="service">
                <h3>Appointment Booking</h3>
                <p>Easily book and manage appointments with your preferred doctor.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 HealthCare. All rights reserved Built by anipower.</p>
        </div>
    </footer>

</body>
</html>





/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background: #333;
    color: white;
    padding: 10px 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    margin-left: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Hero Section */
#hero {
    background-color: #007bff;
    color: white;
    padding: 60px 20px;
    text-align: center;
}

#hero h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

#hero p {
    font-size: 18px;
    margin-bottom: 30px;
}

#hero .btn {
    background-color: #fff;
    color: #007bff;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

#hero .btn:hover {
    background-color: #0056b3;
    color: white;
}

/* Form Section */
.form-section {
    padding: 40px 20px;
    text-align: center;
}

.form-section h2 {
    font-size: 30px;
    margin-bottom: 20px;
}

.form-section form input {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
    font-size: 16px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

.form-section form button {
    background-color: #007bff;
    color: white;
    padding: 12px 25px;
    font-size: 18px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.form-section form button:hover {
    background-color: #0056b3;
}

/* Services Section */
#services {
    background-color: #fff;
    padding: 40px 20px;
    text-align: center;
}

#services h2 {
    font-size: 36px;
    margin-bottom: 30px;
}

#services .service {
    display: inline-block;
    width: 45%;
    margin: 10px;
    padding: 20px;
    background-color: #f0f0f0;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

#services .service h3 {
    font-size: 24px;
    margin-bottom: 10px;
}

#services .service p {
    font-size: 16px;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}
