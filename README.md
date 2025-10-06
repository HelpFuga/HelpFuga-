# HelpFuga-
Pagina web de localizaciones de fuga
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helpfuga - Detección de fugas en Barcelona</title>
    <link rel="stylesheet" href="estilo.css">
    <link rel="icon" href="favicon.ico">
    <!-- Fuente moderna Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600;800&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar">
        <div class="logo-nav">
            <span class="logo-title">Helpfuga</span>
        </div>
        <ul>
            <li><a href="#fugas" class="active">Fugas</a></li>
            <li><a href="#equipo">Equipo</a></li>
            <li><a href="#tecnologia">Tecnología</a></li>
            <li><a href="#zonas">Zonas</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
        <div class="contact-info-nav">
            <span>📞 <a href="tel:+34632980683">632 980 683</a></span>
            <span>✉️ <a href="mailto:varelajimmy30@gmail.com">varelajimmy30@gmail.com</a></span>
        </div>
    </nav>

    <main>
        <section id="fugas" class="card">
            <h2>¿Tienes una fuga?</h2>
            <p>Detectamos fugas en minutos usando tecnología de gas traza, segura y no invasiva. Sin romper paredes ni dañar muebles. ¡Sube una foto o vídeo de tu caso para analizarlo!</p>
        </section>

        <section id="equipo" class="card">
            <h2>¿Quiénes somos?</h2>
            <p>
                En Helpfuga somos un equipo de fontaneros con años de experiencia, formados y especializados en la detección de fugas de agua.<br><br>
                Aunque conocemos todos los aspectos del oficio, nuestra especialidad es encontrar fugas con precisión quirúrgica, sin romper suelos, techos ni paredes.<br><br>
                Nuestra pasión por el detalle, el uso de tecnología de punta y la atención cercana al cliente nos han convertido en una referencia en el sector. Sabemos lo frustrante que puede ser una fuga oculta, por eso nos enfocamos en resolver el problema de raíz, rápido y sin daños.
            </p>
        </section>

        <section id="tecnologia" class="card">
            <h2>Tecnología segura y avanzada</h2>
            <p>
                En Helpfuga apostamos por la tecnología más avanzada para proteger tu hogar y darte resultados exactos.<br><br>
                Utilizamos un sistema de detección basado en un gas trazador compuesto de hidrógeno y nitrógeno, una mezcla completamente segura, no tóxica, no corrosiva y no inflamable, aprobada por nuestros proveedores para su uso en entornos domésticos y profesionales.<br><br>
                Este gas se introduce en las tuberías, y gracias a nuestra máquina de última generación, podemos detectar con altísima precisión el punto exacto donde se escapa.<br><br>
                No hablamos de un equipo cualquiera: se trata de un instrumento profesional de alta gama, de los más costosos del mercado, reservado para especialistas. La calidad del equipo marca la diferencia… y se nota en los resultados.<br><br>
                ✅ Sin romper<br>
                ✅ Sin obras<br>
                ✅ Sin riesgos<br>
                ✅ Con diagnóstico en minutos
            </p>
        </section>

        <section id="zonas" class="card">
            <h2>Zonas de servicio</h2>
            <p>
                Actualmente ofrecemos servicio en toda la ciudad de Barcelona y en el Baix Llobregat, incluyendo municipios como Esplugues de Llobregat, Cornellà, Sant Boi, L’Hospitalet, Gavà, El Prat, entre muchos otros.<br><br>
                Nuestra base operativa se encuentra en Barcelona ciudad y Esplugues, lo que nos permite cubrir de manera eficiente tanto la capital como las zonas colindantes.<br><br>
                Nos desplazamos directamente al lugar, siempre bajo cita previa, garantizando atención personalizada y rápida.<br><br>
                Además, estamos en expansión: pronto ofreceremos cobertura en todo el territorio nacional, para que más personas puedan beneficiarse de un diagnóstico preciso sin daños ni complicaciones.
            </p>
        </section>

        <section id="contacto" class="card">
            <h2>Contacto rápido</h2>
            <p>
                ¿Tienes dudas? Contáctanos por WhatsApp, correo, teléfono o formulario. Respondemos rápido y con atención personalizada.<br><br>
                <strong>Teléfono:</strong> <a href="tel:+34632980683">632 980 683</a><br>
                <strong>Correo:</strong> <a href="mailto:varelajimmy30@gmail.com">varelajimmy30@gmail.com</a>
            </p>
            <div class="contact-buttons">
                <a href="https://wa.me/34632980683" class="btn">WhatsApp</a>
                <a href="mailto:varelajimmy30@gmail.com" class="btn-secondary">Correo</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Helpfuga. Todos los derechos reservados.</p>
    </footer>
</body>
</html>body {
    font-family: 'Montserrat', Arial, sans-serif;
    margin: 0;
    background-color: #fff7eb;
    color: #222;
}
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: linear-gradient(90deg, #ff8800 70%, #ffb347 100%);
    padding: 0.6em 1.2em;
    box-shadow: 0 2px 10px rgba(255,136,0,0.13);
    position: sticky;
    top: 0; z-index: 10;
    flex-wrap: wrap;
}
.logo-nav {
    display: flex;
    align-items: center;
}
.logo-title {
    font-size: 1.6em; font-weight: 800; color: #fff;
    letter-spacing: 2px;
}
.navbar ul {
    display: flex; list-style: none; margin: 0; padding: 0;
}
.navbar li { margin: 0 0.6em; }
.navbar a {
    color: #fff;
    text-decoration: none;
    font-weight: 600;
    padding: 0.4em 1em;
    border-radius: 20px;
    transition: background 0.15s, color 0.15s;
}
.navbar a.active, .navbar a:hover {
    background: #fff;
    color: #ff8800;
}
.contact-info-nav {
    display: flex;
    gap: 1em;
    font-size: 1em;
    align-items: center;
}
.contact-info-nav a {
    color: #fff;
    text-decoration: underline;
    font-weight: 600;
    transition: color 0.2s;
}
.contact-info-nav a:hover {
    color: #222;
}
main {
    max-width: 900px;
    margin: 2em auto;
    padding: 0 1em;
}
.card {
    background: #fff;
    border-radius: 18px;
    box-shadow: 0 2px 14px rgba(255,136,0,0.09);
    margin-bottom: 2em;
    padding: 2em 1.5em;
    transition: box-shadow 0.16s;
    position: relative;
}
.card:hover {
    box-shadow: 0 6px 22px rgba(255,136,0,0.15);
}
.card h2 {
    color: #ff8800;
    font-size: 2em;
    margin-top: 0;
    font-weight: 800;
    letter-spacing: 1px;
}
.card p {
    font-size: 1.14em;
    margin-top: 1em;
    font-weight: 600;
    line-height: 1.7;
}
.contact-buttons {
    margin-top: 1em;
}
.btn, .btn-secondary {
    display: inline-block;
    margin: 0.4em 0.3em;
    padding: 0.7em 2em;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    font-size: 1em;
    transition: box-shadow 0.15s, transform 0.15s;
    box-shadow: 0 2px 12px rgba(255,136,0,0.10);
}
.btn {
    background-color: #ff8800;
    color: white;
    border: none;
}
.btn:hover {
    background-color: #ff6600;
    transform: translateY(-2px) scale(1.045);
    box-shadow: 0 4px 18px rgba(255,136,0,0.19);
}
.btn-secondary {
    background-color: #fff;
    color: #ff8800;
    border: 2px solid #ff8800;
}
.btn-secondary:hover {
    background-color: #ffe1c1;
    color: #ff6600;
    border-color: #ff6600;
    transform: translateY(-2px) scale(1.045);
}
footer {
    text-align: center;
    padding: 1.2em;
    background: linear-gradient(90deg, #ff8800 60%, #ffb347 100%);
    color: white;
    font-size: 1em;
    letter-spacing: 1px;
    margin-top: 2em;
    border-radius: 12px 12px 0 0;
    box-shadow: 0 -2px 12px rgba(255,136,0,0.07);
}
@media (max-width: 700px) {
    .navbar ul { flex-direction: column; }
    .navbar li { margin: 0.4em 0; }
    main { padding: 0 0.5em; }
    .card { padding: 1.2em 0.6em; }
    .card h2 { font-size: 1.3em; }
    .contact-info-nav { flex-direction: column; gap: 0.4em; font-size: 0.95em;}
}
