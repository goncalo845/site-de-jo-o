<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de João</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bem-vindo à Página de João</h1>
    </header>

    <main>
        <section>
            <h2>Aniversário da cidade de Vertente do Lério</h2>
            <img src="teste.jpg" alt="Gráfico Personalizado">
            <p>Esta é uma arte que fiz para o aniversário da minha cidade.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Sua Empresa. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #ffffff;
    color: rgb(253, 109, 109);
    padding: 10px 20px;
    text-align: center;
}

main {
    padding: 20px;
}

h1, h2 {
    color: #3609db;
}

img {
    max-width: 100%;
    height: auto;
    margin:20px;
    display:block;
}

footer {
    background-color: hsl(0, 0%, 100%);
    color: rgb(255, 111, 111);
    text-align: center;
    padding: 10px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}
