# Gameplay

## Loop principal

A experiência de jogo segue este ciclo:

**Receber entrega → entrar no local → superar obstáculos → localizar/resolver o problema → encontrar Etvaldo → tentar concluir a entrega → voltar ao caminhão**

## Movimentação

Shopi deve possuir controles simples e responsivos:

- esquerda/direita: movimentação horizontal;
- cima/baixo: subir e descer escadas;
- espaço/toque equivalente: salto.

A versão atual também contempla controles por toque para celular.

## Plataforma vertical

A primeira fase utiliza progressão vertical baseada em plataformas e escadas. O jogador deve observar padrões de obstáculos e escolher o momento adequado para avançar.

## Obstáculos

Os obstáculos são gerados ou lançados pelo cliente problemático. A primeira fase utiliza objetos com diferentes comportamentos, como queda, rolagem e quique.

A dificuldade deve aumentar progressivamente à medida que Shopi se aproxima do cliente.

## Vidas e checkpoints

O modelo planejado inclui vidas limitadas e checkpoint intermediário para reduzir repetição excessiva.

Ao sofrer dano, o jogador deve receber feedback visual claro e retornar a uma posição segura.

## Pontuação

A pontuação pode considerar:

- progresso na fase;
- desvios de obstáculos;
- tempo de conclusão;
- conclusão da entrega;
- resgate de Etvaldo.

## Ranking

O projeto já possui um sistema de ranking de líderes. O ranking deve estimular replay e comparação de desempenho sem ser necessário para concluir uma fase.

## Mobile

A experiência deve permanecer funcional em telas menores e utilizar controles por toque adequados para movimentação e salto.

## Filosofia de design

O jogo não deve depender de combate tradicional. O conflito nasce das dificuldades absurdas de realizar uma entrega.

A sensação desejada é:

> "Eu só queria fazer meu trabalho."

O jogador deve reconhecer rapidamente o objetivo da fase e aprender os padrões dos obstáculos por tentativa, observação e prática.
