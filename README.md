<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Berlethe SAMBA - Consultant en Stratégie d'Entreprise</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: 'Poppins', sans-serif; line-height: 1.7; color: #334155; background-color: #f8fafc; }

        /* HEADER & HERO SECTION */
        header {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: #ffffff;
            padding: 4.5rem 1rem 3.5rem 1rem;
            text-align: center;
        }

        .profile-pic {
            width: 170px;
            height: 170px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #38bdf8;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
            margin-bottom: 1.5rem;
        }

        header h1 { font-size: 2.4rem; font-weight: 700; margin-bottom: 0.3rem; }
        header .subtitle { font-size: 1.25rem; color: #38bdf8; font-weight: 600; margin-bottom: 0.8rem; }
        header p.tagline { font-size: 1.05rem; color: #94a3b8; max-width: 680px; margin: 0 auto; }

        /* NAVIGATION RAPIDE */
        nav {
            background-color: #ffffff;
            border-bottom: 1px solid #e2e8f0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.03);
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            flex-wrap: wrap;
            max-width: 1000px;
            margin: 0 auto;
        }
        nav li a {
            display: block;
            padding: 1rem 1.2rem;
            color: #475569;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            transition: color 0.2s;
        }
        nav li a:hover { color: #0284c7; }

        /* CONTENEUR PRINCIPAL */
        .container { max-width: 1000px; margin: 2.5rem auto 4rem auto; padding: 0 1.5rem; }

        /* CARTES DE CONTENU */
        .card {
            background: #ffffff;
            border-radius: 12px;
            padding: 2.5rem;
            margin-bottom: 2.5rem;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);
            border: 1px solid #e2e8f0;
        }
        .card h2 {
            color: #0f172a;
            font-size: 1.6rem;
            margin-bottom: 1.5rem;
            border-bottom: 3px solid #38bdf8;
            display: inline-block;
            padding-bottom: 0.3rem;
        }

        /* GRILLES */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; margin-top: 1rem; }
        
        .grid-item { 
            background-color: #f8fafc; 
            padding: 1.5rem; 
            border-radius: 8px; 
            border-left: 4px solid #0284c7; 
            border-top: 1px solid #e2e8f0;
            border-right: 1px solid #e2e8f0;
            border-bottom: 1px solid #e2e8f0;
        }
        .grid-item h3 { margin-bottom: 0.5rem; color: #0f172a; font-size: 1.15rem; }

        /* PHASES DE MÉTHODOLOGIE */
        .timeline { display: flex; flex-direction: column; gap: 1.2rem; margin-top: 1rem; }
        .step {
            display: flex;
            align-items: flex-start;
            gap: 1.2rem;
            background: #f1f5f9;
            padding: 1.2rem 1.5rem;
            border-radius: 8px;
        }
        .step-num {
            background: #0284c7;
            color: white;
            font-weight: bold;
            width: 38px;
            height: 38px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }

        /* LISTES */
        ul.list { list-style: none; }
        ul.list li { position: relative; padding-left: 1.8rem; margin-bottom: 0.8rem; }
        ul.list li::before { content: "➔"; position: absolute; left: 0; color: #0284c7; font-weight: bold; }

        .sources-list a { color: #0284c7; text-decoration: none; font-weight: 600; }
        .sources-list a:hover { text-decoration: underline; }

        /* FORMULAIRE DE CONTACT */
        form { display: flex; flex-direction: column; gap: 1.2rem; margin-top: 1rem; }
        .form-group { display: flex; flex-direction: column; gap: 0.4rem; }
        .form-group label { font-weight: 600; color: #0f172a; font-size: 0.95rem; }
        .form-group input, .form-group textarea {
            padding: 0.8rem 1rem;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
            font-family: inherit;
            font-size: 1rem;
        }
        .form-group input:focus, .form-group textarea:focus {
            outline: none;
            border-color: #0284c7;
            box-shadow: 0 0 0 3px rgba(2, 132, 199, 0.15);
        }
        button.btn-submit {
            background: #0284c7;
            color: white;
            border: none;
            padding: 0.9rem 1.8rem;
            border-radius: 6px;
            font-weight: 600;
            font-size: 1rem;
            cursor: pointer;
            align-self: flex-start;
            transition: background 0.2s;
        }
        button.btn-submit:hover { background: #0369a1; }

        /* FOOTER */
        footer { text-align: center; padding: 2.5rem 1rem; background-color: #0f172a; color: #64748b; font-size: 0.95rem; }
    </style>
</head>
<body>

    <header>
        <!-- Vérifie que le nom du fichier correspond exactement au nom de ta photo sur GitHub -->
        <img src="photo.jpg" alt="Berlethe SAMBA" class="profile-pic">
        
        <h1>Berlethe SAMBA</h1>
        <p class="subtitle">Consultante en Stratégie d'Entreprise</p>
        <p class="tagline">Accompagnement des directions générales dans la résolution de problématiques complexes, la transformation organisationnelle et la croissance durable.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">À propos</a></li>
            <li><a href="#missions">Missions & Cas</a></li>
            <li><a href="#methodology">Méthodologie</a></li>
            <li><a href="#skills">Outils & Compétences</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        
        <!-- SECTION À PROPOS -->
        <section id="about" class="card">
            <h2>Vision & Définition du Métier</h2>
            <p>Le consultant en stratégie est un partenaire clé des Comités de Direction (Comex / Codir). Son intervention vise à apporter une vision objective, étayée par des données rigoureuses, pour guider l'entreprise face à des mutations majeures : nouveaux marchés, ruptures technologiques, pression concurrentielle ou restructuration interne.</p>
            <p style="margin-top: 1rem;">Au-delà du diagnostic, mon approche privilégie la création de valeur mesurable et la mise en place de stratégies véritablement exécutables par les équipes opérationnelles.</p>
        </section>

        <!-- SECTION MISSIONS & CAS D'USAGE -->
        <section id="missions" class="card">
            <h2>Domaines d'Intervention & Cas Concrets</h2>
            <div class="grid">
                <div class="grid-item">
                    <h3>Stratégie de Croissance & Expansion</h3>
                    <p>Étude d'opportunités de marchés à l'international, lancement de nouvelles offres de produits/services, et diversification du portefeuille d'activités.</p>
                </div>
                <div class="grid-item">
                    <h3>Fusions-Acquisitions (M&A) & Due Diligence</h3>
                    <p>Évaluation stratégique de cibles d'acquisition, analyse des synergies potentielles et accompagnement lors des intégrations post-fusion.</p>
                </div>
                <div class="grid-item">
                    <h3>Transformation & Optimisation</h3>
                    <p>Revue des modèles opérationnels (Operating Model), optimisation de la chaîne de valeur, et conduite du changement organisationnel.</p>
                </div>
                <div class="grid-item">
                    <h3>Performance Financière & Marge</h3>
                    <p>Analyse des structures de coûts, politiques de pricing dynamique et programmes de réduction des dépenses non stratégiques.</p>
                </div>
            </div>
        </section>

        <!-- SECTION MÉTHODOLOGIE -->
        <section id="methodology" class="card">
            <h2>La Méthodologie d'une Mission type</h2>
            <div class="timeline">
                <div class="step">
                    <div class="step-num">1</div>
                    <div>
                        <strong>Cadrage & Diagnostic d'urgence :</strong> Collecte d'informations qualitatives et quantitatives, entretiens avec les parties prenantes et analyse de l'écosystème.
                    </div>
                </div>
                <div class="step">
                    <div class="step-num">2</div>
                    <div>
                        <strong>Modélisation & Recommandations :</strong> Formulation d'hypothèses stratégiques, simulation des impacts financiers et validation des scénarios préférentiels.
                    </div>
                </div>
                <div class="step">
                    <div class="step-num">3</div>
                    <div>
                        <strong>Feuille de route (Roadmap) :</strong> Structuration des chantiers prioritaires, allocation des ressources et définition des indicateurs de performance (KPIs).
                    </div>
                </div>
                <div class="step">
                    <div class="step-num">4</div>
                    <div>
                        <strong>Conduite du changement :</strong> Alignement des équipes exécutives, communication stratégique et suivi du déploiement opérationnel.
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION COMPÉTENCES ET OUTILS -->
        <section id="skills" class="card">
            <h2>Outils, Frameworks & Compétences Clés</h2>
            <div class="grid">
                <div class="grid-item">
                    <h3>Cadres d'Analyse (Frameworks)</h3>
                    <p>Matrice BCG, Modèle des 5 Forces de Porter, Analyse PESTEL, Matrice SWOT, Pyramide de Minto (Storytelling).</p>
                </div>
                <div class="grid-item">
                    <h3>Compétences Analytiques</h3>
                    <p>Modélisation financière sous Excel, analyse de données volumineuses, valorisation d'entreprise, benchmark concurrentiel.</p>
                </div>
                <div class="grid-item">
                    <h3>Soft Skills & Soft Power</h3>
                    <p>Aisance relationnelle de haut niveau, capacité de conviction auprès du C-Level, écoute active et gestion des conflits.</p>
                </div>
            </div>
        </section>

        <!-- SECTION PARCOURS & FORMATION -->
        <section class="card">
            <h2>Formations et Voies d'Accès</h2>
            <p>Le métier de consultant en stratégie recrute principalement des profils issus d'une formation d'excellence :</p>
            <ul class="list" style="margin-top: 1rem;">
                <li><strong>Grandes Écoles de Commerce :</strong> HEC, ESSEC, ESCAP, emlyon, EDHEC (Masters Grande École / Msc).</li>
                <li><strong>Grandes Écoles d'Ingénieurs :</strong> Polytechnique, Mines ParisTech, CentraleSupélec, Ponts ParisTech.</li>
                <li><strong>Universités & IEP :</strong> Masters spécialisés en finance/stratégie (Dauphine, Sciences Po Paris).</li>
            </ul>
        </section>

        <!-- SECTION SOURCES ET RÉFÉRENCES -->
        <section class="card">
            <h2>Sources & Ressources Clés</h2>
            <ul class="list sources-list">
                <li>
                    <strong>Consultor :</strong> Le média de référence sur le conseil en stratégie – 
                    <a href="https://www.consultor.fr" target="_blank">consultor.fr</a>
                </li>
                <li>
                    <strong>Apec :</strong> Fiche détaillée du métier de consultant en stratégie – 
                    <a href="https://www.apec.fr" target="_blank">apec.fr</a>
                </li>
                <li>
                    <strong>McKinsey & Company / BCG / Bain :</strong> Publications et études stratégiques mondiales.
                </li>
            </ul>
        </section>

        <!-- SECTION CONTACT -->
        <section id="contact" class="card">
            <h2>Me Contacter</h2>
            <p>Vous souhaitez échanger autour d'un projet stratégique ou en savoir plus sur mon parcours ?</p>
            
            <form action="#" method="POST" onsubmit="alert('Message envoyé !'); return false;">
                <div class="form-group">
                    <label for="name">Nom complet</label>
                    <input type="text" id="name" name="name" placeholder="Votre nom et prénom" required>
                </div>
                <div class="form-group">
                    <label for="email">Adresse e-mail</label>
                    <input type="email" id="email" name="email" placeholder="votre.email@exemple.com" required>
                </div>
                <div class="form-group">
                    <label for="message">Message / Demande</label>
                    <textarea id="message" name="message" rows="5" placeholder="Décrivez votre besoin ou votre demande..." required></textarea>
                </div>
                <button type="submit" class="btn-submit">Envoyer le message</button>
            </form>
        </section>

    </div>

    <footer>
        <p>© 2026 Berlethe SAMBA - Projet Professionnel Conseil en Stratégie</p>
    </footer>

</body>
</html>
