# Prompt 09 — Capítulo 1: 16 fases, áudio e novas mecânicas

## Objetivo

Evoluir o jogo existente **Shopi — Entregas Impossíveis** sem reconstruí-lo do zero, preservando as seis fases, controles, física, vidas, checkpoints, pontuação, ranking, dificuldades e suporte desktop/mobile já existentes.

A atualização amplia a campanha de **6 para 16 fases** e adiciona uma camada audiovisual e mecânica mais rica.

## Principais alterações solicitadas

### 1. Expansão da campanha

Adicionar as fases 7 a 16:

| Fase | Local | Cliente | Mecânica/tema |
|---|---|---|---|
| 7 | O Bairro | Valdemarildo | Encontrar o endereço correto |
| 8 | O Prédio Comercial | Claudecirvaldo | Burocracia e liberação de acessos |
| 9 | A Central de Entregas | Geraldânio | Caos logístico e identificação de encomenda |
| 10 | O Estacionamento | Valdovino | Orientação espacial |
| 11 | O Hospital | Edivanildo | Localização de setor e circulação |
| 12 | A Escola | Professor Valdécio | Percurso e múltiplas rotas |
| 13 | O Mercado | Osvaldirson | Navegação em ambiente congestionado |
| 14 | A Obra | Jocelmar | Plataformas e timing |
| 15 | O Shopping | Ubiraldo | Exploração e combinação de mecânicas |
| 16 | A Última Entrega | Gerentão | Boss final do Capítulo 1 |

Cada fase deve possuir identidade visual, cliente, problema e mecânica próprios, evitando apenas aumentar a quantidade ou velocidade dos obstáculos.

## 2. Nova mecânica — Cabeçada

Shopi pode atingir determinados blocos interativos com a cabeça ao pular e tocar a parte inferior deles.

Os blocos interativos devem ser visualmente distinguíveis e não devem transformar todos os blocos do cenário em elementos interativos.

Ao serem atingidos:

- executar animação de impacto;
- fazer o bloco reagir fisicamente;
- reproduzir efeito sonoro;
- emitir feedback visual discreto;
- executar uma função específica.

Possíveis funções:

- revelar pontos;
- revelar itens ou coletáveis;
- revelar pistas;
- ativar mecanismos;
- abrir caminhos;
- mover plataformas;
- alterar esteiras;
- liberar acessos;
- produzir reações cômicas.

A mecânica deve funcionar em desktop e mobile através do salto normal, sem exigir um botão adicional.

A colisão deve ser justa, com hitbox adequada e proteção contra ativações repetidas involuntárias.

A cabeçada deve ser introduzida progressivamente: descoberta nas fases iniciais da nova campanha, uso combinado nas fases intermediárias e papel relevante no desafio final.

## 3. Sistema de áudio

Adicionar identidade sonora original ao jogo.

Efeitos prioritários:

- pulo;
- aterrissagem;
- escadas;
- coleta;
- cabeçada;
- ativação de mecanismos;
- checkpoint;
- dano;
- perda de vida;
- Game Over;
- conclusão de fase;
- entrada/ação de clientes;
- ações especiais dos bosses;
- derrota/conclusão do boss;
- conclusão do capítulo.

Adicionar música ambiente original em loop, com variações apropriadas para fases normais, situações especiais e boss final, sem copiar músicas ou efeitos de jogos existentes.

Caso exista limitação técnica para música, priorizar efeitos sonoros essenciais.

Permitir controle separado de música e efeitos sonoros.

## 4. Feedback visual

Adicionar, sem prejudicar a legibilidade:

- pequenas partículas;
- animações de impacto;
- reação dos blocos;
- feedback de checkpoint;
- feedback de dano;
- feedback de vitória;
- transições suaves;
- elementos comemorativos no final do capítulo.

## 5. Fase 16 — Boss final

O Gerentão é o boss final do Capítulo 1 e representa a burocracia absurda das entregas.

O desafio possui três etapas:

1. caminho com obstáculos e plataformas;
2. burocracia com regras e rotas que mudam de forma visível e previsível;
3. uso da cabeçada para ativar mecanismos e avançar.

O confronto não é combate violento. O objetivo é conseguir realizar a entrega.

Final cômico:

> “Está faltando a assinatura.”

Depois:

# CAPÍTULO 1 CONCLUÍDO!

Mostrar pontuação da fase, pontuação total, dificuldade, fases concluídas e ranking.

Mensagem final:

> “Shopi não queria salvar o mundo. Ele só queria terminar a entrega.”

Teaser:

> “Mas será que essa foi realmente a última entrega?”

Não implementar o Capítulo 2 nesta atualização.

## 6. Preservação

Não remover ou substituir:

- Shopi;
- Etvaldo;
- seis fases existentes;
- controles desktop;
- controles mobile;
- três dificuldades;
- vidas;
- checkpoints;
- pontuação;
- ranking;
- progressão;
- identidade visual e narrativa.

Na Fase 1, Entrega Tranquila continua sem objetos caindo de cima.

## 7. Testes

Testar regressão das seis fases existentes e testar as novas fases 7–16.

Testar:

- campanha completa 1→16;
- três dificuldades;
- desktop;
- mobile;
- cabeçada;
- áudio;
- controles de música/efeitos;
- vidas;
- checkpoints;
- pontuação;
- ranking;
- boss final;
- tela de conclusão.

Uma funcionalidade somente deve ser considerada concluída quando estiver implementada e funcionando no jogo.

## Princípio

**Ideia → Prompt → Base44 → Implementação → Teste → Feedback → Ajuste → GitHub**
