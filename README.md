<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Meu Portfólio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Seu Nome</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>
            Uma breve descrição sobre você. Fale sobre sua formação, experiência e objetivos.
        </p>
    </section>
    <section id="projetos">
        <h2>Projetos</h2>
        <div class="projetos-lista">
            <div class="projeto">
                <h3>Projeto 1</h3>
                <p>Descrição do projeto 1.</p>
                <a href="#">Veja mais</a>
            </div>
            <div class="projeto">
                <h3>Projeto 2</h3>
                <p>Descrição do projeto 2.</p>
                <a href="#">Veja mais</a>
            </div>
            <!-- Adicione mais projetos aqui -->
        </div>
    </section>
    <section id="contato">
        <h2>Contato</h2>
        <form>
            <label for="nome">Nome:fulano </label>
            <input type="text" id="nome" name="nome" required>
            <label for="email">Email:fulano@gmail.com </label>
            <input type="email" id="email" name="email" required>
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Seu Nome. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
