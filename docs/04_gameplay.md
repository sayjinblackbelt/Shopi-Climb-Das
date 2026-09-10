# Gameplay

## Loop principal

A experiência de jogo segue este ciclo:

**Receber entrega → entrar no local → superar obstáculos → localizar/resolver o problema → encontrar o cliente/Etvaldo → tentar concluir a entrega → voltar ao caminhão**

## Movimentação

Shopi possui controles simples:

- esquerda/direita: movimentação horizontal;
- cima/baixo: subir e descer escadas;
- espaço/toque equivalente: salto.

A experiência funciona em desktop e dispositivos móveis.

## Plataforma vertical

A primeira fase utiliza progressão vertical baseada em plataformas e escadas. A segunda fase mantém a exploração entre áreas da casa e introduz perseguição do cliente.

## Dificuldade

O jogo possui três níveis globais:

| Nível | Multiplicador | Característica |
|---|---:|---|
| Entrega Tranquila | ×1 | experiência introdutória, com menor pressão |
| Entrega Complicada | ×1,5 | obstáculos moderados |
| Entrega Impossível | ×2 | maior frequência, velocidade e desafio |

Na Fase 1, **Entrega Tranquila não possui objetos caindo de cima**. Nos níveis superiores, os objetos lançados por Tabacudo fazem parte do desafio.

## Fase 2 e perseguição

A Fase 2 — A Casa introduz Cleovasdo, que tenta devolver a encomenda e foge de Shopi. O jogador precisa persegui-lo por diferentes ambientes domésticos.

A perseguição utiliza comportamento simples e controlado, priorizando diversão e compreensão do objetivo em vez de uma IA complexa.

## Obstáculos

A Fase 1 utiliza obstáculos com diferentes comportamentos, como queda, rolagem e quique.

A Fase 2 utiliza obstáculos coerentes com uma casa, como bolas, brinquedos, vasos, caixas, cadeiras, móveis, ferramentas e aspirador.

## Itens colecionáveis

Uma nova mecânica está planejada: **2 itens por fase**.

O jogador poderá revelar itens escondidos ao pular e atingir a parte inferior de determinados elementos do cenário. Depois de revelados, os itens podem ser coletados.

Os itens são objetivos secundários: não são necessários para concluir a fase.

A coleta deverá:

- atualizar um contador, como `ITENS: 1/2`;
- conceder bônus de pontuação;
- respeitar o multiplicador de dificuldade;
- funcionar em teclado e touch.

Os seis pneus do caminhão formarão uma coleção especial ao longo da campanha.

## Vidas e checkpoints

O jogo utiliza vidas limitadas e checkpoint para reduzir repetição excessiva. Ao sofrer dano, o jogador recebe feedback e retorna a uma posição segura.

## Pontuação

A pontuação pode considerar:

- progresso na fase;
- conclusão da entrega;
- resgate de Etvaldo;
- itens coletados;
- demais ações previstas pelo sistema atual.

Os multiplicadores de dificuldade devem ser preservados.

## Ranking

O projeto possui ranking de líderes para comparação de desempenho. A estrutura poderá evoluir futuramente para rankings por fase e recordes pessoais.

## Mobile

A experiência permanece funcional em telas menores e utiliza controles por toque para movimentação e salto.

## Filosofia de design

O jogo não depende de combate tradicional. O conflito nasce das dificuldades absurdas de realizar uma entrega.

A sensação desejada é:

> "Eu só queria fazer meu trabalho."

O jogo deve recompensar tentativa, observação, prática e exploração, mantendo objetivos claros e mecânicas diferentes para cada cliente.