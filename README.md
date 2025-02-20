<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Website </title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }

        nav {
            background-color: #444;
            padding: 1rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        nav a:hover {
            color: #ffd700;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        section {
            margin: 2rem 0;
            padding: 2rem;
            background-color: #f4f4f4;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Baga nagaan gara fuula website kattaa basaqaa dhuftan</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">Waa'ee  keenyaa illaachisee</a></li>
            <li><a href="#services">Tajaajilaa kenninuu</a></li>
            <li><a href="#contact">Nu qunnamuuf</a></a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="home">
            <h2>Home</h2>


            <p> Ragaan lubbuu dha.Ragaa keenya qindeeessine hinqabne yoo ta'e burjaajii nuti uuma..</


        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Ergama fi kaayyoo dhaabata kana .</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <div class="services-grid">
                <div class="service-item">
                    <h3>Karooraa fi sagantaa hojii qopheessu</h3>
                    <p> Gorsa leenjissuu </p>
                </div>
                <div class="service-item">
                    <h3>Development</h3>
                    <p>Custom web application development.</p>
                </div>
                <div class="service-item">
                    <h3>SEO</h3>
                    <p>Search engine optimization services.</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                
                <label for="message">Message:</label>
                <textarea id="message" name="message"></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2017/2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>

