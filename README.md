<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Banco</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenido a Mi Banco</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Accede a tu cuenta</h2>
            <form action="/login" method="post">
                <label for="username">Usuario:</label>
                <input type="text" id="username" name="username">
                <label for="password">Contraseña:</label>
                <input type="password" id="password" name="password">
                <button type="submit">Iniciar sesión</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Mi Banco. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

