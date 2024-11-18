# nba_players_EDA

<img src="https://images.pexels.com/photos/41433/pexels-photo-41433.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1">

## Projeto da disciplina de Estatistica I - Ada Tech - Santander Coders_2024

Imagine poder mergulhar na rica história da NBA, analisando a evolução dos jogadores ao longo dos anos, desde suas performances em quadra até suas jornadas antes de chegarem à liga. O dataset que estamos explorando oferece um olhar detalhado sobre os principais aspectos dos atletas, como altura, peso, país de origem e o impacto que cada um teve nas temporadas que disputaram.

Além dos números, como pontos, rebotes e assistências, podemos ver como os jogadores se desenvolveram desde o draft e como as diferentes características influenciam seus desempenhos. Esta análise vai além das estatísticas, revelando tendências, padrões e como o basquete se transforma com o passar do tempo.

## Contexto do projeto

<img src="https://images.pexels.com/photos/16955708/pexels-photo-16955708/free-photo-of-linhas-filas-bola-esfera.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" min-width="400px" max-width="400px" width="400px" align="right" alt="Bola">

Como analista de dados de um time de basquete, nosso grupo foi incumbida de identificar um jogador promissor que possa ajudar a equipe a se destacar na próxima temporada. Embora ainda não saibamos para qual posição, focaremos em variáveis chave que melhor reflitam o desempenho geral de um jogador e que possam ser usadas independentemente da posição em quadra.

Este projeto tem como objetivo oferecer uma visão abrangente do desempenho dos jogadores ao longo das temporadas, identificando as melhores variáveis para orientar a escolha de futuros atletas.

## Sobre o Dataset

| Colunas | Tipo | Descrição |
|----------|----------|----------|
| nome_do_jogador | Qualitativa nominal | Nome do jogador |
| team_abbreviation | Qualitativa nominal | Nome abreviado do time em que o jogador jogou (no final da temporada) |
| age | Quantitativa discreta | Idade do jogador |
| player_height | Quantitativa contínua | Altura do jogador (em centímetros) |
| player_weight | Quantitativa contínua | Peso do jogador (em quilogramas) |
| college | Qualitativa nominal | Nome da faculdade que o jogador frequentou |
| country | Qualitativa nominal | Nome do país em que o jogador nasceu (não necessariamente a nacionalidade) |
| draft_year | Quantitativa discreta | O ano em que o jogador foi convocado |
| draft_round | Quantitativa discreta | A rodada de draft em que o jogador foi escolhido |
| draft_number | Quantitativa discreta | O número em que o jogador foi escolhido em sua rodada de recrutamento |    
| gp (games played) | Quantitativa discreta | Jogos disputados ao longo da temporada |             
| pts (points) | Quantitativa contínua | Número médio de pontos marcados |      
| reb (rebounds) | Quantitativa contínua  | Número médio de rebotes obtidos |            
| ast (assists) | Quantitativa contínua | Número médio de assistências distribuídas |
| net_rating | Quantitativa contínua | Diferencial de pontos da equipe por 100 posses enquanto o jogador está em quadra |           
| oreb_pct (offensive rebound percentage) | Quantitativa contínua | Porcentagem de rebotes ofensivos disponíveis que o jogador pegou enquanto estava em quadra |          
| dreb_pct (defensive rebound percentage) | Quantitativa contínua | Porcentagem de rebotes defensivos disponíveis que o jogador pegou enquanto estava em quadra |       
| usg_pct (usage percentage) | Quantitativa contínua | Porcentagem de jogadas de equipe usadas pelo jogador enquanto ele estava em quadra ((FGA + Possession Ending FTA + TO) / POSS) |   
| ts_pct (true shot percentage) | Quantitativa contínua | Medida da eficiência de arremessos do jogador que leva em consideração lances livres, arremessos de 2 e 3 pontos (PTS / (2*(FGA + 0.44 * FTA))) |   
| ast_pct (assist percentage) | Quantitativa contínua | Porcentagem de assistências pelo jogador enquanto ele estava em quadra |    
| season | Qualitativa ordinal | Temporada da NBA |

## Link do dataset
O dataset está disponível em: <a href="https://www.kaggle.com/datasets/justinas/nba-players-data" target="_blank">NBA Players</a>
