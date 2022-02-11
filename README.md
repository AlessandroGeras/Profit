<h1> Profit</h1>
<h3> Filtragem de dados em Python - Projeto real
  <br />
Início - 10/02/2022 - Conclusão - 11/02/2022 </h3>

<!-- TABLE OF CONTENTS -->
<details>
  <summary name="indice">Índice</summary>
  <ol>   
    <li><a href="#projeto">Sobre o projeto</a></li>
    <li><a href="#detalhes">Detalhes da aplicação</a></li>
    <li><a href="#dia1">Dia 1</a></li>
    <li><a href="#dia2">Dia 2</a></li>
    <li><a href="#dia3">Dia 3</a></li>
    <li><a href="#dia4">Dia 4</a></li>
    <li><a href="#dia5">Dia 5</a></li>
    <li><a href="#dia6">Dia 6</a></li>
    <li><a href="#dia7">Dia 7</a></li>
    <li><a href="#site">Como usar o site</a></li>
    <li><a href="#tecnologias">Dependências e Tecnologias usadas</a></li>
  </ol>
</details>
<h2 name="projeto"> Sobre o projeto  </h2>
Fiz este projeto em 2 dias, sem saber nada de Python. Cliente perguntou se eu tinha condições de aplicar uma solução para uma questão de Profit. Óbvio que eu não ia dizer que não, mesmo não sabendo nada de Python. Assumi a bronca e fomos a luta. Adoro desafios 😈 <br /> A proposta do projeto era que durante o dia um determinado ativo poderia ter variações, e que cada variação teria um ponto máximo, um ponto mínimo e o valor final da hora. E que a solução seria de achar durante o dia, em que momento o ativo rompeu novamente seu ponto máximo e seu ponto mínimo a cada hora para que fosse analisado padrões. O objetivo seria detectar no ano,por exemplo, se um ativo teria um grande porcentagem de quebra de pontos máximos às 10:00 horas da manhã para que fosse criado um robô para efetuar as transações automaticamente pelo cliente. O projeto foi implementado com sucesso 👏 Como resultado foi gerado uma nova tabela em Excel com os filtros aplicados. Cliente não pediu gráficos pois ele mesmo iria criar tabelas dinãmicas.
<br /><br />

Comentários sobre o meu próprio projeto: Ter aprendido javascript me ajudou imensamente neste projeto. Aprendi a automatizar tarefas no Python e mandar relatórios automatizados também por e-mail. Fiquei feliz por esta experiência, sempre que tiver que automatizar algo, irei lhe usar Python. Impressionante como eu ainda não sabia o que era Python e pra que servia. I miss you Python ❤️.
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>
 
<h2 name="detalhes"> Detalhes da aplicação  </h2>
Navbar com 3 botões funcionais, login, cadastrar e logoff. <br />
Forms com 1 formulário com regex, 1 formulário normal e a store que teve que ser integrada aqui para reduzir as chamadas de props.<br />
Bootcamps com imagens e textos. <br />
Advertising com imagem e texto. <br />
Footer com links não funcionais. <br />
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="dia1"> Dia 1</h2>
Criado toda a estrutura do site, responsividade, CSS e animações. Pouco para o primeiro dia? Diz isso pras 600 linhas de CSS que foram criadas. Isso só de CSS puro. Sim, eu amo CSS 😍
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="dia2"> Dia 2</h2>
Dia de aprender regex!!! Eu não sabia o que era regex, pra mim era autenticação de caracteres em formulários. Foram 5 minutos só para descobrir que aquilo se chamava regex 😆
Meio confuso, levei metade do dia pra entender, e a outra metade do dia da implantar e fazer os efeitos visuais no formulário.
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="dia3">Dia 3</h2>
Express instalado e configurado com as rotas, e só. Resto do dia estudando como o banco de dados do projeto final, Sqlite, funcionava e como fazer as queries. Achei difícil e tentei usar o PostgreSQL. Achei que eu estava fugindo do meu desafio e prometi que iria ter sucesso no outro dia com o Sqlite. ☹️
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="di4">Dia 4</h2>
Implantado o Sequelize para integrar o Sqlite. Deu vários problemas nas queries de update que me levaram a querer voltar pra ideia do PostgreSQL. Mais uma vez me xinguei por querer fugir do desafio e fui novamente a luta. Problema que o Sequelize não dava retorno nas promises que tinham múltiplas queries do Sqlite, só no PostgreSQL segundo a documentação oficial. Recomendado fazer uma sequência de promises par resolver o problema. Pesquisei mais um pouco porque não estava afim de fazer as queries, uma a uma, quando alguém disse ter achado um exploit de enviar as queries em Json, em vez de criar as queries em Json diretamente no Sequelize. Não tinha sentido trocar 6 por meia dúvia mas funcionou. Ufa! 🤡
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="dia5">Dia 5</h2>
Configurado o banco de dados finalmente. Feito testes de CRUD ao longo do dia. Estudado mais um pouco sobre banco de dados e trocado os ID´s por UUID e trocado as passwords por hashs de criptografia. Iniciado os estudos sobre tokens.
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="dia6">Dia 6</h2>
Dia totalmente improdutivo. Sucesso em gerar o token mas falha em receber. Tentado vários métodos de comunicação para enviar o token. Falha em todos os métodos. Erros de CORS acontencendo simultaneamente. Erros resolvidos e novos aparecendo. Não sabia o que fazer. Pensei em desistir e entregar o projeto sem o token pois já estava de bom tamanho. Só tinha um problema, eu nunca desisto. 😈
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="dia7">Dia 7</h2>
Reconhecido problema no Express, ele não pega cookie, quem diria. Instalado o modulo CookieParser e tudo funcionou 🏆 Configurado o server em modo REST. Resolvido o problema de CORS que proibia conexão entre o mesmo domínio (localhost de localhost), configurado sistema de cache para responder os pedidos de GET. Configurado a store do site. Desafio completado 👏
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="site">Como usar o site</h2>
Clique no botão superior em Cadastrar, crie um usuário. Clique no botão superior Login e faça login. Você cairá na store e lá só existem 4 produtos. Os testes de banco de dados pode ser feitos comprando até 3 produtos. Você pode fazer logoff e entrar de novo e os produtos comprados estarão indisponíveis. Você pode comprar até 3 produtos e tentar acionar a opção de comprar novamente sem fazer logoff. Novamente os produtos comprados estarão indisponíveis. Você pode acessar o endereço localhost:5000/users para ver a base de dados. Não fiz GET pro usuário ver alguma coisa porque simplesmente ele já vê o que ele tem quando entra na store. E não fiz o delete porque achei que não tinha contexto neste projeto e não fez falta no aprendizado até porque era o comando mais fácil do banco de dados. Quando você comprar os 4 produtos você receberá um link no console do DevTools do navegador para acessar a página de segurança dos usuários. É o mesmo conteúdo do /users só que ele tem controle via token. Depois de 1 minuto você irá perder acesso ao link e terá que logar de novo para ganhar outro link. Fiz isso para testar a segurança do token pois se eu tivesse feito no login automático ninguém ia saber que ele existe pois ele seria autenticado automaticamente. E no link, já era, depois de 1 minuto, adeus acesso.
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="tecnologias">Dependências e Tecnologias usadas</h2>
<strong>Dependências Front-End:</strong><br />
Styled-Componentes<br />
WebFont<br /><br />

<strong>Dependências Back-End:</strong><br />
Express<br />
CORS<br />
Sequelize<br />
CookieParser<br />
statusCodes<br />
jsonwebtoken<br />
bcrypt<br /><br />

<h3>Tecnologias usadas:</h3>
#html
<br />
#css
<br />
#js
<br />
#React
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

