# Clusterização de uma base de dados do jogo Dota 2.

### Caminho do projeto: clustering_validation/src/portfolio_projects/dota2_clustering.ipynb

O trabalho consiste em uma clusterização de dados de partidas do jogo Dota 2 (um dos jogos mais jogados no mundo) realizadas por competidores em ligas profissionais no ano de 2022. É um jogo que eu gosto, mas particularmente tenho dificuldades e, para entender melhor as "features" que levam à vitória e quais personagens estão sendo mais utilizados nos campeonatos e o porquê, o presente trabalho foi realizado.

A base de dados foi coletada em um site que disponibiliza dados estatísticos das partidas profissionais e também de todos os jogadores, mas, para baixar os meus dados, precisaria de pagar um certo valor em uma key para usar uma API, então foram obtidos dados de 20.000 jogos realizados por profissionais no ano de 2022 (que são dados gratuitos). As informações sobre a base de dados são:

1. hero_id: o jogo possui mais de 120 personagens ditos heróis, cada um com habilidades específicas e muitas vezes desbalanceados;
2. kills: número de mortes que o jogador provoca;
3. deaths: número de mortes sofridas;
4. assists: número de assistências (participações em mortes);
5. gold: quantidade de ouro obtida;
6. last_hits: quantidade de finalizações a unidades que não são jogadores. A cada finalização ganha-se ouro;
7. denies: quantidade de finalizações das suas próprias unidades para que o jogador do time adversário não ganhe ouro e experiência;
8. gold_per_min: quantidade de ouro por minuto, geralmente reflete uma boa partida em termos de recursos;
9. xp_per_min: quantidade de experiência por minuto, geralmente reflete uma boa partida em termos de nível de personagem;
10. gold_spent: ouro gasto;
11. hero_damage: dano total em uma partida provocado a outros jogadores;
12. tower_damage: dano total em uma partida provocado a estruturas;
13. hero_healing: cura total proporcionada por heróis que tem esse tipo de habilidade;
14. level: nível do personagem;
15. firstblood_claimed: se o personagem provocou a primeira morte do jogo ou não. Ela é mais valorizada do que as convencionais;
16. roshans_killed: roshan é um personagem que quando derrotado dá uma vantagem grande para o time que o derrotou;
