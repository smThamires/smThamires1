# smThamires1
Portifolio
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thamires Moreirar</title>
    
    <!-- Fonte do Google: Press Start 2P -->
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

    <!-- Link para o arquivo de estilo CSS -->
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!-- Cabeçalho -->
    <header>
        <div class="container">
            <h1>Thamires Moreira<span>Seu Nome</span></h1>
            <nav>
                <ul>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#projetos">Projetos</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Seção Sobre -->
    <section id="sobre">
        <div class="container">
            <h2>Sobre Mim</h2>
            <p>Sou uma desenvolvedora em processo de aprendizado nas areas de tecnologia e programação. Aqui estão alguns dos meus projetos!</p>
        </div>
    </section>

    <!-- Seção Projetos -->
    <section id="projetos">
        <div class="container">
            <h2>Meus Projetos</h2>
            <div class="cards">
                <div class="card">
                    <h3><a href="https://github.com/seunome/projeto1">Projeto 1</a></h3>
                    <p>Descrição do projeto 1. Este projeto é incrível!</p>
                </div>
                <div class="card">
                    <h3><a href="https://github.com/seunome/projeto2">Projeto 2</a></h3>
                    <p>Descrição do projeto 2. Um jogo simples, mas divertido!</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Contato -->
    <section id="contato">
        <div class="container">
            <h2>Contato</h2>
            <ul>
                <li><a href="mailto:email@exemplo.com">Email</a></li>
                <li><a href="https://www.linkedin.com/in/seunome">LinkedIn</a></li>
            </ul>
        </div>
    </section>

    <!-- Rodapé -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Seu Nome - Portfólio Gamer</p>
        </div>
    </footer>
</body>

</html>

/* ========================
   Reset de Estilos Padrão
   ======================== */
   * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* ========================
   Estilos Globais
   ======================== */
body {
    font-family: 'Press Start 2P', cursive; /* Fonte estilo gamer */
    background: #0e0e0e; /* Fundo escuro */
    color: #fff; /* Texto branco */
    line-height: 1.6; /* Melhor legibilidade */
}

/* ========================
   Cabeçalho
   ======================== */
header {
    background: linear-gradient(45deg, #ff00ff, #00ffff); /* Gradiente vibrante */
    padding: 10px 0;
    text-align: center;
}

header h1 {
    font-size: 3rem;
    color: #fff;
}

header h1 span {
    color: #ffcc00;
}

header nav ul {
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

header nav ul li {
    list-style: none;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    font-size: 1.2rem;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 1px;
    transition: color 0.3s;
}

header nav ul li a:hover {
    color: #ffcc00;
}

/* ========================
   Seções
   ======================== */
section {
    padding: 50px 20px;
    text-align: center;
}

#sobre {
    background: #1a1a1a; /* Cor de fundo escura */
}

#projetos {
    background: #333; /* Cor de fundo mais clara para contrastar */
}

#contato {
    background: #0a0a0a; /* Cor de fundo mais escura */
}

/* ========================
   Títulos das Seções
   ======================== */
h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
    color: #ffcc00; /* Cor amarela para destaque */
}

/* ========================
   Parágrafos
   ======================== */
p {
    font-size: 1.1rem;
    margin-bottom: 20px;
}

/* ========================
   Cartões de Projetos
   ======================== */
.cards {
    display: flex;
    justify-content: center;
    gap: 20px; /* Espaçamento entre os cartões */
}

.card {
    background: #1e1e1e; /* Fundo escuro para os cartões */
    padding: 20px;
    width: 250px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    transition: transform 0.3s ease;
}

.card:hover {
    transform: translateY(-10px); /* Efeito de elevação ao passar o mouse */
}

.card h3 {
    font-size: 1.5rem;
    color: #ffcc00; /* Título do projeto em amarelo */
    margin-bottom: 10px;
}

.card h3 a {
    text-decoration: none;
    color: #ffcc00;
}

.card h3 a:hover {
    text-decoration: underline; /* Sublinha o link ao passar o mouse */
}

.card p {
    color: #ccc; /* Texto de descrição mais claro */
    font-size: 1rem;
}

/* ========================
   Rodapé
   ======================== */
footer {
    background: #000; /* Fundo escuro para o rodapé */
    padding: 20px;
    text-align: center;
}

footer p {
    font-size: 1rem;
    color: #777; /* Texto do rodapé em cinza claro */
}

/* ========================
   Links
   ======================== */
a {
    text-decoration: none;
    color: #00ffff; /* Cor ciano para links */
}

a:hover {
    color: #ff00ff; /* Cor magenta ao passar o mouse */
}



