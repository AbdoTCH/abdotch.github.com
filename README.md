
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apprendre HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        section {
            margin-bottom: 20px;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
            font-size: 24px;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        code {
            background-color: #eaeaea;
            padding: 5px;
            border-radius: 4px;
            font-family: monospace;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>

<header>
    <h1>Apprendre les Bases de HTML</h1>
</header>

<main>
    <section>
        <h2>Introduction à HTML</h2>
        <p>HTML (HyperText Markup Language) est le langage de balisage standard pour créer des pages web. Il permet de structurer le contenu sur Internet.</p>
    </section>

    <section>
        <h2>Structure de base d'une page HTML</h2>
        <p>Chaque page HTML commence avec une structure de base comme ceci :</p>
        <pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;title&gt;Titre de la page&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;!-- Contenu de la page --&gt;
  &lt;/body&gt;
&lt;/html&gt;</code></pre>
    </section>

    <section>
        <h2>Les Balises de Texte</h2>
        <p>Les balises de texte les plus utilisées incluent :</p>
        <ul>
            <li><code>&lt;h1&gt; à &lt;h6&gt;</code> : Titres</li>
            <li><code>&lt;p&gt;</code> : Paragraphe</li>
            <li><code>&lt;strong&gt;</code> : Texte en gras</li>
            <li><code>&lt;em&gt;</code> : Texte en italique</li>
        </ul>
    </section>

    <section>
        <h2>Les Liens</h2>
        <p>Pour créer un lien, utilisez la balise <code>&lt;a&gt;</code> :</p>
        <pre><code>&lt;a href="https://www.example.com"&gt;Visiter Exemple&lt;/a&gt;</code></pre>
    </section>

    <section>
        <h2>Les Images</h2>
        <p>Pour insérer une image, utilisez la balise <code>&lt;img&gt;</code> :</p>
        <pre><code>&lt;img src="chemin/vers/image.jpg" alt="Description de l'image"&gt;</code></pre>
    </section>
</main>

<footer>
    <p>&copy; 2024 Apprendre HTML. Tous droits réservés.</p>
</footer>

</body>
</html>
