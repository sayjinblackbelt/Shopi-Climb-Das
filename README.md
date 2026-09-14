# 📦 Shopi — Entregas Impossíveis

> Um jogo arcade 2D de plataforma vertical em que Shopi, um entregador carregando uma encomenda, precisa fazer seu trabalho enquanto enfrenta clientes absurdamente problemáticos.

🇧🇷 **Português** · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)

[![Jogar](https://img.shields.io/badge/🎮-Jogar%20agora-orange)](https://shopi-climb-dash.base44.app/)

## 🎮 Jogue agora

[**Abrir Shopi Climb Dash**](https://shopi-climb-dash.base44.app/)

**GitHub Pages:** https://sayjinblackbelt.github.io/Shopi-Climb-Das/

O portal GitHub Pages apresenta o jogo, documentação, navegação em três idiomas e contador global de visitantes.

## 📅 Publicação

**Data oficial de publicação do jogo:** **04/09/2026**.

O projeto foi publicado inicialmente como um MVP e evoluiu de forma incremental até a campanha atual de 20 fases.

## 🧾 Sobre o projeto

**Shopi — Entregas Impossíveis** é um projeto independente desenvolvido incrementalmente com Base44 e documentado no GitHub.

A proposta combina plataforma vertical, escadas, obstáculos, exploração, mecanismos, pontuação, progressão de campanha e comédia situacional.

> **Shopi não quer salvar o mundo. Ele só quer terminar a entrega.**

## 👥 Personagens

- **Shopi:** protagonista, entregador carismático, determinado e ligeiramente atrapalhado.
- **Etvaldo:** ajudante de Shopi no caminhão e parceiro recorrente.
- **Clientes/Bosses:** cada cliente transforma uma entrega comum em um desafio diferente.

## 🗺️ Campanha — Capítulo 1

| Fase | Local | Cliente | Desafio principal |
|---|---|---|---|
| 1 | O Prédio | Tabacudo | Reclama de tudo |
| 2 | A Casa | Cleovasdo | Devolução / perseguição |
| 3 | O Condomínio | Osvaldêncio | Bloqueios e rotas |
| 4 | O Centro Comercial | Jocelvânio | Localização |
| 5 | O Shopping | Ubiratânio | Pedido absurdo |
| 6 | O Centro de Distribuição | Edivaldir | Troca da encomenda |
| 7 | O Bairro | Valdemarildo | Endereço correto |
| 8 | O Prédio Comercial | Claudecirvaldo | Burocracia |
| 9 | A Central de Entregas | Geraldânio | Caos logístico |
| 10 | O Estacionamento | Valdovino | Orientação espacial |
| 11 | O Hospital | Edivanildo | Localização de setor |
| 12 | A Escola | Professor Valdécio | Percurso e rotas |
| 13 | O Mercado | Osvaldirson | Ambiente congestionado |
| 14 | A Obra | Jocelmar | Plataformas e timing |
| 15 | O Shopping | Ubiraldo | Exploração e combinação |
| 16 | A Última Entrega | Gerentão | Boss final |
| 17 | A Estação | — | Rotas e plataformas |
| 18 | O Hotel | — | Encontrar andar/quarto |
| 19 | O Parque de Diversões | — | Plataformas móveis e caminhos imprevisíveis |
| 20 | A Garagem da Shopi | — | Epílogo e encerramento do Capítulo 1 |

## 🎮 Gameplay atual

O jogo possui:

- **20 fases implementadas no Capítulo 1**;
- 3 níveis de dificuldade;
- plataformas, escadas e salto;
- vidas e checkpoints;
- pontuação e ranking;
- progressão de campanha;
- clientes como bosses;
- controles desktop e mobile;
- blocos interativos e mecânica de cabeçada;
- efeitos sonoros e feedback audiovisual;
- Código da Entrega a partir da Fase 6.

### Cabeçada

Shopi pode pular e atingir determinados blocos interativos com a cabeça. Eles podem revelar pontos, pistas, itens, abrir caminhos ou ativar mecanismos.

### Código da Entrega

A partir da Fase 6, cada entrega pode apresentar um código simples, por exemplo:

`SHP-06-EDV-4721`

O objetivo é reforçar a aparência de uma operação real de logística sem criar um sistema complexo.

### Dificuldades

🟢 **Entrega Tranquila** — “É só entregar a caixa.” — ×1  
🟡 **Entrega Complicada** — “Tem certeza que esse endereço está certo?” — ×1,5  
🔴 **Entrega Impossível** — “Você chamou o gerente?” — ×2

Na Entrega Tranquila da Fase 1 não existem objetos caindo de cima.

## 🧪 Qualidade e testes

O projeto segue:

**Ideia → Prompt → Base44 → Implementação → Teste → Feedback → Ajuste → Registro no GitHub**

O fluxo crítico de progressão, menus, pausa, Game Over e conclusão de fases foi considerado funcional pelo autor. A versão atual deve ser tratada como uma campanha de **20 fases implementadas**, com foco agora em refinamento e balanceamento.

Durante o ciclo de melhorias de 14/09/2026, foi identificada uma pendência na **Fase 11 — O Hospital**: existe um ponto em que um salto entre duas partes do cenário não é possível. A correção prevista é reduzir o espaço ou inserir um ponto de apoio/plataforma intermediária.

## 👥 Contador de visitantes

O portal GitHub Pages possui agora um contador global de visitantes, independente do ranking do jogo.

**Marco registrado:** 151 visitantes em 14/09/2026.

## 📁 Documentação

- [Conceito](docs/01_conceito.md)
- [Personagens](docs/02_personagens.md)
- [Fases e campanha](docs/03_fases.md)
- [Gameplay](docs/04_gameplay.md)
- [Clientes / Bosses](docs/05_clientes_bosses.md)
- [Ranking](docs/06_ranking.md)
- [Métricas](docs/07_metricas.md)
- [Base44](docs/08_base44.md)
- [Roadmap](docs/09_roadmap.md)
- [Testes com alunos](docs/10_testes_com_alunos.md)
- [Histórico de melhorias — PT](docs/11_historico_2026-09-14.md)
- [Improvement History — EN](docs/11_history_2026-09-14.md)
- [Historial de mejoras — ES](docs/11_historial_2026-09-14.md)
- [Changelog](CHANGELOG.md)

### Prompts principais

- [MVP](prompts/01_mvp.md)
- [Controles touch](prompts/02_controles_touch.md)
- [Ranking](prompts/03_ranking.md)
- [Contador de visitantes](prompts/04_contador_visitantes.md)
- [Fase 2](prompts/05_fase_2_casa.md)
- [Dificuldade](prompts/06_dificuldade.md)
- [Placar por fases e geral](prompts/08_placar_fases_geral.md)
- [Capítulo 1, áudio e cabeçada](prompts/09_capitulo_1_16_fases_audio.md) — registro histórico da expansão até a Fase 16.

## 📊 Status

**Capítulo 1:** 20 fases implementadas.  
**Publicação oficial:** 04/09/2026.  
**Mobile:** controles funcionando bem.  
**Fluxo de campanha:** funcional após correções.  
**Visitantes:** 151 registrados em 14/09/2026.  
**Próxima correção registrada:** Fase 11, salto impossível.  
**Próximo ciclo:** balanceamento, refinamento e testes das 20 fases.

## 👨‍💻 Autor

**Filipe G Morais**

Projeto independente de experimentação em criação de jogos, tecnologia, design visual e desenvolvimento incremental com IA/no-code.
