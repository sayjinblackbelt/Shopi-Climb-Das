# Gameplay

## Loop principal

A experiência segue o ciclo:

**Receber entrega → entrar no local → superar obstáculos → explorar/usar mecanismos → localizar ou resolver o problema → encontrar o cliente → concluir a entrega → avançar na campanha**

## Movimentação

- esquerda/direita: movimentação horizontal;
- cima/baixo: subir e descer escadas;
- espaço/toque equivalente: salto.

A experiência funciona em desktop e dispositivos móveis.

## Campanha

A campanha foi ampliada para **16 fases**. As fases 1–6 formam a campanha original; as fases 7–15 ampliam ambientes e mecânicas; a Fase 16 encerra o Capítulo 1 com o boss Gerentão.

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

A nova camada audiovisual inclui efeitos sonoros para ações importantes, como:

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

### Fase 16 — A Última Entrega

O Gerentão é o boss final do Capítulo 1. O desafio é dividido em três etapas: caminho com obstáculos, burocracia com mudanças sinalizadas e uso da cabeçada para ativar mecanismos.

O confronto é não violento. O objetivo é realizar a entrega.

Ao concluir, aparece **CAPÍTULO 1 CONCLUÍDO!**, com resultados da campanha e teaser de possível continuação.

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

A campanha deve recompensar tentativa, observação, prática e exploração, mantendo objetivos claros e mecânicas diferentes para cada cliente.