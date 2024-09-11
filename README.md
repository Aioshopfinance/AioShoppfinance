# AioShoppfinance<!DOCTYPE html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AioShopFinance</title>
    <style>
        body {
            background-color: #1a1a1a; /* Fundo preto */
            color: white; /* Texto branco */
            font-family: 'Orbitron', sans-serif; /* Fonte futurista */
        }

        header {
            background-color: #00FFFF; /* Cor neon */
            padding: 20px;
            text-align: center;
        }

        nav a {
            color: white;
            font-size: 18px; /* Aumentar o tamanho do texto do menu */
            padding: 10px 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #FF00FF; /* Efeito hover neon */
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        .section {
            margin: 20px 0;
            padding: 20px;
            background: white;
            border-radius: 8px;
        }

        .section h2 {
            color: #2a3f54;
        }

        .footer {
            background-color: #2a3f54;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .product {
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .services-links {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }

        .service-button {
            padding: 15px 30px;
            background-color: #00FFFF;
            color: #1a1a1a;
            border-radius: 10px;
            text-decoration: none;
            font-family: 'Arial', sans-serif;
            font-size: 18px;
            transition: all 0.3s ease;
        }

        .service-button:hover {
            background-color: #FF00FF;
            color: white;
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>AioShopFinance</h1>
    </header>

    <!-- Menu de navegação atualizado -->
    <nav>
        <a href="index.html">Página Inicial</a>
        <a href="investimentos.html">Investimentos</a>
        <a href="renda-extra.html">Renda Extra</a>
        <a href="ferramentas.html">Ferramentas</a>
        <a href="#products">Infoprodutos</a>
        <a href="blog.html">Blog</a>
    </nav>

    <div class="container">
        <section id="investments" class="section">
            <h2>Investimentos</h2>
            <p><a href="investimentos.html">Saiba mais sobre como investir com sabedoria.</a></p>
        </section>

        <section id="extra-income" class="section">
            <h2>Renda Extra</h2>
            <p><a href="renda-extra.html">Descubra diversas maneiras de criar uma renda extra.</a></p>
        </section>

        <section id="tools" class="section">
            <h2>Ferramentas</h2>
            <p><a href="ferramentas.html">Explore as ferramentas de cálculo e monitoramento.</a></p>
        </section>

        <section id="products" class="section">
            <h2>Infoprodutos Financeiros</h2>
            <div class="product">
                <h3><a href="ebook-investir.html">A Importância de Investir</a></h3>
                <p>Aprenda os princípios básicos e avançados para fazer investimentos de forma segura e lucrativa.</p>
            </div>
            <div class="product">
                <h3><a href="ebook-mentalidade-investimentos.html">Mudando Sua Mentalidade para Investimentos</a></h3>
                <p>Entenda como mudar sua mentalidade para obter sucesso nos investimentos de longo prazo.</p>
            </div>
            <div class="product">
                <h3><a href="audiobook-intuicao-investir.html">Usando Sua Intuição para Investir</a></h3>
                <p>Descubra como utilizar sua intuição como ferramenta para tomar decisões mais rápidas e precisas no mercado financeiro.</p>
            </div>
            <div class="product">
                <h3><a href="audiobook-oportunidades-investimento.html">Aproveitando as Oportunidades de Investimento</a></h3>
                <p>Aprenda a identificar e aproveitar as melhores oportunidades de investimento no mercado.</p>
            </div>
            <div class="product">
                <h3><a href="audiobook-renda-extra.html">Criando Sua Própria Renda Extra</a></h3>
                <p>Saiba como criar fontes de renda extra para garantir maior estabilidade financeira.</p>
            </div>
        </section>
    </div>

    <footer class="footer">
        <p>&copy; 2024 AioShopFinance. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

