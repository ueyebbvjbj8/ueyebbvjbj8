<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Web Interactiva</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenido a mi Página Web Interactiva</h1>
    </header>
    <main>
        <section id="content">
            <h2>Artículos</h2>
            <ul>
                <li>Artículo 1</li>
                <li>Artículo 2</li>
                <li>Artículo 3</li>
            </ul>
            <button id="alertButton">Haz clic aquí</button>
        </section>
    </main>
    <script src="scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1em 0;
    text-align: center;
}

main {
    padding: 1em;
}

h2 {
    color: #4CAF50;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    background-color: white;
    margin: 0.5em 0;
    padding: 1em;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 0.5em 1em;
    cursor: pointer;
    border-radius: 5px;
    font-size: 1em;
}

button:hover {
    background-color: #45a049;
}
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1em 0;
    text-align: center;
}

main {
    padding: 1em;
}

h2 {
    color: #4CAF50;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    background-color: white;
    margin: 0.5em 0;
    padding: 1em;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 0.5em 1em;
    cursor: pointer;
    border-radius: 5px;
    font-size: 1em;
}

button:hover {
    background-color: #45a049;
}
document.addEventListener('DOMContentLoaded', function() {
    document.getElementById('alertButton').addEventListener('click', function() {
        alert('¡Has hecho clic en el botón!');
    });
});
