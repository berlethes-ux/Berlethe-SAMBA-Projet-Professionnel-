<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consultant en Stratégie d'Entreprise</title>
    <style>
        /* Styles Généraux */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f8f9fa;
        }
        a {
            color: #003366;
            text-decoration: none;
        }

        /* En-tête */
        header {
            background-color: #003366;
            color: #ffffff;
            padding: 3rem 1rem;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* Conteneur principal */
        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }

        /* Cartes d'information */
        .card {
            background: #ffffff;
            border-radius: 8px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
        }
        .card h2 {
            color: #003366;
            margin-bottom: 1rem;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 0.5rem;
        }

        /* Grille des compétences */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 1rem;
        }
        .grid-item {
            background-color: #eef2f7;
            padding: 1.2rem;
            border-radius: 6px;
            border-left: 4px solid #003366;
        }
        .grid-item h3 {
            margin-bottom: 0.5rem;
            color: #1a365d;
        }

        /* Liste des missions */
        ul.missions {
            list-style-type: none;
        }
        ul.missions li {
            position: relative;
            padding-left: 1.5rem;
            margin-bottom: 0.8rem;
        }
        ul.missions li::before {
            content: "✔";
            position: absolute;
            left: 0;
            color: #003366;
            font-weight: bold;
        }

        /* Pied de page */
        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #1a202c;
            color: #ffffff;
            font-size: 0.9rem;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Le Métier de Consultant en Stratégie</h1>
        <p>Accompagner les dirigeants dans leurs décisions cruciales</p>
    </header>

    <div class="container">
        
        <section class="card">
            <h2>Qu'est-ce qu'un Consultant en Stratégie ?</h2>
            <p>Le consultant en stratégie d'entreprise est un expert externe sollicité par la direction générale d'une organisation pour résoudre des problèmes complexes, optimiser la performance globale ou guider des choix de croissance majeurs.</p>
        </section>

        <section class="card">
            <h2>Missions Principales</h2>
            <ul class="missions">
                <li><strong>Analyse stratégique :</strong> Évaluer le positionnement de l'entreprise et étudier son marché/concurrence.</li>
                <li><strong>Audits opérationnels :</strong> Identifier les blocages internes et les leviers d'amélioration.</li>
                <li><strong>Recommandations :</strong> Formuler des plans d'action concrets pour la direction.</li>
                <li><strong>Opérations financières :</strong> Accompagner les fusacqs (fusions-acquisitions) et restructurations.</li>
            </ul>
        </section>

        <section class="card">
            <h2>Compétences Clés</h2>
            <div class="grid">
                <div class="grid-item">
                    <h3>Esprit d'analyse</h3>
                    <p>Capacité à traiter d'importantes masses de données pour en extraire des vérités financières et opérationnelles.</p>
                </div>
                <div class="grid-item">
                    <h3>Rigueur & Logique</h3>
                    <p>Cadrage de problèmes complexes selon des méthodologies d'analyse éprouvées.</p>
                </div>
                <div class="grid-item">
                    <h3>Communication</h3>
                    <p>Capacité à convaincre les comités de direction grâce à des présentations percutantes (PowerPoint, synthèses).</p>
                </div>
            </div>
        </section>

    </div>

    <footer>
        <p>© 2026 - Site d'information sur le conseil en stratégie</p>
    </footer>

</body>
</html>
