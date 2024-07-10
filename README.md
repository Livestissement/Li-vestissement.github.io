<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vendre Ma Formation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Vendez votre Formation</h1>
    </header>
    <section id="intro">
        <h2>À propos de la formation</h2>
        <p>Découvrez notre formation unique qui vous aidera à atteindre vos objectifs. Inscrivez-vous maintenant pour en savoir plus!</p>
    </section>
    <section id="details">
        <h2>Ce que vous apprendrez</h2>
        <ul>
            <li>Compétence 1</li>
            <li>Compétence 2</li>
            <li>Compétence 3</li>
        </ul>
    </section>
    <section id="testimonials">
        <h2>Témoignages</h2>
        <p>"Cette formation a changé ma vie!" - Jean Dupont</p>
        <p>"Incroyable expérience d'apprentissage." - Marie Curie</p>
    </section>
    <section id="signup">
        <h2>Inscrivez-vous maintenant</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>
            <input type="submit" value="S'inscrire">
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Vendre Ma Formation. Tous droits réservés.</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

h2 {
    color: #333;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background-color: #e4e4e4;
    margin: 5px 0;
    padding: 10px;
    border-radius: 4px;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    margin: 10px 0 5px;
}

input[type="text"], input[type="email"] {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

input[type="submit"] {
    padding: 10px;
    border: none;
    border-radius: 4px;
    background-color: #333;
    color: #fff;
    cursor: pointer;
}

input[type="submit"]:hover {
    background-color: #555;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: #fff;
    position: fixed;
    width: 100%;
    bottom: 0;
}
