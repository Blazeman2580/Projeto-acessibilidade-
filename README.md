# Projeto-acessibilidade-
Projeto exemplo com boas práticas de acessibilidade na web
# Projeto Web Acessível

Este projeto demonstra **boas práticas de acessibilidade** na web, incluindo:
- Contraste adequado de cores
- Textos legíveis
- Navegação por teclado
- Descrições alternativas (`alt`) para imagens
- Layout responsivo

## Estrutura
## Como usar
1. Baixe ou clone o repositório.
2. Abra `index.html` no navegador.
3. Personalize o conteúdo e as imagens conforme necessário.

## Licença
Livre para uso educacional.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projeto Acessível</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>Projeto Web Acessível</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#galeria">Galeria</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>
  <main>
    <section id="sobre">
      <h2>Sobre o Projeto</h2>
      <p>Este projeto demonstra boas práticas de acessibilidade na web, garantindo contraste adequado, navegação por teclado e descrições alternativas para imagens.</p>
      <p class="highlight">Exemplo de destaque com contraste forte para leitura fácil.</p>
    </section>
    <section id="galeria">
      <h2>Galeria de Imagens</h2>
      <img src="imagens/equipe.jpg" alt="Imagem ilustrativa de pessoas trabalhando juntas em um projeto">
      <img src="imagens/comemoracao.jpg" alt="Imagem de uma equipe comemorando após alcançar um objetivo">
    </section>
    <section id="contato">
      <h2>Contato</h2>
      <p>Envie uma mensagem para nossa equipe acessível:</p>
      <a href="mailto:contato@projetoacessivel.com" class="button">Enviar E-mail</a>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Projeto Web Acessível</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  color: #222;
  line-height: 1.6;
}

header {
  background-color: #005f73;
  color: #fff;
  padding: 20px;
  text-align: center;
}

nav a {
  color: #fff;
  margin: 0 10px;
  text-decoration: none;
  font-weight: bold;
}

nav a:focus {
  outline: 3px solid #ffb703;
}

main {
  padding: 20px;
  max-width: 900px;
  margin: 0 auto;
}

h1, h2 {
  margin-bottom: 15px;
}

p {
  margin-bottom: 15px;
  font-size: 1.1rem;
}

img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  margin-bottom: 10px;
}

.button {
  display: inline-block;
  padding: 10px 20px;
  margin-top: 10px;
  background-color: #0a9396;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s;
}

.button:hover,
.button:focus {
  background-color: #94d2bd;
  outline: none;
}

footer {
  background-color: #005f73;
  color: #fff;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}

.highlight {
  background-color: #ee9b00;
  color: #000;
  padding: 5px 10px;
  border-radius: 5px;
}
