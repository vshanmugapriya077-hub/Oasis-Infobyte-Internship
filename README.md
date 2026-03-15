<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>TECHBYTE</title>

    <style>
        /* Reset default margins */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body Styling */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        /* Header */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: #333;
            color: white;
        }

        header .logo {
            font-size: 22px;
            font-weight: bold;
        }

        header nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
        }

        header nav a:hover {
            color: #f4b400;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
        }

        .hero h1 {
            font-size: 42px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
        }

        .hero button {
            padding: 12px 25px;
            margin-top: 25px;
            border: none;
            background-color: white;
            color: #333;
            font-weight: bold;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }

        .hero button:hover {
            background-color: #f4b400;
            color: white;
        }

        /* Services Section */
        .services {
            display: flex;
            justify-content: space-around;
            padding: 60px 20px;
            background-color: #f9f9f9;
            flex-wrap: wrap;
        }

        .box {
            background-color: white;
            padding: 30px;
            width: 25%;
            min-width: 250px;
            text-align: center;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            transition: 0.3s;
        }

        .box:hover {
            transform: translateY(-8px);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <div class="logo">Techbyte</div>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Welcome to TECHBYTE</h1>
        <p>Learn Web Development with Simple Projects</p>
        <button>Get Started</button>
    </section>

    <!-- Services Section -->
    <section class="services">
        <div class="box">
            <h2>Design</h2>
            <p>Creative and modern designs.</p>
        </div>

        <div class="box">
            <h2>Development</h2>
            <p>Clean and efficient coding.</p>
        </div>

        <div class="box">
            <h2>Support</h2>
            <p>24/7 customer support.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 techbyte | All Rights Reserved</p>
    </footer>

</body>
</html>
