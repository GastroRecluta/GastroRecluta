## Hi there 👋

<!--
**GastroRecluta/GastroRecluta** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consultora Gastronómica</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background: #ff6600; color: white; text-align: center; padding: 1rem; }
        nav { text-align: center; padding: 1rem; }
        nav a { margin: 0 15px; text-decoration: none; color: #ff6600; font-weight: bold; }
        section { padding: 2rem; text-align: center; }
        .cta-button { background: #ff6600; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; }
        form input, form textarea { width: 80%; max-width: 500px; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; }
        form button { background: #ff6600; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; }
        footer { background: #333; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
        footer a { color: white; margin: 0 10px; text-decoration: none; }
    </style>
</head>
<body>
    <header>
        <h1>Consultora Gastronómica</h1>
        <p>Conectamos talento gastronómico con los mejores restaurantes</p>
    </header>

    <nav>
        <a href="#empresas">Para Empresas</a>
        <a href="#candidatos">Para Candidatos</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="empresas">
        <h2>¿Necesitas Personal?</h2>
        <p>Publica tu oferta de empleo y accede a una base de datos de candidatos.</p>
        <a href="#contacto" class="cta-button">Publicar Oferta</a>
    </section>

    <section id="candidatos">
        <h2>¿Buscas Trabajo?</h2>
        <p>Regístrate y accede a las mejores oportunidades en gastronomía.</p>
        <a href="#contacto" class="cta-button">Registrarme</a>
    </section>

    <section id="servicios">
        <h2>Nuestros Servicios</h2>
        <ul>
            <li>Revisión y mejora de CV</li>
            <li>Simulación de entrevistas</li>
            <li>Cursos online de formación gastronómica</li>
        </ul>
        <a href="#contacto" class="cta-button">Más Información</a>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Envíanos un mensaje y te responderemos a la brevedad.</p>
        <form action="mailto:info@consultoragastronomica.com" method="post" enctype="text/plain">
            <input type="text" name="nombre" placeholder="Tu nombre" required><br>
            <input type="email" name="email" placeholder="Tu correo electrónico" required><br>
            <textarea name="mensaje" placeholder="Tu mensaje" rows="5" required></textarea><br>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Consultora Gastronómica. Todos los derechos reservados.</p>
        <p>
            <a href="https://facebook.com" target="_blank">Facebook</a>
            <a href="https://instagram.com" target="_blank">Instagram</a>
            <a href="https://linkedin.com" target="_blank">LinkedIn</a>
        </p>
    </footer>
</body>
</html>
