# Efeito-da-Legalizacao-da-Maconha-na-Taxa-de-Criminalidade-ao-Longo-do-Tempo
Que tal substituir "achismos" por opinião baseada em dados?

### Definição do Problema

Em 2016, os eleitores da Califórnia nos EUA aprovaram a Proposição 64, que legalizou o uso recreativo da maconha no estado. Neste link você encontra os detalhes sobre a aprovação da Proposição 64:

<a href="https://ballotpedia.org/California_Proposition_64,_Marijuana_Legalization_(2016)">California Proposition 64, Marijuana Legalization (2016)</a>

Os opositores à medida apresentaram cinco principais objeções à mudança no Guia Oficial de Informações do Eleitor do estado. Eles argumentaram que a legalização:

- (1) Dobraria o número de mortes nas rodovias.
- (2) Permitiria o cultivo de maconha perto de escolas e parques.
- (3) Aumentaria a atividade do mercado negro e do cartel.
- (4) Prejudicaria as comunidades pobres com problemas de dependência por meio do influxo de novos pontos de vendas de maconha.
- (5) Aumentaria a criminalidade ao longo do tempo, especialmente nas áreas próximas aos pontos de venda de maconha legalizada (cada ponto de venda de maconha legalizada é chamado de marijuana dispensary). 

Trabalho: 

Realizar uma análise de dados com base em séries temporais e análises geoespaciais, além de outras técnicas exploratórias mais gerais, para examinar se essas previsões se tornaram realidade em Los Angeles desde que a legalização entrou em vigor. Nosso foco principal será nos dados disponíveis sobre detenções por crimes relacionados à maconha e na taxa geral de crimes nas proximidades de dispensários. Focaremos principalmente nos itens 2, 4 e 5 acima.

Os dados usados neste projeto estão disponíveis publicamente e são oferecidos pelo portal de dados abertos do governo de Los Angeles.

Você é favor ou contra à legalização da Maconha? Acompanhe o projeto passo a passo, leia atentamente cada comentário e então emita sua opinião com base em dados.

### Divisão do Projeto Final

Iremos trabalhar com dados de 4 fontes diferentes. Teremos que extrair, limpar, organizar, relacionar e explorar os dados e definir um Pipeline de Dados. Aplicaremos Modelagem Estatística, iremos validar suposições e hipóteses e identificar as variáveis relevantes para nossa análise durante a Modelagem Preditiva. Por fim, vamos construir um modelo de Análise de Séries Temporais, interpretar as estatísticas e emitir nossa conclusão através de um Sumário Executivo.

Ao final do projeto, estaremos aptos a responder à pergunta:

Qual o Efeito da Legalização da Maconha na Taxa de Criminalidade ao Longo do Tempo?

Projeto será dividido em 3 Partes principais:

- Parte 1 - Definição do Problema, Coleta, Pipeline e Limpeza de Dados.

- Parte 2 - Análise Exploratória com Geolocalização e Modelagem Estatística.

- Parte 3 - Modelagem Preditiva, Análise de Séries Temporais, Conclusões Finais e Apresentação do Sumário Executivo do Projeto. 

Trabalharemos com cerca de 4 milhões de registros de dados reais disponíveis publicamente em diferentes fontes.

### Fontes de Dados

Os dados necessários para nosso trabalho não podem ser encontrados em uma única fonte. Precisamos dos seguintes dados:

- 1- Dados sobre lojas que vendem maconha legalizada em Los Angeles. Esses dados serão coletados do Yelp via API.

- 2- Dados sobre os crimes em Los Angeles. O portal <a href="https://data.lacity.org/">Los Angeles Open Data</a> fornece esses dados com fácil acesso para download no formato csv ou via API. (Arquivo já disponível).

- 3- Dados sobre prisões em Los Angeles. O mesmo portal no item 2 fornece os dados e faremos o download. (Arquivo já disponível).

- 4- Dados demográficos de escolas em Los Angeles. Esses dados estão disponíveis publicamente no <a href="http://www.lausd.k12.ca.us/lausd/offices/bulletins/">School Information Branch</a>, de onde faremos o download.(Arquivo já disponível).

Para cada conjunto de dados, teremos que limpar os dados e deixá-los organizados para as Partes 2 e 3 do nosso projeto.
