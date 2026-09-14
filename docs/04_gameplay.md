# Gameplay

## Loop principal

A experiência segue o ciclo:

**Receber entrega → entrar no local → superar obstáculos → explorar/usar mecanismos → localizar ou resolver o problema → encontrar o cliente/situação → concluir a entrega → avançar na campanha**

## Movimentação

- esquerda/direita: movimentação horizontal;
- cima/baixo: subir e descer escadas;
- espaço/toque equivalente: salto.

A experiência funciona em desktop e dispositivos móveis.

## Campanha

A campanha atual possui **20 fases implementadas no Capítulo 1**. As fases 1–16 formam o núcleo expandido da campanha; as fases 17–20 ampliam o arco até o encerramento na garagem da Shopi.

1. O Prédio — Tabacudo
2. A Casa — Cleovasdo
3. O Condomínio — Osvaldêncio
4. O Centro Comercial — Jocelvânio
5. O Shopping — Ubiratânio
6. O Centro de Distribuição — Edivaldir
7. O Bairro — Valdemarildo
8. O Prédio Comercial — Claudecirvaldo
9. A Central de Entregas — Geraldânio
10. O Estacionamento — Valdovino
11. O Hospital — Edivanildo
12. A Escola — Professor Valdécio
13. O Mercado — Osvaldirson
14. A Obra — Jocelmar
15. O Shopping — Ubiraldo
16. A Última Entrega — Gerentão
17. A Estação — rotas e plataformas
18. O Hotel — andar e quarto corretos
19. O Parque de Diversões — plataformas móveis e caminhos imprevisíveis
20. A Garagem da Shopi — epílogo do Capítulo 1

## Código da Entrega

A partir da Fase 6, cada entrega pode apresentar um identificador simples para reforçar a sensação de logística real.

Formato de referência:

`SHP-06-EDV-4721`

- `SHP` — Shopi;
- `06` — número da fase;
- `EDV` — identificação curta do cliente;
- `4721` — identificador da encomenda.

O código é principalmente um elemento de ambientação. Pode aparecer no início ou no resultado da entrega e, de forma pontual, em etiquetas, terminais ou outros elementos do cenário.

## Nova mecânica — Cabeçada

Shopi pode atingir com a cabeça determinados blocos interativos ao pular e tocar sua parte inferior.

O bloco deve:

- possuir indicação visual própria;
- reagir com pequena animação/movimento;
- emitir efeito sonoro;
- gerar feedback visual discreto;
- executar uma função específica.

Os efeitos possíveis incluem pontos, revelação de itens ou pistas, abertura de passagem, ativação de mecanismos, movimentação de plataformas, alteração de esteiras e reações cômicas.

A cabeçada funciona pelo salto normal, sem botão adicional, tanto no teclado quanto no touch. A colisão deve ser justa e protegida contra ativações repetidas involuntárias.

A mecânica é introduzida progressivamente e passa a ser utilizada em combinação com outras mecânicas nas fases avançadas.

## Dificuldade

O jogo possui três níveis globais:

| Nível | Multiplicador | Característica |
|---|---:|---|
| Entrega Tranquila | ×1 | menor pressão e maior acessibilidade |
| Entrega Complicada | ×1,5 | desafio intermediário |
| Entrega Impossível | ×2 | maior frequência, velocidade e dificuldade |

Na Fase 1, **Entrega Tranquila não possui objetos caindo de cima**. Nos níveis superiores, os objetos lançados por Tabacudo fazem parte do desafio.

A dificuldade pode alterar comportamento, velocidade, frequência e tolerância dos obstáculos ou clientes, preservando a identidade de cada fase.

## Áudio

A camada audiovisual inclui efeitos sonoros para ações importantes, como:

- pulo e aterrissagem;
- escadas;
- cabeçada;
- coleta;
- mecanismos;
- checkpoint;
- dano e perda de vida;
- conclusão de fase;
- Game Over;
- ações de clientes/bosses;
- conclusão do boss;
- conclusão do capítulo.

A direção sonora deve ser original, curta, cartunesca e coerente com o humor do jogo. Música ambiente pode variar entre fases normais, situações especiais e boss final. Música e efeitos devem possuir controle independente quando disponível.

## Feedback visual

A evolução audiovisual também utiliza, de forma moderada:

- partículas;
- animações de impacto;
- reação dos blocos;
- feedback de checkpoint;
- feedback de dano;
- feedback de vitória;
- transições suaves;
- comemoração no final do capítulo.

O feedback não deve comprometer a legibilidade ou o desempenho.

## Fases específicas

### Fases 1–6

Mantêm a estrutura e a identidade da campanha original, agora integradas à evolução geral do jogo.

### Fases 7–15

Ampliam progressivamente exploração, orientação, mecanismos, plataformas móveis, rotas alternativas, timing e combinação de mecânicas. A cabeçada é utilizada de forma crescente para revelar pistas, ativar mecanismos e abrir caminhos.

### Fase 11 — O Hospital

Durante o teste do ciclo de melhorias de 14/09/2026 foi identificado um ponto em que o salto entre duas partes do cenário não é possível. A correção está registrada como pendência para o próximo ciclo: reduzir o espaço entre as partes ou inserir um ponto de apoio/plataforma intermediária.

A intenção é manter o desafio sem criar um bloqueio impossível.

### Fase 16 — A Última Entrega

O Gerentão é o boss final do núcleo original do Capítulo 1. O desafio é dividido em três etapas: caminho com obstáculos, burocracia com mudanças sinalizadas e uso da cabeçada para ativar mecanismos.

O confronto é não violento. O objetivo é realizar a entrega.

Ao concluir, aparece **CAPÍTULO 1 CONCLUÍDO!**, com resultados da campanha e teaser de possível continuação. As fases 17–20 atualmente registradas ampliam a campanha até seu epílogo.

### Fases 17–20

- **Fase 17 — A Estação:** rotas e plataformas.
- **Fase 18 — O Hotel:** localização do andar/quarto.
- **Fase 19 — O Parque de Diversões:** plataformas móveis e caminhos imprevisíveis.
- **Fase 20 — A Garagem da Shopi:** epílogo e encerramento do Capítulo 1.

## Obstáculos

Os obstáculos continuam variando conforme o ambiente e a situação da fase. A expansão prioriza variedade de situações e mecânicas em vez de apenas aumentar velocidade ou quantidade.

## Vidas e checkpoints

O jogo utiliza vidas limitadas e checkpoints para reduzir repetição excessiva. O jogador recebe feedback ao sofrer dano e retorna a uma posição segura.

## Pontuação e ranking

A pontuação recompensa desempenho durante a fase. O sistema de ranking deve preservar os melhores resultados e acompanhar o desempenho por fase e na campanha geral conforme implementado.

## Mobile

A experiência permanece funcional em telas menores. Movimentação, salto, escadas e cabeçada devem funcionar com os controles touch existentes.

## Filosofia de design

O jogo não depende de combate tradicional. O conflito nasce das dificuldades absurdas de realizar uma entrega.

A sensação desejada é:

> “Eu só queria fazer meu trabalho.”

A campanha deve recompensar tentativa, observação, prática e exploração, mantendo objetivos claros e mecânicas diferentes para cada situação.
