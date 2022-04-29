# Projeto de Estudo de Machine Learning

Esse projeto foi desenvolvido seguindo as orientações do Téo Calvo, Head of Data na Gamers Club, a partir das lives realizadas no canal [Téo Me Why](https://www.twitch.tv/teomewhy).

Nele, o nosso objetivo é resolver um problema de negócio utilizando Data Science e os dados disponíveis da Gamers Club.

# O problema de negócio

A Gamers Club é uma plataforma de eSports.

O problema de negócio escolhido foi a previsão de assinatura dos usuários na Gamers Club.

## Sobre os dados

Os dados utilizados estão disponíveis na [página oficial do Kaggle](https://www.kaggle.com/gamersclub/brazilian-csgo-plataform-dataset-by-gamers-club)

O banco de dados disponibilizado possui 4 tabelas:

- tb_players: concentra as informações dos jogadores;
- tb_lobby_stats_player: apresenta as estatísticas dos jogadores nas partidas;
- tb_players_medalha: possui as informações sobre as medalhas de cada jogador;
- tb_medalha: possui as informações dos tipos de medalha.

# Conhecimentos técnicos

- SQL
- Python

Bibliotecas Python

- SQLalchemy
- Pandas
- Numpy
- Scikit-learn
- Feature-engine
- XGBoost
- Scikit-plot
- Yellowbrick

# Etapas do Projeto

## Criação do book de variáveis

Para a criação do book de variáveis, foram necessárias as seguintes etapas:
-Sumarizar as estatísticas dos jogadores, selecionando apenas os últimos 30 dias de estatísticas disponíveis na tabela tb_lobby_stats_player.

-
