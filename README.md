<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Meu Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Serviços</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Sobre Nós</h2>
            <p>Este é um site de exemplo criado para demonstrar como montar um site simples com HTML, CSS e JavaScript.</p>
        </section>

        <section>
            <h2>Nossos Serviços</h2>
            <p>Oferecemos serviços de desenvolvimento web e design.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
 /* Reseta estilos padrões */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

header {
    background: #35424a;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin-bottom: 10px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

main section {
    margin-bottom: 20px;
}

footer {
    background: #35424a;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
 // Este é um exemplo simples de JavaScript para adicionar funcionalidades no futuro
document.addEventListener("DOMContentLoaded", function() {
    console.log("Site carregado com sucesso!");
    // Aqui você pode adicionar funcionalidades interativas
});
