<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bruno - Tech & Marketing Specialist</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', system-ui, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(20px);
            border-radius: 24px;
            padding: 50px;
            max-width: 900px;
            width: 100%;
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.15);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .header {
            text-align: center;
            margin-bottom: 50px;
        }

        .title {
            font-size: 3.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.4rem;
            color: #6c757d;
            font-weight: 500;
        }

        .stacks-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin-bottom: 50px;
        }

        .stack-card {
            background: white;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            border: 1px solid rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .stack-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }

        .stack-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: linear-gradient(90deg, #667eea, #764ba2);
        }

        .stack-icon {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        .stack-name {
            font-size: 1.3rem;
            font-weight: 700;
            color: #2c3e50;
            margin-bottom: 10px;
        }

        .stack-desc {
            color: #6c757d;
            line-height: 1.6;
        }

        .automation-section {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 40px;
            border-radius: 16px;
            text-align: center;
        }

        .automation-title {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 20px;
        }

        .automation-desc {
            font-size: 1.1rem;
            opacity: 0.9;
            line-height: 1.6;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
        }

        .social-link {
            padding: 12px 25px;
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .social-link:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(102, 126, 234, 0.3);
        }

        @media (max-width: 768px) {
            .container {
                padding: 30px 20px;
            }
            
            .title {
                font-size: 2.5rem;
            }
            
            .stacks-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1 class="title">🚀 Bruno</h1>
            <p class="subtitle">Tech & Marketing Specialist</p>
        </div>

        <div class="stacks-grid">
            <div class="stack-card">
                <div class="stack-icon">🌐</div>
                <h3 class="stack-name">HTML5 & CSS3</h3>
                <p class="stack-desc">Desenvolvimento front-end moderno com layouts responsivos e experiências de usuário excepcionais.</p>
            </div>

            <div class="stack-card">
                <div class="stack-icon">⚡</div>
                <h3 class="stack-name">JavaScript</h3>
                <p class="stack-desc">Interatividade avançada, manipulação de DOM e desenvolvimento de funcionalidades dinâmicas.</p>
            </div>

            <div class="stack-card">
                <div class="stack-icon">💻</div>
                <h3 class="stack-name">WordPress</h3>
                <p class="stack-desc">Desenvolvimento de temas customizados, plugins e gestão completa de projetos WordPress.</p>
            </div>

            <div class="stack-card">
                <div class="stack-icon">🎨</div>
                <h3 class="stack-name">UX Design</h3>
                <p class="stack-desc">Design centrado no usuário com foco em usabilidade, acessibilidade e experiências intuitivas.</p>
            </div>

            <div class="stack-card">
                <div class="stack-icon">📈</div>
                <h3 class="stack-name">Gestão de Tráfego</h3>
                <p class="stack-desc">Estratégias de aquisição de tráfego qualificado e otimização de conversões.</p>
            </div>

            <div class="stack-card">
                <div class="stack-icon">🤖</div>
                <h3 class="stack-name">n8n & Automações</h3>
                <p class="stack-desc">Integrações avançadas e automação de processos com n8n, webhooks e APIs.</p>
            </div>
        </div>

        <div class="automation-section">
            <h2 class="automation-title">💡 Especialista em Automações</h2>
            <p class="automation-desc">
                Integro sistemas, crio fluxos automatizados e conecto ferramentas para otimizar processos 
                e aumentar a eficiência dos negócios. Experiência comprovada em projetos como integração 
                Sellflux → n8n → Google Sheets.
            </p>
        </div>

        <div class="social-links">
            <a href="https://github.com/seu-usuario" class="social-link">GitHub</a>
            <a href="https://linkedin.com/in/seu-perfil" class="social-link">LinkedIn</a>
            <a href="https://instagram.com/seu-perfil" class="social-link">Instagram</a>
        </div>
    </div>
</body>
</html>
