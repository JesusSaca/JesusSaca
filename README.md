## Hi there 👋

<!--
**JesusSaca/JesusSaca** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
    <title>Jesús Alexis Saca Vásquez - GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #0f0f23 0%, #1a1a3e 50%, #2d1b3d 100%);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #ffffff;
            min-height: 100vh;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header-section {
            text-align: center;
            margin-bottom: 40px;
            position: relative;
            overflow: hidden;
            border-radius: 20px;
            background: linear-gradient(45deg, #1e3c72, #2a5298);
            padding: 60px 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }

        .header-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse"><path d="M 10 0 L 0 0 0 10" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="0.5"/></pattern></defs><rect width="100" height="100" fill="url(%23grid)"/></svg>') repeat;
            opacity: 0.3;
        }

        .profile-avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            background: linear-gradient(45deg, #667eea, #764ba2);
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
            font-weight: bold;
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
            position: relative;
            z-index: 2;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        .name {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #00ff87, #60efff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            position: relative;
            z-index: 2;
        }

        .title {
            font-size: 1.5rem;
            color: #a0a0ff;
            margin-bottom: 20px;
            position: relative;
            z-index: 2;
        }

        .section {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 8px 32px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }

        .section:hover {
            transform: translateY(-5px);
        }

        .section-title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
            color: #00ff87;
        }

        .section-icon {
            font-size: 1.5rem;
        }

        .about-text {
            font-size: 1.1rem;
            color: #e0e0e0;
            margin-bottom: 20px;
            text-align: center;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .tech-category {
            background: rgba(255, 255, 255, 0.03);
            border-radius: 12px;
            padding: 20px;
            border-left: 4px solid #00ff87;
        }

        .tech-category h4 {
            color: #00ff87;
            margin-bottom: 15px;
            font-size: 1.2rem;
        }

        .tech-item {
            display: inline-flex;
            align-items: center;
            background: rgba(255, 255, 255, 0.1);
            padding: 8px 15px;
            border-radius: 25px;
            margin: 5px;
            font-size: 0.9rem;
            transition: all 0.3s ease;
        }

        .tech-item:hover {
            background: rgba(0, 255, 135, 0.2);
            transform: scale(1.05);
        }

        .level {
            font-size: 0.8rem;
            color: #a0a0ff;
            margin-left: 5px;
        }

        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .stat-card {
            background: linear-gradient(135deg, rgba(0, 255, 135, 0.1), rgba(96, 239, 255, 0.1));
            border-radius: 15px;
            padding: 25px;
            text-align: center;
            border: 1px solid rgba(0, 255, 135, 0.3);
        }

        .stat-number {
            font-size: 3rem;
            font-weight: bold;
            color: #00ff87;
            display: block;
        }

        .stat-label {
            color: #a0a0ff;
            font-size: 1rem;
            margin-top: 5px;
        }

        .projects-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 20px;
        }

        .project-card {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0.02));
            border-radius: 15px;
            padding: 25px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            border-color: #00ff87;
            box-shadow: 0 15px 35px rgba(0, 255, 135, 0.2);
        }

        .project-title {
            color: #00ff87;
            font-size: 1.3rem;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .project-description {
            color: #e0e0e0;
            margin-bottom: 15px;
        }

        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .tech-tag {
            background: rgba(96, 239, 255, 0.2);
            color: #60efff;
            padding: 4px 12px;
            border-radius: 15px;
            font-size: 0.8rem;
        }

        .university-info {
            text-align: center;
            background: linear-gradient(45deg, rgba(0, 255, 135, 0.1), rgba(96, 239, 255, 0.1));
            border-radius: 15px;
            padding: 25px;
            border: 1px solid rgba(0, 255, 135, 0.3);
        }

        .university-name {
            font-size: 1.3rem;
            color: #00ff87;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .degree {
            font-size: 1.1rem;
            color: #60efff;
            margin-bottom: 5px;
        }

        .location {
            color: #a0a0ff;
        }

        .floating-shapes {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .shape {
            position: absolute;
            opacity: 0.1;
            animation: float 6s ease-in-out infinite;
        }

        .shape:nth-child(1) {
            top: 20%;
            left: 10%;
            animation-delay: 0s;
        }

        .shape:nth-child(2) {
            top: 60%;
            right: 10%;
            animation-delay: 2s;
        }

        .shape:nth-child(3) {
            bottom: 20%;
            left: 20%;
            animation-delay: 4s;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(180deg); }
        }

        @media (max-width: 768px) {
            .name { font-size: 2rem; }
            .title { font-size: 1.2rem; }
            .container { padding: 10px; }
            .section { padding: 20px; }
            .tech-grid { grid-template-columns: 1fr; }
            .projects-container { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>
    <div class="floating-shapes">
        <div class="shape">💻</div>
        <div class="shape">🚀</div>
        <div class="shape">⚡</div>
    </div>

    <div class="container">
        <!-- Header Section -->
        <div class="header-section">
            <div class="profile-avatar">JS</div>
            <h1 class="name">Jesús Alexis Saca Vásquez</h1>
            <p class="title">Estudiante de Ingeniería en Computación e Informática</p>
        </div>

        <!-- About Section -->
        <div class="section">
            <h2 class="section-title">
                <span class="section-icon">👨‍💻</span>
                Sobre mí
            </h2>
            <p class="about-text">
                Estudiante de Ingeniería en Computación e Informática con sólidos conocimientos en análisis de datos, 
                desarrollo de software y programación de bases de datos. Destacado por mi compromiso académico, 
                capacidad autodidacta y habilidades técnicas. Orientado al trabajo en equipo con enfoque en Business Intelligence.
            </p>
            <p class="about-text">
                🎯 <strong>Objetivo:</strong> Desarrollar carrera profesional en empresas internacionales especializadas en 
                análisis de datos y programación de bases de datos.
            </p>
        </div>

        <!-- Education Section -->
        <div class="section">
            <h2 class="section-title">
                <span class="section-icon">🎓</span>
                Formación Académica
            </h2>
            <div class="university-info">
                <div class="university-name">Universidad Nacional Pedro Ruiz Gallo</div>
                <div class="degree">Ingeniería en Computación e Informática</div>
                <div class="location">Lambayeque, Perú • Cursando 5to ciclo</div>
            </div>
        </div>

        <!-- Technologies Section -->
        <div class="section">
            <h2 class="section-title">
                <span class="section-icon">🛠️</span>
                Tecnologías y Herramientas
            </h2>
            <div class="tech-grid">
                <div class="tech-category">
                    <h4>💻 Lenguajes de Programación</h4>
                    <div class="tech-item">C# <span class="level">(Intermedio)</span></div>
                    <div class="tech-item">C++ <span class="level">(Intermedio)</span></div>
                    <div class="tech-item">HTML/CSS <span class="level">(Intermedio)</span></div>
                    <div class="tech-item">Python <span class="level">(Básico)</span></div>
                    <div class="tech-item">Java <span class="level">(Básico)</span></div>
                    <div class="tech-item">R <span class="level">(Básico)</span></div>
                </div>

                <div class="tech-category">
                    <h4>🗄️ Bases de Datos y Análisis</h4>
                    <div class="tech-item">SQL Server <span class="level">(Intermedio)</span></div>
                    <div class="tech-item">Excel <span class="level">(Intermedio)</span></div>
                    <div class="tech-item">Power BI <span class="level">(Básico)</span></div>
                </div>

                <div class="tech-category">
                    <h4>⚙️ Herramientas de Desarrollo</h4>
                    <div class="tech-item">Visual Studio</div>
                    <div class="tech-item">Visual Studio Code</div>
                    <div class="tech-item">NetBeans</div>
                </div>

                <div class="tech-category">
                    <h4>🤝 Habilidades Blandas</h4>
                    <div class="tech-item">Trabajo en equipo</div>
                    <div class="tech-item">Autodidacta</div>
                    <div class="tech-item">Compromiso</div>
                    <div class="tech-item">Resiliencia</div>
                </div>
            </div>
        </div>

        <!-- Stats Section -->
        <div class="section">
            <h2 class="section-title">
                <span class="section-icon">📊</span>
                Estadísticas Académicas
            </h2>
            <div class="stats-container">
                <div class="stat-card">
                    <span class="stat-number">5°</span>
                    <div class="stat-label">Ciclo Actual</div>
                </div>
                <div class="stat-card">
                    <span class="stat-number">1°</span>
                    <div class="stat-label">Lugar AchiTech Challenge</div>
                </div>
                <div class="stat-card">
                    <span class="stat-number">BI</span>
                    <div class="stat-label">Enfoque Principal</div>
                </div>
            </div>
        </div>

        <!-- Projects Section -->
        <div class="section">
            <h2 class="section-title">
                <span class="section-icon">🚀</span>
                Proyectos Destacados
            </h2>
            <div class="projects-container">
                <div class="project-card">
                    <div class="project-title">🏆 AchiTech Challenge 2025</div>
                    <div class="project-description">
                        Primer lugar en concurso de programación - Categoría Experto. 
                        Demostración de habilidades técnicas avanzadas trabajando en equipo universitario.
                    </div>
                    <div class="project-tech">
                        <span class="tech-tag">Algoritmos</span>
                        <span class="tech-tag">Programación</span>
                        <span class="tech-tag">Trabajo en Equipo</span>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-title">📊 Sistema OLAP de Análisis de Datos</div>
                    <div class="project-description">
                        Desarrollo de dashboards con Excel, implementación de Integration Services Project 
                        en Visual Studio, creación de OLAP con diseño estrella y análisis avanzado.
                    </div>
                    <div class="project-tech">
                        <span class="tech-tag">SQL Server</span>
                        <span class="tech-tag">Excel</span>
                        <span class="tech-tag">Visual Studio</span>
                        <span class="tech-tag">OLAP</span>
                        <span class="tech-tag">BI</span>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-title">💻 Proyectos Académicos de Software</div>
                    <div class="project-description">
                        Desarrollo de aplicaciones de software como productos acreditables finales, 
                        aplicando metodologías de desarrollo y buenas prácticas de programación.
                    </div>
                    <div class="project-tech">
                        <span class="tech-tag">C#</span>
                        <span class="tech-tag">Bases de Datos</span>
                        <span class="tech-tag">Metodologías</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Contact Section -->
        <div class="section">
            <h2 class="section-title">
                <span class="section-icon">📫</span>
                Contacto
            </h2>
            <div style="text-align: center;">
                <p style="color: #e0e0e0; font-size: 1.1rem;">
                    📧 <strong>Email:</strong> j22.saca@gmail.com<br>
                    📍 <strong>Ubicación:</strong> Lambayeque, Perú
                </p>
                <p style="color: #a0a0ff; margin-top: 15px;">
                    🔍 Buscando oportunidades en Business Intelligence y desarrollo de software
                </p>
            </div>
        </div>
    </div>
</body>
</html>
