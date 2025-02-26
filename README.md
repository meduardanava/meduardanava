<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu GitHub Stats</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: white;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        h1, h2 {
            color: #a736f7;
        }

        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }

        .rainbow-line {
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, red, orange, yellow, green, blue, indigo, violet);
            background-size: 400% 400%;
            animation: rainbow 4s linear infinite;
        }

        @keyframes rainbow {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .about-me {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            margin-bottom: 20px;
        }

        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #a736f7;
            box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.3);
        }

        .social-links a {
            margin: 10px;
            text-decoration: none;
            font-size: 24px;
            color: #a736f7;
            transition: 0.3s;
        }

        .social-links a:hover {
            color: #ffcc00;
        }

        img {
            width: 100%;
            max-width: 600px;
            margin: 10px 0;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.3);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Maria Eduarda Nava</h1>
        <div class="rainbow-line"></div>

        <div class="about-me">
            <p>Acadêmica do 6º período de Análise e Desenvolvimento de Sistemas na Universidade Paranaense.</p>
            <p>Buscando conhecimento na área da Tecnologia</p>
            <p>📚 Atualmente estou me aprofundando em <strong>Análise de Teste, QA, Angular e desenvolvimento Front-End</strong>.</p>
            
            <div class="social-links">
                <a href="https://www.linkedin.com/in/maria-eduarda-nava/" target="_blank">💼 LinkedIn</a>
            </div>
        </div>

        <h1>📊 Estatísticas do GitHub</h1>
        <div class="rainbow-line"></div>

        <img src="https://github-readme-stats.vercel.app/api?username=meduardanava&show_icons=true&theme=radical&count_private=true" alt="GitHub Stats">
        
        <h2>🚀 Linguagens Mais Usadas</h2>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=meduardanava&layout=compact&langs_count=8&theme=radical" alt="Linguagens mais usadas">
        
        <h2>📈 Gráfico de Commits</h2>
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=meduardanava&theme=github-dark" alt="GitHub Contributions Graph">
        
        <h2>🌍 Linguagens que já explorei</h2>
        <img src="https://skillicons.dev/icons?i=html,css,js,ts,java,angular" alt="Linguagens">

        <div class="rainbow-line"></div>
    </div>

</body>
</html>
