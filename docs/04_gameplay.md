# Gameplay

## Loop principal

A experiência de jogo segue este ciclo:

**Receber entrega → entrar no local → superar obstáculos → localizar/resolver o problema → encontrar o cliente → concluir a entrega → avançar na campanha**

## Movimentação

Shopi possui controles simples:

- esquerda/direita: movimentação horizontal;
- cima/baixo: subir e descer escadas;
- espaço/toque equivalente: salto.

A experiência funciona em desktop e dispositivos móveis.

## Campanha

O jogo atual possui **6 fases jogáveis**, todas testadas até o final pelo autor. Cada fase apresenta um cenário, cliente e situação de entrega diferentes.

A campanha atual é:

1. O Prédio — Tabacudo
2. A Casa — Cleovasdo
3. O Condomínio — Osvaldêncio
4. O Centro Comercial — Jocelvânio
5. O Shopping — Ubiratânio
6. O Centro de Distribuição — Edivaldir

## Plataforma vertical e exploração

A primeira fase utiliza progressão vertical baseada em plataformas e escadas. As fases seguintes ampliam a exploração para ambientes e situações diferentes, mantendo o foco em movimentação, observação e resolução do problema de entrega.

## Dificuldade

O jogo possui três níveis globais:

| Nível | Multiplicador | Característica |
|---|---:|---|
| Entrega Tranquila | ×1 | menor pressão e maior acessibilidade |
| Entrega Complicada | ×1,5 | desafio intermediário |
| Entrega Impossível | ×2 | maior frequência, velocidade e dificuldade |

Na Fase 1, **Entrega Tranquila não possui objetos caindo de cima**. Nos níveis superiores, os objetos lançados por Tabacudo fazem parte do desafio.

A dificuldade também pode alterar comportamento, velocidade, frequência e tolerância de obstáculos ou clientes, preservando a identidade e a jogabilidade de cada fase.

## Fases específicas

### Fase 1 — O Prédio

Progressão vertical com plataformas, escadas e obstáculos associados a Tabacudo. O jogador sobe, supera os desafios, encontra Etvaldo e chega ao cliente.

### Fase 2 — A Casa

Cleovasdo tenta devolver a encomenda e foge pela casa. A fase introduz perseguição em ambientes domésticos.

### Fase 3 — O Condomínio

Osvaldêncio cria bloqueios e restrições de circulação. O jogador precisa encontrar rotas alternativas para avançar.

### Fase 4 — O Centro Comercial

Jocelvânio nunca está exatamente onde deveria estar. A fase explora localização e perseguição.

### Fase 5 — O Shopping

Ubiratânio fez um pedido absurdo. A situação de entrega gera o desafio específico da fase.

### Fase 6 — O Centro de Distribuição

Edivaldir quer trocar a encomenda. O jogador percorre um ambiente de logística e resolve a situação da troca.

## Obstáculos

Os obstáculos variam conforme o ambiente e a situação da fase. Na Fase 1 podem existir queda, rolagem e quique; na Fase 2 predominam elementos domésticos; nas fases seguintes os obstáculos devem refletir o cenário e a mecânica correspondente.

## Vidas e checkpoints

O jogo utiliza vidas limitadas e checkpoint para reduzir repetição excessiva. Ao sofrer dano, o jogador recebe feedback e retorna a uma posição segura.

## Pontuação

A pontuação recompensa o desempenho durante a fase. O sistema pode considerar progresso, conclusão da entrega, ações especiais e outros eventos de gameplay já implementados.

Os multiplicadores de dificuldade devem ser preservados quando aplicáveis.

## Placar por fase e placar geral

A próxima evolução do sistema de competição organiza a pontuação em dois níveis:

### Placar por fase

Cada uma das seis fases pode possuir um melhor resultado registrado para o jogador, associado à pontuação e à dificuldade utilizada.

Quando o novo resultado for superior ao melhor resultado anterior naquela fase, ele substitui o recorde. Um resultado inferior não deve apagar o melhor resultado.

### Placar geral

O placar geral é calculado a partir da **soma das melhores pontuações do jogador nas seis fases**.

A proposta é permitir:

- acompanhar desempenho individual por fase;
- comparar jogadores em cada etapa da campanha;
- comparar o desempenho acumulado de toda a campanha;
- identificar novos recordes.

## Itens colecionáveis — planejado

Permanece planejada uma mecânica com **2 itens colecionáveis por fase**, revelados pela exploração e pelo salto. Os itens devem conceder bônus de pontuação e funcionar em desktop e mobile.

Essa mecânica não deve ser tratada como implementada até que seja validada em teste.

## Mobile

A experiência permanece funcional em telas menores e utiliza controles por toque para movimentação e salto.

## Filosofia de design

O jogo não depende de combate tradicional. O conflito nasce das dificuldades absurdas de realizar uma entrega.

A sensação desejada é:

> "Eu só queria fazer meu trabalho."

O jogo deve recompensar tentativa, observação, prática e exploração, mantendo objetivos claros e mecânicas diferentes para cada cliente.