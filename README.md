# Portfolio-aliou-seck
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Portfolio Data Analyst</title>
    <style>
        :root {
            --primary-color: #4285F4;
            --secondary-color: #34A853;
            --accent-color: #EA4335;
            --text-color: #333333;
            --light-bg: #F8F9FA;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            margin: 0;
            padding: 0;
        }
        
        .container {
            width: 85%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }
        
        .logo {
            font-weight: bold;
            font-size: 1.5rem;
            color: var(--primary-color);
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 2rem;
        }
        
        .nav-links a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: 500;
        }
        
        .nav-links a:hover {
            color: var(--primary-color);
        }
        
        section {
            padding: 5rem 0;
        }
        
        .hero {
            background-color: var(--light-bg);
            padding: 8rem 0 5rem;
            margin-top: 60px;
        }
        
        .hero-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        .hero-text {
            width: 50%;
        }
        
        .hero-image {
            width: 45%;
            text-align: center;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        .btn {
            display: inline-block;
            background: var(--primary-color);
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 500;
            margin-top: 1rem;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            color: var(--primary-color);
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .skill-card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            text-align: center;
        }
        
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .project-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .project-image {
            height: 200px;
            background-color: #ddd;
            background-size: cover;
            background-position: center;
        }
        
        .project-content {
            padding: 1.5rem;
        }
        
        footer {
            background: var(--text-color);
            color: white;
            padding: 3rem 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">Mon Portfolio Data</div>
                <ul class="nav-links">
                    <li><a href="#about">À propos</a></li>
                    <li><a href="#skills">Compétences</a></li>
                    <li><a href="#projects">Projets</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container hero-content">
            <div class="hero-text">
                <h1>Transformez les données en insights actionnables</h1>
                <p>Je suis [Votre Prénom], Data Analyst certifié(e) Google, spécialisé(e) dans l'extraction de sens à partir de données complexes.</p>
                <a href="#projects" class="btn">Voir mes projets</a>
            </div>
            <div class="hero-image">
                <div style="background-color:#eee; width:300px; height:300px; border-radius:50%; display:flex; align-items:center; justify-content:center;">
                    [Votre photo]
                </div>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2 class="section-title">À propos de moi</h2>
            <p>Récemment certifié(e) par Google en analyse de données, je maîtrise l'art de transformer des données complexes en insights actionnables. Passionné(e) par la résolution de problèmes et curieux(se) par nature, j'aime explorer les données pour découvrir des tendances et patterns cachés.</p>
            <p>Ma certification Google m'a formé à l'utilisation d'outils comme SQL, Tableau, R et Sheets pour le nettoyage, l'analyse et la visualisation de données. Je suis maintenant à la recherche de nouvelles opportunités pour appliquer ces compétences à des problèmes business concrets.</p>
        </div>
    </section>

    <section id="skills" style="background-color: var(--light-bg);">
        <div class="container">
            <h2 class="section-title">Mes compétences</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>SQL</h3>
                    <p>Requêtes complexes, agrégation, jointures, fonctions window</p>
                </div>
                <div class="skill-card">
                    <h3>Visualisation</h3>
                    <p>Tableau, Looker Studio, création de dashboards interactifs</p>
                </div>
                <div class="skill-card">
                    <h3>Analyse statistique</h3>
                    <p>R, tests d'hypothèses, analyse exploratoire</p>
                </div>
                <div class="skill-card">
                    <h3>Nettoyage de données</h3>
                    <p>Identification et correction des anomalies, préparation des données</p>
                </div>
            </div>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2 class="section-title">Mes projets</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image"></div>
                    <div class="project-content">
                        <h3>Analyse des vélos partagés</h3>
                        <p>Comparison des habitudes entre abonnés annuels et utilisateurs occasionnels.</p>
                        <a href="#">Voir le projet</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image"></div>
                    <div class="project-content">
                        <h3>Dashboard ventes e-commerce</h3>
                        <p>Analyse RFM et identification des tendances produits.</p>
                        <a href="#">Voir le projet</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image"></div>
                    <div class="project-content">
                        <h3>Performance campagne marketing</h3>
                        <p>Calcul du ROI par canal et analyse du parcours client.</p>
                        <a href="#">Voir le projet</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" style="background-color: var(--light-bg);">
        <div class="container">
            <h2 class="section-title">Contactez-moi</h2>
            <p>Je suis ouvert aux opportunités en tant que Data Analyst junior. N'hésitez pas à me contacter!</p>
            <p>Email: votre.email@exemple.com</p>
            <p>LinkedIn: linkedin.com/in/votreprofil</p>
            <p>GitHub: github.com/votreprofil</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2023 [Votre Nom]. Tous droits réservés.</p>
        </div>
    </footer>
</body>
</html>
