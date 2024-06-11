# code-bg
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Web Personnelle</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #50b3a2;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #e8491d 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .bio, .portfolio, .gallery, .social {
            margin: 20px 0;
            padding: 20px;
            background: #fff;
            border-radius: 5px;
        }
        .bio img, .gallery img {
            max-width: 100%;
            border-radius: 5px;
        }
        .social a {
            margin: 0 10px;
            text-decoration: none;
            color: #50b3a2;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Bienvenue sur ma page personnelle</h1>
            <nav>
                <ul>
                    <li><a href="#bio">Biographie</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#gallery">Galerie</a></li>
                    <li><a href="#social">Réseaux Sociaux</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <div class="container">
        <section id="bio" class="bio">
            <h2>Biographie</h2>
            <p>Je m'appelle [Ton Nom], et je suis passionné par la programmation. J'ai commencé à coder à [ton âge de début] et j'adore créer des solutions innovantes pour résoudre des problèmes.</p>
            <img src="portrait.jpg" alt="Portrait de moi">
        </section>

        <section id="portfolio" class="portfolio">
            <h2>Portfolio</h2>
            <p>Voici quelques projets de programmation sur lesquels j'ai travaillé :</p>
            <ul>
                <li><strong>Projet 1 :</strong> Description du projet 1.</li>
                <li><strong>Projet 2 :</strong> Description du projet 2.</li>
                <li><strong>Projet 3 :</strong> Description du projet 3.</li>
            </ul>
        </section>

        <section id="gallery" class="gallery">
            <h2>Galerie</h2>
            <p>Quelques photos de mes projets et de moi en action :</p>
            <img src="projet1.jpg" alt="Projet 1">
            <img src="projet2.jpg" alt="Projet 2">
        </section>

        <section id="social" class="social">
            <h2>Réseaux Sociaux</h2>
            <p>Vous pouvez me suivre sur :</p>
            <a href="https://twitter.com/toncompte" target="_blank">Twitter</a>
            <a href="https://github.com/toncompte" target="_blank">GitHub</a>
            <a href="https://linkedin.com/in/toncompte" target="_blank">LinkedIn</a>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2024 [Ton Nom]. Tous droits réservés.</p>
    </footer>
</body>
</html>
