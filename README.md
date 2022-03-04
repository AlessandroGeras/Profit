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
    <li><a href="#tecnologias">Tecnologias usadas</a></li>
  </ol>
</details>
<h2 name="projeto"> Sobre o projeto  </h2>
Fiz este projeto em 2 dias, sem saber nada de Python. Cliente perguntou se eu tinha condições de aplicar uma solução para uma questão de Profit. Óbvio que eu não ia dizer que não, mesmo não sabendo nada de Python. Assumi a bronca e fomos a luta. Adoro desafios 😈 <br /> A proposta do projeto era que durante o dia, um determinado ativo poderia ter variações, e que cada variação teria um ponto máximo, um ponto mínimo e o valor final da hora. E que a solução seria de achar durante o dia, em que momento o ativo rompeu novamente seu ponto máximo e seu ponto mínimo a cada hora para que fosse analisado padrões. O objetivo seria detectar no ano, por exemplo, se um ativo teria um grande porcentagem de quebra de pontos máximos às 10:00 horas da manhã para que fosse criado um robô para efetuar as transações automaticamente pelo cliente naquele horário. Mas isso como eu disse, foi apenas um exemplo do que ele realmente queria. O projeto foi implementado com sucesso 👏 <br /> <br />Como resultado foi gerado uma nova tabela em Excel com os filtros aplicados. Cliente não pediu gráficos pois ele mesmo iria criar tabelas dinãmicas.
<br /><br />

Comentários sobre o meu próprio projeto: Ter aprendido javascript me ajudou imensamente neste projeto. Aprendi a automatizar tarefas no Python e mandar relatórios automatizados também por e-mail. Fiquei feliz por esta experiência, sempre que tiver que automatizar algo, irei lhe usar Python. Impressionante como eu ainda não sabia o que era Python e pra que servia. I miss you Python ❤️.
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>
 
<h2 name="detalhes"> Detalhes da aplicação  </h2>
A tabela original se chama WinFut e sua exportação ficou em apenas 5 colunas. Para o resultado final só precisei de uma coluna e as outras 4 podiam ser descartadas mas resolvi deixar que elas fossem visualizadas na exportação final, para ajudar o acompanhamento da lógica. Realmente, deixando elas fica muito mais fácil dar o OK no teste. <br /><br />

Candle - É uma faixa de horário. Ex: Candle das 10 vai das 10:00 até 10:59. <br />

Coluna Max e Coluna Min - Recebem o valor Máximo e Mínimo da primeira linha e vão se atualizando sempre que encontrarem um valor maior ou menor que o atual. Sempre são resetadas nas linhas que começam com hora "09:00:00" e pegam seus novos valores nesta mesma linha.

Candle_Máximo e Candle_Mínimo - São mostradas só nas linhas com hora de início das candles ("10:00:00" até "18:00:00"),  caso tenham rompido o valor máximo e/ou valor mínimo durante o minuto 0 até o minuto 55 da sua hora ("18:00:00 até o minuto 20). Então se uma candle não romper nenhum dos dois sentidos em sua hora, nada será mostrado para deixar o relatório mais limpo.

Candle_Análise - É o que o cliente quer, analisando qual rompimento aconteceu primeiro e marcando a hora do rompimento. Funciona exatamente como o Candle_Máximo e o Candle_Mínimo.


Finalizando e resumindo, o ponto chave de consulta é nos horários ("10:00:00" até "18:00:00"), caso tenham algo. Tudo começa na primeira linha independente da hora que ela começar e tudo será resetado na hora ("09:00:00").

Off Topic - Curti o Python pela rapidez de processamento. Ele até mostra automaticamente o tempo que leva para fazer a tarefa inteira. Levou 11 segundo pra fazer a importação do excel para dentro do Python, mexer em 10330 linhas e exportar. 
<p align="right">(<a href="#indice">voltar ao indice</a>)</p>

<h2 name="tecnologias">Tecnologias usadas</h2>
#Python
<p align="right">(<a href="#indice">voltar ao indice</a>)</p> 
