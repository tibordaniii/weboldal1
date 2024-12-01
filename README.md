<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weboldal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            background: #fff;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Üdvözöllek a weboldalamon!</h1>
    </header>
    <nav>
        <a href="#about">Rólam</a>
        <a href="#services">Szolgáltatások</a>
        <a href="#contact">Kapcsolat</a>
    </nav>
    <section id="about">
        <h2>Rólam</h2>
        <p>Ez az oldal egy egyszerű bemutató célú weboldal. Tartalmaz alapvető információkat és szolgáltatásokat.</p>
    </section>
    <section id="services">
        <h2>Szolgáltatások</h2>
        <p>Weboldal készítés, tartalomkezelés és karbantartás professzionális szinten.</p>
    </section>
    <section id="contact">
        <h2>Kapcsolat</h2>
        <p>Ha kérdésed van, írj nekem a <a href="mailto:email@example.com">email@example.com</a> címen.</p>
    </section>
    <footer>
        <p>&copy; 2024 Minden jog fenntartva.</p>
    </footer>
</body>
</html>
