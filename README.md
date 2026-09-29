# Portf-lio-Curr-culo-Pessoal-

Portfólio / Currículo Web

Sobre o Projeto:

Este projeto consiste na criação de uma página de **Portfólio / Currículo Web** desenvolvida utilizando HTML5. O objetivo é apresentar informações pessoais, habilidades, projetos realizados e disponibilizar um formulário para contato.

A página foi desenvolvida como uma atividade prática para demonstrar o uso de uma estrutura HTML semântica, organizada e funcional**, utilizando elementos como `<header>`, `<nav>`, `<main>`, `<section>`, `<table>`, `<fieldset>` e `<footer>`.



Desenvolvedor

Nome: Kayke Willians
Área: Desenvolvimento e Tecnologia

O portfólio apresenta informações sobre o desenvolvedor, suas habilidades e alguns projetos desenvolvidos durante seus estudos na área de tecnologia.


Objetivo

O principal objetivo do projeto é desenvolver uma página web que funcione como um **portfólio e currículo online**, reunindo em um único local:

* Informações pessoais;
* Apresentação profissional;
* Habilidades técnicas;
* Projetos desenvolvidos;
* Tecnologias utilizadas;
* Formas de contato.

Além disso, o projeto tem como finalidade praticar a construção de páginas utilizando **HTML5 semântico**.



Tecnologias Utilizadas

* HTML5 – Estrutura e organização da página;
* CSS – Não utilizado nesta versão, mantendo o projeto em HTML puro;
* GitHub – Utilizado para disponibilização dos projetos e links;
* Figma – Utilizado no projeto de interface do aplicativo Pet&Go;
* Arduino / C++ – Utilizado no projeto de protótipo com Arduino.



Estrutura do Projeto

O projeto possui uma página principal organizada nas seguintes partes:

1. Cabeçalho

O `<header>` contém o nome do desenvolvedor e sua área de atuação.

Também possui um menu de navegação criado com `<nav>`, permitindo acessar rapidamente as principais seções da página:

* Sobre;
* Projetos;
* Contato.

2. Sobre Mim

A seção **Sobre Mim** apresenta:

* Foto de perfil;
* Texto de apresentação;
* Lista de habilidades.

As habilidades apresentadas no projeto são:

* HTML e CSS;
* JavaScript;
* PHP;
* MySQL;
* Git e GitHub.

A imagem de perfil foi configurada com 150px de largura e 150px de altura, conforme solicitado na atividade.

3. Meus Projetos

A seção **Meus Projetos** apresenta uma tabela com quatro colunas:

| Projeto             | Tecnologias   | Status             | Link    |
| ------------------- | ------------- | ------------------ | ------- |
| Site Pessoal        | HTML e CSS    | Concluído          | Acessar |
| Sistema de Cadastro | PHP e MySQL   | Em desenvolvimento | Acessar |
| Aplicativo Pet&Go   | Figma e UI/UX | Concluído          | Acessar |
| Projeto Arduino     | Arduino e C++ | Concluído          | Acessar |

A tabela utiliza elementos semânticos como `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` e `<td>`.

4. Entre em Contato

A seção **Entre em Contato** possui um formulário dentro de um `<fieldset>` com o título **Dados do Contato**.

O formulário contém os seguintes campos:

* Nome;
* E-mail;
* Assunto;
* Mensagem;
* Botão de envio.

Cada campo possui seu respectivo `<label>`, relacionado corretamente ao campo por meio do atributo `for`.

5. Rodapé

O `<footer>` apresenta as informações de contato e os direitos autorais do projeto.

São exibidos:

* Copyright;
* E-mail;
* Telefone.



Estrutura Semântica

O projeto utiliza elementos semânticos do HTML5 para organizar o conteúdo:

```text
<header>
    <nav>
        Menu de navegação
    </nav>
</header>

<main>
    <section>
        Sobre Mim
    </section>

    <section>
        Meus Projetos
    </section>

    <section>
        Entre em Contato
    </section>
</main>

<footer>
    Informações de contato
</footer>
```

Essa organização facilita a leitura do código e melhora a estrutura da página.



Navegação

O menu utiliza links internos através de âncoras HTML:

```html
<a href="#sobre">Sobre</a>
<a href="#projetos">Projetos</a>
<a href="#contato">Contato</a>
```

Cada link direciona o usuário para sua respectiva seção da página.



Imagem de Perfil

A imagem de perfil é adicionada utilizando a tag `<img>`:

```html
<img src="minha-img.png" width="150" height="150" alt="Foto de perfil">
```

O atributo `alt` também foi utilizado para fornecer uma descrição alternativa da imagem.



Formulário

O formulário foi criado utilizando diferentes elementos HTML:

```html
<form>
    <fieldset>
        <legend>Dados do Contato</legend>

        <label for="nome">Nome:</label>
        <input type="text" id="nome">

        <label for="email">E-mail:</label>
        <input type="email" id="email">

        <label for="assunto">Assunto:</label>
        <select id="assunto"></select>

        <label for="mensagem">Mensagem:</label>
        <textarea id="mensagem"></textarea>

        <button type="submit">Enviar</button>
    </fieldset>
</form>
```

Os campos de nome e e-mail possuem validação básica através do atributo `required`.



Como Executar

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto.
3. Localize o arquivo `index.html`.
4. Abra o arquivo em um navegador, como Google Chrome, Microsoft Edge ou Mozilla Firefox.
5. Navegue pelas seções utilizando o menu superior.



Arquivos

```text
📦 portfolio
 ├── 📄 index.html
 ├── 🖼️ minha-img.png
 └── 📄 README.md
```



Conceitos Praticados

Durante o desenvolvimento deste projeto foram praticados conceitos como:

* Estrutura básica do HTML5;
* HTML semântico;
* Links e âncoras;
* Inserção de imagens;
* Listas;
* Tabelas;
* Formulários;
* Campos de entrada;
* `<select>`;
* `<textarea>`;
* `<fieldset>` e `<legend>`;
* Labels associados aos campos;
* Links externos;
* Organização de conteúdo em seções.



Informações Acadêmicas

Aluno: Kayke Willians
Curso: Desenvolvimento / Tecnologia
Projeto: Portfólio / Currículo Web
Ano: 2026



Licença

Este projeto foi desenvolvido para fins **educacionais e acadêmicos**.
