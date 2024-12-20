<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Incentiva el Uso de la Bicicleta!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background 0.3s;
        }
        nav a:hover {
            background: #4CAF50;
        }
        section {
            padding: 2rem;
            text-align: center;
        }
        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }
        .benefit {
            background: white;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>¡Muévete en Bicicleta!</h1>
        <p>Una opción saludable, ecológica y divertida.</p>
    </header>

    <nav>
        <a href="#benefits">Beneficios</a>
        <a href="#tips">Consejos</a>
        <a href="#join">Únete</a>
    </nav>

    <section id="benefits">
        <h2>Beneficios de usar la bicicleta</h2>
        <div class="benefits">
            <div class="benefit">
                <h3>Salud</h3>
                <p>Fortalece el corazón, mejora la resistencia física y reduce el estrés.</p>
            </div>
            <div class="benefit">
                <h3>Medio Ambiente</h3>
                <p>Reduce la contaminación y ayuda a combatir el cambio climático.</p>
            </div>
            <div class="benefit">
                <h3>Ahorro</h3>
                <p>Menos gastos en combustible y mantenimiento comparado con un auto.</p>
            </div>
        </div>
    </section>

    <section id="tips">
        <h2>Consejos para comenzar</h2>
        <p>Si eres nuevo en el mundo de la bicicleta, sigue estos consejos:</p>
        <ul>
            <li>Empieza con rutas cortas y seguras.</li>
            <li>Usa equipo de seguridad, como casco y luces.</li>
            <li>Mantén tu bicicleta en buen estado con revisiones regulares.</li>
        </ul>
    </section>

    <section id="join">
        <h2>Únete a nuestra comunidad</h2>
        <p>Comparte tus experiencias, encuentra rutas y pedalea con otros entusiastas.</p>
        <button style="padding: 1rem 2rem; background-color: #4CAF50; color: white; border: none; border-radius: 5px; font-size: 1rem; cursor: pointer;">
            ¡Regístrate Ahora!
        </button>
    </section>

    <footer>
        <p>© 2024 Muévete en Bicicleta. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
