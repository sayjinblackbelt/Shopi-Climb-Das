# Changelog

## [0.2.2] — 14/09/2026 — Campanha atualizada para 20 fases

### Atualizado
- Documentação principal sincronizada com o estado real informado pelo autor: **20 fases implementadas no Capítulo 1**.
- Fases 17–20 registradas na documentação:
  - 17 — A Estação;
  - 18 — O Hotel;
  - 19 — O Parque de Diversões;
  - 20 — A Garagem da Shopi.
- Portal GitHub Pages atualizado de 16 para 20 fases.
- README em português, inglês e espanhol atualizado para 20 fases.
- Foco do próximo ciclo ajustado de expansão da campanha para refinamento, balanceamento e testes das 20 fases existentes.

### Pendência mantida
- **Fase 11 — O Hospital:** existe um ponto em que o salto entre duas partes do cenário não é possível. A correção prevista é reduzir a distância ou inserir um ponto de apoio/plataforma intermediária.

### Verificação do repositório
- Estrutura do repositório revisada.
- Arquivos principais de documentação e portal conferidos.
- Links para o jogo, GitHub Pages e documentação mantidos.
- A página pública do jogo responde atualmente, mas o conector web não permite executar a jogabilidade interativa do Base44; portanto, esta revisão não declara teste manual completo das 20 fases no navegador.

## [0.2.1] — 14/09/2026 — Fluxo, gameplay e identidade das entregas

### Corrigido
- Progressão entre fases e desbloqueio/seleção de fases.
- Continuação da campanha.
- Pausa com continuar, reiniciar, configurações e sair.
- Game Over com recuperação e seleção de fase.
- Fluxo de conclusão de fase e acesso à próxima fase.
- Proteção contra conclusão prematura do Capítulo 1.
- Conclusão correta da campanha na Fase 16.

### Melhorado
- Sensação de movimentação e resposta do salto.
- Leitura de plataformas e caminhos.
- Ritmo e progressão de dificuldade.
- Feedback visual e sonoro.
- Câmera, checkpoints e pontuação.
- Interação dos blocos de cabeçada.
- Identidade dos clientes e relação Shopi/Etvaldo.
- Preservação dos controles mobile já funcionais.

### Adicionado
- **Código da Entrega** a partir da Fase 6, com formato de referência como `SHP-06-EDV-4721`.
- Documentação específica do ciclo de melhorias de 14/09/2026 em português, inglês e espanhol.
- Contador global de visitantes no portal GitHub Pages.

### Pendência identificada no teste
- **Fase 11 — O Hospital:** existe um ponto em que o salto entre duas partes do cenário não é possível. Para o próximo ciclo, reduzir a distância ou inserir um ponto de apoio/plataforma intermediária.

### Validação
O fluxo crítico foi considerado funcional pelo autor. As melhorias gerais foram implementadas e testadas, e a Fase 11 ficou registrada como pendência específica para correção posterior.

### Documentação
- [Histórico 14/09/2026 — Português](docs/11_historico_2026-09-14.md)
- [Improvement History 2026-09-14 — English](docs/11_history_2026-09-14.md)
- [Historial de mejoras 14/09/2026 — Español](docs/11_historial_2026-09-14.md)

## [0.2.0] — Capítulo 1 expandido: 16 fases + áudio + cabeçada

### Adicionado
- Expansão da campanha de 6 para **16 fases**.
- Dez novas fases, da Fase 7 à Fase 16.
- Novos clientes: Valdemarildo, Claudecirvaldo, Geraldânio, Valdovino, Edivanildo, Professor Valdécio, Osvaldirson, Jocelmar, Ubiraldo e Gerentão.
- Fase 16 como **boss final do Capítulo 1**.
- Nova mecânica de **cabeçada em blocos interativos**.
- Reação visual e sonora dos blocos atingidos.
- Uso progressivo da cabeçada em pistas, mecanismos, plataformas, caminhos e desafios.
- Efeitos sonoros para ações e eventos importantes do jogo.
- Evolução do feedback visual e audiovisual.
- Tela narrativa de conclusão do Capítulo 1.
- Preparação da campanha para evolução futura por capítulos.

### Preservado
- Shopi e Etvaldo.
- As seis fases originais.
- Três níveis de dificuldade.
- Controles desktop e mobile.
- Vidas e checkpoints.
- Pontuação e ranking.
- Identidade humorística do jogo.
- Na Entrega Tranquila da Fase 1, ausência de objetos caindo de cima.

### Validação
A nova versão foi considerada funcional pelo autor após a implementação no Base44. A documentação registra a evolução; a validação contínua de regressão, mobile, áudio, dificuldades e campanha completa permanece parte do processo de qualidade.

## [0.1.4] — Fase 2: A Casa

### Adicionado
- Segunda fase jogável da campanha.
- Cleovasdo como segundo cliente problemático.
- Mecânica de perseguição do cliente.
- Ambientes domésticos.
- Obstáculos domésticos e progressão da nova fase.
- Integração da Fase 2 com os níveis de dificuldade existentes.
- Final cômico envolvendo a devolução da encomenda.

## [0.1.3] — Sistema de dificuldade

### Adicionado
- Três níveis globais de dificuldade.
- Ajuste real de quantidade, velocidade e comportamento dos obstáculos.
- Na Entrega Tranquila da Fase 1, objetos não caem de cima.

## [0.1.2] — Ranking

### Adicionado
- Ranking de líderes baseado no desempenho dos jogadores.
- Estrutura preparada para futura evolução do ranking por fase e recordes.

## [0.1.1] — Controles mobile

### Adicionado
- Controles por toque para celulares e tablets.
- Compatibilidade preservada com os controles de teclado.

## [0.1.0] — Protótipo inicial

### Adicionado
- Conceito inicial de Shopi — Entregas Impossíveis.
- Shopi como protagonista e entregador.
- Etvaldo como ajudante do caminhão.
- Primeira fase em um prédio.
- Tabacudo como primeiro cliente problemático.
- Plataformas, escadas e obstáculos verticais.
- Sistema de vidas e progressão da fase.
- Controles para desktop.

## Planejado

- Itens colecionáveis: 2 por fase.
- Coleção especial dos 6 pneus do caminhão.
- Estatísticas de partidas.
- Melhores tempos.
- Melhorias adicionais de acessibilidade.
- Capítulo 2.

---

O projeto é desenvolvido de forma incremental, principalmente com o Base44. Cada alteração relevante deve ser registrada nos arquivos de prompts e neste changelog. Funcionalidades devem ser marcadas como concluídas somente após implementação e validação.
