<sub>**Datas:** pasta 23/12/2022 · código 19/12/2022 (`minesweeper.Rmd`)</sub>

# Campo minado + ML

Simula tabuleiros **Campo Minado** e treina **rede neural / árvore** para prever células seguras a partir de tabuleiro parcial.

## O que o código faz

`minesweeper.Rmd` em duas partes:

1. **Jogo 16×30** — gera minas, vizinhança, jogada interativa.
2. **10 000 tabuleiros 5×5** — features do que já foi revelado → `neuralnet` / `rpart`.

## Dados

Tudo simulado; sem arquivos de entrada.

## Como rodar

Knit no RStudio (a parte com 10k puzzles é **lenta**).