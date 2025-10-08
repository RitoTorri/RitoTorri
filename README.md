<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jesús Cortez - Desarrollador Backend</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            position: relative;
            overflow: hidden;
        }

        .header-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 30px;
        }

        .text-content {
            flex: 1;
            min-width: 300px;
        }

        .image-content {
            flex-shrink: 0;
        }

        .coding-gif {
            width: 300px;
            height: 200px;
            border-radius: 15px;
            object-fit: cover;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        h1 {
            color: #2c3e50;
            font-size: 2.5em;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        h2 {
            color: #34495e;
            font-size: 1.8em;
            margin-bottom: 20px;
        }

        h3 {
            color: #2c3e50;
            margin: 25px 0 15px 0;
            font-size: 1.4em;
        }

        .subtitle {
            font-size: 1.2em;
            color: #7f8c8d;
            margin-bottom: 20px;
        }

        .highlight {
            background: linear-gradient(120deg, #a8edea 0%, #fed6e3 100%);
            padding: 20px;
            border-radius: 15px;
            margin: 20px 0;
            border-left: 5px solid #667eea;
        }

        .tech-stack {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .tech-category {
            margin-bottom: 30px;
        }

        .tech-icons {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 15px 0;
            justify-content: center;
        }

        .tech-icon {
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .tech-icon:hover {
            transform: translateY(-5px);
        }

        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin: 15px 0;
        }

        .contact {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 40px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .contact-badges {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }

        .contact-badge {
            transition: all 0.3s ease;
        }

        .contact-badge:hover {
            transform: scale(1.05);
        }

        .quote {
            text-align: center;
            color: white;
            font-style: italic;
            margin-top: 30px;
            padding: 20px;
            font-size: 1.1em;
        }

        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            .coding-gif {
                width: 100%;
                max-width: 300px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            h2 {
                font-size: 1.5em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <div class="header-content">
                <div class="text-content">
                    <h1>👋 ¡Hola! Soy Jesús Cortez</h1>
                    <h2>🚀 Desarrollador Backend</h2>
                    <div class="subtitle">
                        <p>🎓 <strong>Estudiante de Ingeniería Informática</strong></p>
                        <p>💡 <strong>Apasionado por crear sistemas robustos y escalables</strong></p>
                        <p>📈 <strong>Mejorando día a día en planificación y diseño de arquitecturas completas</strong></p>
                    </div>
                </div>
                <div class="image-content">
                    <img src="https://raw.githubusercontent.com/AVS1508/AVS1508/master/assets/Night-Coding.gif" 
                         alt="Night Coding" 
                         class="coding-gif">
                </div>
            </div>
        </div>

        <!-- Tech Stack Section -->
        <div class="tech-stack">
            <h2>🛠️ Mi Stack Tecnológico</h2>
            
            <!-- Frontend -->
            <div class="tech-category">
                <h3>Frontend</h3>
                <div class="tech-icons">
                    <img src="https://skillicons.dev/icons?i=html" alt="HTML" class="tech-icon" title="HTML5">
                    <img src="https://skillicons.dev/icons?i=css" alt="CSS" class="tech-icon" title="CSS3">
                    <img src="https://skillicons.dev/icons?i=js" alt="JavaScript" class="tech-icon" title="JavaScript">
                </div>
                <div class="badges">
                    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
                    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
                    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
                </div>
            </div>

            <!-- Backend -->
            <div class="tech-category">
                <h3>Backend & Frameworks</h3>
                <div class="tech-icons">
                    <img src="https://skillicons.dev/icons?i=php" alt="PHP" class="tech-icon" title="PHP">
                    <img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" class="tech-icon" title="Node.js">
                    <img src="https://skillicons.dev/icons?i=express" alt="Express" class="tech-icon" title="Express.js">
                </div>
                <div class="badges">
                    <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
                    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
                    <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
                </div>
            </div>

            <!-- Databases -->
            <div class="tech-category">
                <h3>Bases de Datos & ORM</h3>
                <div class="tech-icons">
                    <img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" class="tech-icon" title="MySQL">
                    <img src="https://skillicons.dev/icons?i=postgresql" alt="PostgreSQL" class="tech-icon" title="PostgreSQL">
                    <img src="https://skillicons.dev/icons?i=prisma" alt="Prisma" class="tech-icon" title="Prisma">
                </div>
                <div class="badges">
                    <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
                    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
                    <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma">
                </div>
            </div>

            <!-- Tools -->
            <div class="tech-category">
                <h3>Herramientas de Desarrollo</h3>
                <div class="tech-icons">
                    <img src="https://skillicons.dev/icons?i=git" alt="Git" class="tech-icon" title="Git">
                    <img src="https://skillicons.dev/icons?i=github" alt="GitHub" class="tech-icon" title="GitHub">
                    <img src="https://skillicons.dev/icons?i=vscode" alt="VSCode" class="tech-icon" title="VS Code">
                </div>
                <div class="badges">
                    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
                    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
                    <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code">
                </div>
            </div>
        </div>

        <!-- Contact Section -->
        <div class="contact">
            <h2>📫 ¡Contáctame!</h2>
            <div class="contact-badges">
                <a href="https://www.linkedin.com/in/francisco-cortez-torres-553693380?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" 
                   target="_blank" class="contact-badge">
                    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                </a>
                <a href="mailto:cortezfrancisco025@gmail.com" class="contact-badge">
                    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                </a>
            </div>
        </div>

        <!-- Quote -->
        <div class="quote">
            <p>⭐ "El software es como la arquitectura: requiere buenos cimientos para construir grandes estructuras"</p>
        </div>
    </div>

    <script>
        // Efectos interactivos simples
        document.addEventListener('DOMContentLoaded', function() {
            const techIcons = document.querySelectorAll('.tech-icon');
            
            techIcons.forEach(icon => {
                icon.addEventListener('mouseenter', function() {
                    this.style.filter = 'brightness(1.2)';
                });
                
                icon.addEventListener('mouseleave', function() {
                    this.style.filter = 'brightness(1)';
                });
            });
        });
    </script>
</body>
</html>
