# DEVLOG

## 07/10/2026 — Aula 08

- Montei a vila de 40 × 24 peças em duas camadas (`chao` e `objetos`) com o mesmo `tiles/vila.tres`, e o Jogador em quatro direções, com a câmera em zoom 3 e limites de 640 × 384.
- Transformei as casas (4 × 3) e as árvores altas (1 × 2) em peças grandes no TileSet, apagando antes as peças pequenas que elas cobriam.
- Travou: errei a conta da casa, porque achei que ela começava no canto da célula clicada. Na verdade ela é desenhada centrada na célula, e a casa clicada em (32, 16) vai das linhas 15 a 18.
- Resolvi passando a clicar no meio da casa e conferindo com as formas de colisão visíveis. O personagem para no muro, nas casas, nas árvores e na cerca.
