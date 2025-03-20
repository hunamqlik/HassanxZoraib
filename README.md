<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        /* Add some basic styles for layout */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #ddd;
            color: #333;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Website</h1>
        <p>Your one-stop solution for everything!</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content Section -->
    <section>
        <h2 id="home">Home</h2>
        <p>This is the homepage of the website. Here, you'll find information about us and the services we offer.</p>

        <h2 id="about">About Us</h2>
        <p>We are a team of creative designers and developers who specialize in creating stunning websites.</p>

        <h2 id="services">Our Services</h2>
        <ul>
            <li>Website Design</li>
            <li>Web Development</li>
            <li>E-commerce Solutions</li>
            <li>SEO Optimization</li>
        </ul>

        <h2 id="contact">Contact Us</h2>
        <p>If you have any questions or want to get started on your project, feel free to <a href="mailto:info@example.com">email us</a>!</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 My Website. All Rights Reserved.</p>
    </footer>

</body>
</html>
