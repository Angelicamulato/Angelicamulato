
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grupo de Mulheres - Melidrosa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fdf6fb;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f3a1c6;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            text-align: center;
            margin: 1em 0;
        }
        nav a {
            margin: 0 1em;
            color: #f3a1c6;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            margin: 2em;
            padding: 1em;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #f3a1c6;
        }
        .forum, .register {
            background-color: #ffeaf1;
            padding: 1em;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #f3a1c6;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        input[type="text"], input[type="email"], textarea {
            width: 100%;
            padding: 0.5em;
            margin: 0.5em 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        button {
            background-color: #f3a1c6;
            color: white;
            border: none;
            padding: 0.5em 1em;
            border-radius: 4px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Grupo de Mulheres - Angélica Mulato</h1>
    </header>
    <nav>
        <a href="#bem-estar">Bem-estar</a>
        <a href="#receitas">Receitas</a>
        <a href="#dicas">Dicas</a>
        <a href="#forum">Fórum</a>
        <a href="#inscricao">Inscrição</a>
    </nav>
    <section id="bem-estar">
        <h2>Bem-estar Mental e Físico</h2>
        <p>Compartilhamos dicas e práticas para manter a mente e o corpo saudáveis.</p>
    </section>
    <section id="receitas">
        <h2>Receitas de Comidas Saudáveis</h2>
        <p>Encontre aqui deliciosas receitas que promovem a saúde e o bem-estar.</p>
    </section>
    <section id="dicas">
        <h2>Dicas de Maquiagem e Moda Acessível</h2>
        <p>Dicas práticas e acessíveis de maquiagem e moda para todas as idades.</p>
    </section>
    <section id="forum" class="forum">
        <h2>Fórum de Discussão</h2>
        <p>Participe das nossas discussões e compartilhe suas experiências.</p>
        <textarea placeholder="Partilhe sua experiência (pode ser anónimo)"></textarea>
        <button>Enviar</button>
    </section>
    <section id="inscricao" class="register">
        <h2>Inscrição para Novos Membros</h2>
        <p>Junte-se a nós e faça parte do nosso grupo de mulheres inspiradoras.</p>
        <input type="text" placeholder="Nome">
        <input type="email" placeholder="Email">
        <textarea placeholder="Por que quer se juntar?"></textarea>
        <button>Inscrever-se</button>
    </section>
    <footer>
        <p>&copy; 2024 Grupo de Mulheres - Angélica Mulato</p>
    </footer>
</body>
</html>
