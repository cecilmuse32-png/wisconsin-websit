# wisconsin-websit
A responsive website showcasing web applications and digital services in Wisconsin, including government, healthcare, education, and business sectors.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wisconsin Web Applications</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
        }

        header {
            background: #8B0000;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffcc00;
        }

        section {
            padding: 20px;
        }

        .card {
            background: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }

        button {
            padding: 10px;
            background: #8B0000;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background: #ffcc00;
            color: black;
        }
    </style>
</head>
<body>

<header>
    <h1>Wisconsin Web Applications</h1>
    <p>Exploring Digital Services and Web Solutions in Wisconsin</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#applications">Applications</a>
    <a href="#benefits">Benefits</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Wisconsin Web Applications</h2>
    <div class="card">
        <p>
            Wisconsin has embraced modern web technologies to improve public services,
            business operations, and education systems. Web applications in Wisconsin
            are widely used in healthcare, government services, agriculture, and commerce.
        </p>
    </div>
</section>

<section id="applications">
    <h2>Types of Web Applications</h2>

    <div class="card">
        <h3>Government Services</h3>
        <p>Online tax filing, license renewals, and public records access.</p>
    </div>

    <div class="card">
        <h3>Healthcare Systems</h3>
        <p>Patient portals, appointment booking, and telemedicine platforms.</p>
    </div>

    <div class="card">
        <h3>Education Platforms</h3>
        <p>Online learning systems used by schools and universities.</p>
    </div>

    <div class="card">
        <h3>Business Applications</h3>
        <p>E-commerce, inventory systems, and customer management tools.</p>
    </div>
</section>

<section id="benefits">
    <h2>Benefits of Web Applications</h2>
    <div class="card">
        <ul>
            <li>Accessible from anywhere</li>
            <li>Cost-effective solutions</li>
            <li>Improved efficiency</li>
            <li>Real-time data updates</li>
        </ul>
        <button onclick="showMessage()">Click for More Info</button>
        <p id="message"></p>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <div class="card">
        <p>Email: info@wisconsinwebapps.com</p>
        <p>Phone: +1 234 567 890</p>
    </div>
</section>

<footer>
    <p>&copy; 2026 Wisconsin Web Applications</p>
</footer>

<script>
    function showMessage() {
        document.getElementById("message").innerText =
            "Web applications are transforming Wisconsin's digital landscape!";
    }
</script>

</body>
</html>
