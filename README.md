# Projeto_Part1_Atividade_BackEnd2
<body>
    <h1>Biblioteca</h1>
    <p>Este projeto é uma aplicação para gerenciar livros e autores em uma biblioteca. Ele permite cadastrar, listar, e gerenciar a relação entre livros e autores.</p>

<h2>Funcionalidades</h2>
<li><strong>Livro:</strong></li>
<ul>
<li>Criar novos livros.</li>
<li>Visualizar detalhes dos livros.</li>
<li>Atualizar informações dos livros.</li>
<li>Deletar livros.</li>
</ul>
<li><strong>Autor:</strong></li>
<ul>
<li>Criar novos autores.</li>
<li>Visualizar detalhes dos autores.</li>
<li>Atualizar informações dos autores.</li>
<li>Deletar autores.</li>
</ul>

<h2>Estrutura das Entidades</h2>
    <h3>Livro</h3>
    <p>O modelo de Livro contém os seguintes campos:</p>
    <ul>
        <li><strong>id:</strong> Identificador único do livro.</li>
        <li><strong>titulo:</strong> Título do livro.</li>
        <li><strong>descricao:</strong> Descrição detalhada do livro.</li>
        <li><strong>qtdePaginas:</strong> Quantidade de páginas do livro.</li>
        <li><strong>nota:</strong> Nota atribuída ao livro.</li>
    </ul>

<h3>Autor</h3>
    <p>O modelo de Autor contém os seguintes campos:</p>
    <ul>
        <li><strong>id:</strong> Identificador único do autor.</li>
        <li><strong>nome:</strong> Nome completo do autor.</li>
        <li><strong>email:</strong> E-mail de contato do autor.</li>
    </ul>

<h3>Relação entre Autor e Livro</h3>
    <p>Um autor pode estar associado a um ou mais livros, e cada livro deve ter pelo menos um autor. Essa relação é do tipo "um para muitos".</p>


<h2>Pré-requisitos</h2>
    <ul>
        <li>Java JDK 8 ou superior</li>
        <li>Maven</li>
        <li>Banco de dados MongoDB</li>
    </ul>
</body>