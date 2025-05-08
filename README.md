""<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EDU-CONNECT</title>
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 90%;
            margin: auto;
        }
        .navbar h1 {
            font-size: 1.8em;
        }
        nav ul {
            list-style-type: none;
            display: flex;
            gap: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.1em;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #e0e0e0;
        }
        /* Hero Section */
        .hero {
            background-image: url('https://via.placeholder.com/1500x500');
            background-size: cover;
            background-position: center;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .hero-content h2 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .hero-content p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        .btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.1em;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #45a049;
        }
        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="navbar">
            <h1>EDU-CONNECT</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <section class="hero">
        <div class="hero-content">
            <h2>Connecting Education with Opportunities</h2>
            <p>Your journey to knowledge begins here.</p>
            <a href="#" class="btn">Get Started</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 EDU-CONNECT. All rights reserved.</p>
    </footer>
</body>
</html>
""
