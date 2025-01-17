<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EFC Adler Society</title>
    <style>
        body {
            font-family: Cooper Black, sans-serif;
            background-color: #a81414;
            background-image: url('18-19-europaleague-eintracht-frankfurt-apollon-limassol-07.jpg'); /* Hintergrundbild */
            background-size: cover;
            background-position: center;
            color: #fff;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .container {
            width: 100%;
            max-width: 800px;
            background-color: rgba(0, 0, 0, 0.8); /* Leicht transparentes Schwarz */
            padding: 20px;
            box-sizing: border-box;
            margin: 20px;
            border-radius: 10px;
        }
        header {
            background-color: #000000;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .content {
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            width: 100%;
            border-radius: 10px;
            margin-top: 20px;
        }
        form input, form textarea {
            display: block;
            width: 100%;
            margin-bottom: 10px;
            padding: 10px;
            box-sizing: border-box;
        }
        .shop-item {
            border: 1px solid #e60000;
            padding: 20px;
            margin: 10px 0;
        }
        .shop-item img {
            max-width: 100%;
            height: auto;
        }
        .shop-item h3 {
            margin-top: 0;
        }
        .login-form {
            max-width: 400px;
            margin: 0 auto;
        }
        .hidden {
            display: none;
        }
        a.email-link {
            color: #e60000;
            text-decoration: underline;
        }
        @media (max-width: 600px) {
            nav {
                display: flex;
                flex-direction: column;
            }
            nav a {
                margin: 5px 0;
            }
        }
    </style>
    <script>
        function login(event) {
            event.preventDefault();
            const password = document.getElementById('password').value;
            if (password === 'fanclub123') {
                document.getElementById('shop-content').classList.remove('hidden');
                document.getElementById('login-form').classList.add('hidden');
            } else {
                alert('Falsches Passwort!');
            }
        }
    </script>
</head>
<body>
    <div class="container">
        <header>
            <img class="imgzentirert" src="1721640644838.png" width="600" height="300" border="0" alt="Bildtext">   
        </header>
        <nav>
            <a href="#home">Startseite</a>
            <a href="#about">Über uns</a>
            <a href="#gallery">Galerie</a>
            <a href="#shop">Shop</a>
            <a href="#membership">Mitgliedsantrag</a>
            <a href="#contact">Kontakt</a>
        </nav>
        <div id="home" class="content">
            <h2>Willkommen bei EFC Adler Society</h2>
            <p>Wir sind ein leidenschaftlicher Fanclub von Eintracht Frankfurt.

                Der EFC wurde am 06.12.2019 gegründet
                <p> 
        </div>
        <div id="about" class="content">
            <h2>Über uns</h2>

            <p>EFC Adler Society wurde gegründet, um Fans von Eintracht Frankfurt zusammenzubringen und gemeinsame Erlebnisse zu teilen.

                <p>Martin hatte schon lange Interesse an einem EFC gehabt. Hat es aber immer verdrängt. Es gab zwar coole Fanclubs, er wollte aber was Eigenes aufziehen. Was ganz Besonderes.
             ER ist ein riesengroßer SGE Fan geworden und das seit seinem 7. Lebensjahr. Ab da kaufte er seine Fußballschuhe im Geschäft von Bernd Nickel. er lernte ihn kennen und bekam Poster, Autogrammkarten usw. von ihm. Da war es um ihn geschehen!

             <p>Viele Jahre später, nämlich am 06.12.2019 entschied er sich Nägel mit Köpfen zu machen…
                Also fragte er Marcus, ob er Lust hätte mitzumachen. Das Ziel war es, Gleichgesinnte und SGE Verrückte in einer Gruppe zu vereinen! Freude, Freundschaft und ein friedliches Miteinander sollte die Basis sein!
                Wir sind mittlerweile eine 20-köpfige Gemeinschaft geworden. Um den Adler die Krone aufzusetzen, Wollten wir ein öffentlich anerkannter Fanclub von Eintracht Frankfurt werden!</p>

            </p>

            <h2>Das sind wir</h2>

            <p>1. Vorsitzender: Martin
               <p>2. Vorsitzender: Marcus</p> 
                <p>3. Vorsitzender: Mario</p>
            </p>
            <p>Schatzmeisterin: Rosi
                              <p>2. Schatzmeister: Detlef</p>
            </p>
            <p>Schriftführer: Sissi - ist zudem für die Homepage verantwortlich
                              <p>2. Schriftführerin: Sandra</p>
            </p>
            <div id="gallery" class="content gallery">
                <h2>Galerie</h2>
                <img src="https://via.placeholder.com/300x200" alt="Event Bild 1">
                
            </div>
            <div id="shop" class="content">
                <h2>Shop (Passwortgeschützt)</h2>
                <div id="login-form" class="login-form">
                    <form onsubmit="login(event)">
                        <input type="password" id="password" placeholder="Passwort" required>
                        <input type="submit" value="Login">
                    </form>
                </div>
        
                <div id="shop-content" class="hidden">
                    <div class="shop-item">
                        <img src="https://via.placeholder.com/200x200" alt="Trikot">
                        <h3>Trikot</h3>
                        <p>Preis: 50€</p>
                      
                    </div>
                    <div class="shop-item">
                        <img src="https://via.placeholder.com/200x200" alt="Schal">
                        <h3>Schal</h3>
                        <p>Preis: 20€</p>
                        
                    </div>
                    <div 
                    <p>Für die Bestellung, fülle bitte das unten aufgeführte</p>
                    <p>Kontaktformular aus. Wichtig ist, dass du die Größe und die Menge angibst.</p>
        <p>Sobald wir deine Bestellung bearbeitet haben, bekommst du eine E-Mail von uns.</p> <p>Vorab möchten wir dich aber um ein wenig Geduld bitten, da wir alles einzeln anfertigen.</p>
                    
                    <h2>Bestellung</h2>
                    <form action="/submit_contact" method="post">
                        <input type="text" name="name" placeholder="Name" required>
                        <input type="email" name="email" placeholder="E-Mail" required>
                        <input type="text" name="subject" placeholder="Betreff" required>
                        <textarea name="message" placeholder="Nachricht" required></textarea>
                        <input type="submit" value="Senden">
                    <!-- Weitere Shop-Artikel hier hinzufügen -->
                </div>
        
    </div>
    <div id="membership" class="content">
        <h2>Mitgliedsantrag</h2>

        <p>Laden Sie unseren Mitgliedsantrag herunter und senden Sie ihn ausgefüllt an uns zurück. 
            Vorab gerne als Foto an die E-Mail <a href="mailto:adlersociety@web.de" class="email-link">adlersociety@web.de</a>
       
            <p>Sobald wir über deinen Antrag entschieden haben, erhältst du von uns eine E-Mail. </p>

        <p>Wir freuen uns schon auf dich! </p>

       <p> Das Team der Adler Society</p> 
    

        <a href="mitgliedsantrag.pdf" download="mitgliedsantrag.pdf" style="color: #e60000; text-decoration: underline;">Mitgliedsantrag herunterladen</a>
        <form action="/submit_membership" method="post">
        </form>
    </div>

    <div id="contact" class="content">
        <h2>Kontakt</h2>
        <form action="/submit_contact" method="post">
            <input type="text" name="name" placeholder="Name" required>
            <input type="email" name="email" placeholder="E-Mail" required>
            <input type="text" name="subject" placeholder="Betreff" required>
            <textarea name="message" placeholder="Nachricht" required></textarea>
            <input type="submit" value="Senden">
        </form>

        <p><h3>Ansprechpartner</h3></p>
        <p>Name: Martin Gocz<br>Position: Präsident<br><a E-Mail: href="mailto:adlersociety@web.de" class="email-link">adlersociety@web.de</a></p>
        </p>
        
    </div>
    <footer>
        <p>&copy; 2024 EFC Adler Society // Sissi</p>
    </footer>
</body>
</html>


