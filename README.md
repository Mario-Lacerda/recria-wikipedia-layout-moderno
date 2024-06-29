# Desafio Dio - Recriando o Wikipedia com Layout Moderno   



**Projeto: Recriando o Wikipedia com Layout Moderno**



O Wikipedia é uma enciclopédia online gratuita e colaborativa que contém milhões de artigos em vários idiomas. Este projeto visa recriar o Wikipedia com um layout moderno e responsivo, usando tecnologias da web como HTML, CSS e JavaScript.



### **Requisitos**

- Conhecimento básico de HTML, CSS e JavaScript
- Editor de código
- Navegador da web



### **Estrutura do Projeto**

O projeto será estruturado nas seguintes seções:



- **Página Inicial:** Exibe uma lista de artigos em destaque e uma barra de pesquisa.
- **Página do Artigo:** Exibe o conteúdo do artigo, incluindo texto, imagens e referências.
- **Barra de Navegação:** Fornece links para a página inicial, a página de sobre e a página de contato.
- **Rodapé:** Exibe informações de direitos autorais e links para as redes sociais.



### **Implementação**



**Página Inicial**

plaintext



```plaintext
<!DOCTYPE html>
<html>
<head>
  <title>Wikipedia</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Wikipedia</h1>
    <form action="/search">
      <input type="text" name="q" placeholder="Pesquisar">
      <button type="submit">Pesquisar</button>
    </form>
  </header>
  <main>
    <section>
      <h2>Artigos em Destaque</h2>
      <ul>
        <li><a href="/articles/Einstein">Albert Einstein</a></li>
        <li><a href="/articles/Segunda Guerra Mundial">Segunda Guerra Mundial</a></li>
        <li><a href="/articles/Brasil">Brasil</a></li>
      </ul>
    </section>
  </main>
  <footer>
    <p>Copyright &copy; 2023 Wikipedia</p>
    <ul>
      <li><a href="/about">Sobre</a></li>
      <li><a href="/contact">Contato</a></li>
    </ul>
  </footer>
</body>
</html>
```



### **Página do Artigo**

plaintext



```plaintext
<!DOCTYPE html>
<html>
<head>
  <title>Albert Einstein</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Wikipedia</h1>
    <nav>
      <a href="/">Página Inicial</a>
      <a href="/about">Sobre</a>
      <a href="/contact">Contato</a>
    </nav>
  </header>
  <main>
    <article>
      <h1>Albert Einstein</h1>
      <p>Albert Einstein (Ulm, 14 de março de 1879 — Princeton, 18 de abril de 1955) foi um físico teórico alemão, amplamente reconhecido como um dos maiores físicos de todos os tempos.</p>
      <p>Einstein desenvolveu a teoria da relatividade, uma das duas principais teorias da física moderna, juntamente com a mecânica quântica. A teoria da relatividade explica a natureza do espaço, tempo, gravidade e movimento.</p>
      <p>Einstein também fez contribuições significativas para a física estatística, teoria quântica e cosmologia. Ele recebeu o Prêmio Nobel de Física em 1921 por sua explicação do efeito fotoelétrico.</p>
    </article>
  </main>
  <footer>
    <p>Copyright &copy; 2023 Wikipedia</p>
  </footer>
</body>
</html>
```



### **Barra de Navegação**

css



```css
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #f5f5f5;
  padding: 10px;
}

nav a {
  text-decoration: none;
  color: #000;
  padding: 5px;
}

nav a:hover {
  background-color: #ddd;
}
```



### **Rodapé**

css



```css
footer {
  background-color: #f5f5f5;
  padding: 10px;
  text-align: center;
}

footer p {
  margin-bottom: 5px;
}

footer a {
  text-decoration: none;
  color: #000;
  padding: 5px;
}

footer a:hover {
  background-color: #ddd;
}
```



### **Conclusão**



Este projeto fornece uma base abrangente para recriar o Wikipedia com um layout moderno e responsivo. Ele aborda aspectos essenciais como estrutura de página, navegação e formatação de conteúdo. Ao implementar essas estratégias, os desenvolvedores podem criar uma interface de usuário atraente e fácil de usar para sua enciclopédia online.

