Avance de la pagina web
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tipos de Juegos</title>
    <style>
       
         * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        
        body {
            font-family: 'Open Sans', sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

      
        header {
            background: linear-gradient(90deg, #4b6cb7 0%, #182848 100%);
            color: #fff;
            padding: 2em 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 0.5em;
        }

        header p {
            font-size: 1.2em;
            margin-top: 0.5em;
        }

        
        nav {
            background: #fff;
            padding: 1em 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        nav a {
            margin: 0 1em;
            color: #4b6cb7;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
        }

        nav a:hover {
            color: #182848;
        }

        
        .container {
            width: 80%;
            max-width: 1200px;
            margin: 2em auto;
            padding: 2em;
            background: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

      
        section {
            margin-bottom: 2em;
        }

        section h2 {
            font-size: 2em;
            margin-bottom: 0.5em;
            color: #4b6cb7;
            border-bottom: 2px solid #4b6cb7;
            padding-bottom: 0.3em;
        }

        section p {
            margin-bottom: 1em;
            font-size: 1.1em;
            line-height: 1.6;
        }

        section ul {
            list-style-type: disc;
            padding-left: 20px;
        }

        section ul li {
            margin-bottom: 0.5em;
            font-size: 1.1em;
        }

        
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            .container {
                width: 90%;
                padding: 1em;
            }

            nav a {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Tipos de Juegos</h1>
    <p>Explora diferentes géneros de videojuegos</p>
</header>

<nav>
    <a href="#rol">Juegos de Rol</a>
    <a href="#accion">Juegos de Acción</a>
    <a href="#aventura">Juegos de Aventura</a>
    <a href="#indie">Juegos Indie</a>
    <a href="#estrategia">Juegos de Estrategia</a> <!-- Nuevo -->
    <a href="#puzzle">Juegos de Rompecabezas</a> <!-- Nuevo -->
    <a href="#deportes">Juegos de Deportes</a> <!-- Nuevo -->
    <a href="#sigilo">Juegos de Sigilo</a> <!-- Nuevo -->
</nav>

<div class="container">
    <section id="accion">
        <h2>Juegos de Acción</h2>
        <p>Los juegos de acción se enfocan en desafíos físicos que requieren coordinación mano-ojo y tiempos de reacción rápidos.</p>
        <h3>Ejemplos:</h3>
        <ul>
            <li>Call of Duty</li>
            <li>Grand Theft Auto V</li>
            <li>Fortnite</li>
        </ul>
    </section>


<section id="aventura">
    <h2>Juegos de Aventura</h2>
    <p>Los juegos de aventura se caracterizan por su enfoque en la exploración y la resolución de acertijos, a menudo con una narrativa fuerte.</p>
    <h3>Ejemplos:</h3>
    <ul>
        <li>The Legend of Zelda: Breath of the Wild</li>
        <li>Uncharted 4: A Thief's End</li>
        <li>Tomb Raider</li>
    </ul>
</section>

<section id="indie">
    <h2>Juegos Indie</h2>
    <p>Los juegos indie son creados por desarrolladores independientes, a menudo con un enfoque en la innovación y la creatividad.</p>
    <h3>Ejemplos:</h3>
    <ul>
        <li>Hollow Knight</li>
        <li>Celeste</li>
        <li>Undertale</li>
    </ul>
</section>

    <section id="estrategia"> <!-- Nuevo -->
        <h2>Juegos de Estrategia</h2>
        <p>Los juegos de estrategia requieren planificación cuidadosa y toma de decisiones estratégicas para alcanzar la victoria.</p>
        <h3>Ejemplos:</h3>
        <ul>
            <li>Age of Empires</li>
            <li>StarCraft</li>
            <li>Civilization VI</li>
        </ul>
    </section>

    <section id="puzzle"> <!-- Nuevo -->
        <h2>Juegos de Rompecabezas</h2>
        <p>Los juegos de rompecabezas desafían la mente del jugador con acertijos y desafíos lógicos.</p>
        <h3>Ejemplos:</h3>
        <ul>
            <li>Tetris</li>
            <li>Portal</li>
            <li>Monument Valley</li>
        </ul>
    </section>

    <section id="rol">
        <h2>Juegos de Rol (RPG)</h2>
        <p>Los juegos de rol se centran en la narrativa y el desarrollo del personaje, permitiendo a los jugadores asumir roles y vivir aventuras en mundos complejos.</p>
        <h3>Ejemplos:</h3>
        <ul>
            <li>The Witcher 3: Wild Hunt</li>
            <li>Final Fantasy VII</li>
            <li>Dark Souls</li>
        </ul>
    </section>

    <section id="deportes"> <!-- Nuevo -->
        <h2>Juegos de Deportes</h2>
        <p>Los juegos de deportes simulan actividades deportivas del mundo real, permitiendo a los jugadores competir en diversos eventos.</p>
        <h3>Ejemplos:</h3>
        <ul>
            <li>FIFA</li>
            <li>NBA 2K</li>
            <li>Wii Sports</li>
        </ul>
    </section>

    <section id="sigilo"> <!-- Nuevo -->
        <h2>Juegos de Sigilo</h2>
        <p>Los juegos de sigilo desafían a los jugadores a completar objetivos evitando la detección, utilizando tácticas de ocultación y estrategia.</p>
        <h3>Ejemplos:</h3>
        <ul>
            <li>Metal Gear Solid</li>
            <li>Hitman</li>
            <li>Splinter Cell</li>
        </ul>
    </section>
</div>

<footer>
    <p>&copy; 2024 Página de Juegos. Todos los derechos reservados.</p>
</footer>

</body>
</html>
