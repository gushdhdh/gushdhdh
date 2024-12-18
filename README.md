<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome</title>
    <style>
        /* General page settings */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0; /* Light gray */
            margin: 0;
            padding: 0;
            color: #333; /* Dark gray text */
            overflow-x: hidden;
        }

        /* Header and footer design */
        header, footer {
            background-color: #333; /* Black */
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        header nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            margin: 0 15px;
        }

        header nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.1em;
            transition: color 0.3s ease;
        }

        header nav ul li a:hover {
            color: #bcbcbc; /* Light gray */
        }

        /* Main section design */
        .hero-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 80vh;
            text-align: center;
        }

        .hero-section h1 {
            font-size: 3.5em;
            font-weight: bold;
            color: #333; /* Black */
            margin-bottom: 20px;
            animation: fadeIn 1.5s ease;
        }

        .hero-section p {
            font-size: 1.2em;
            color: #666; /* Medium gray */
            max-width: 700px;
            margin: 20px 0;
            line-height: 1.6;
            animation: fadeIn 2s ease;
        }

        .hero-section button {
            padding: 15px 30px;
            font-size: 1.2em;
            color: white;
            background-color: #333; /* Black */
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
            animation: fadeIn 2.5s ease;
        }

        .hero-section button:hover {
            background-color: #444; /* Dark gray */
            transform: scale(1.1);
        }

        .hero-section button:active {
            transform: scale(0.95);
        }

        /* Animation effects */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        footer p {
            font-size: 0.9em;
            margin: 5px 0;
        }

        /* Login screen */
        .login-section {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #666; /* Medium gray */
        }

        .login-section h2 {
            color: white;
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .login-form {
            background-color: #333; /* Black */
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }

        .login-form input {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border: 2px solid #444; /* Dark gray */
            border-radius: 5px;
            font-size: 1.2em;
            color: #333;
            background-color: #f0f0f0; /* Light gray */
        }

        .login-form button {
            width: 100%;
            padding: 12px;
            font-size: 1.2em;
            color: white;
            background-color: #444; /* Dark gray */
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .login-form button:hover {
            background-color: #555; /* Lighter gray */
        }

        .login-form button:active {
            transform: scale(0.95);
        }

    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home Page</a></li>
                <li><a href="#team">Our Team</a></li>
                <li><a href="#services">Our Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#login">Login</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Main section -->
        <section class="hero-section" id="home">
            <h1 class="floating">Welcome to Our Team</h1>
            <p>We are the development team, working on developing applications and software, providing innovative and effective software solutions.</p>
            <button onclick="navigateToSection('team')">Meet Our Team</button>
        </section>

        <!-- Team section -->
        <section class="about-section" id="team">
            <h1>Meet Our Team</h1>
            <p>We are a diverse team with experience in design, software development, and UI/UX design, and we strive to provide excellence in every project we undertake.</p>
            <div class="team-members">
                <div class="team-member">
                    <h3>Gharam</h3>
                    <p>Web Developer</p>
                </div>
                <div class="team-member">
                    <h3>Maram</h3>
                    <p>UI/UX Specialist</p>
                </div>
                <div class="team-member">
                    <h3>Nouf</h3>
                    <p>App Developer</p>
                </div>
            </div>
        </section>

        <!-- Login screen -->
        <section class="login-section" id="login">
            <h2>Welcome to the Login Page</h2>
