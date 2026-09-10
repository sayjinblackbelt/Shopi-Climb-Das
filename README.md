# 📦 Shopi — Entregas Impossíveis

> Um jogo arcade 2D de plataforma vertical em que Shopi, um entregador carregando uma encomenda, precisa fazer seu trabalho enquanto enfrenta clientes absurdamente problemáticos.

🇧🇷 **Português** · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)

[![Jogar](https://img.shields.io/badge/🎮-Jogar%20agora-orange)](https://shopi-climb-dash.base44.app/)
[![Status](https://img.shields.io/badge/status-6%20fases%20jogáveis-brightgreen)](#status-atual)
[![Desenvolvido com](https://img.shields.io/badge/desenvolvido%20com-Base44-blue)](#desenvolvimento)

## 🎮 Jogue agora

[**Abrir Shopi Climb Dash**](https://shopi-climb-dash.base44.app/)

O jogo atual funciona diretamente no navegador, em computadores e dispositivos móveis. As seis fases da campanha estão jogáveis e foram testadas até o final.

## 🧾 Sobre o projeto

**Shopi — Entregas Impossíveis** é um projeto independente de jogo 2D desenvolvido de forma incremental com Base44 e documentado no GitHub.

A proposta combina plataforma vertical, escadas, obstáculos, pontuação, progressão de campanha e comédia situacional.

O diferencial está nos **clientes problemáticos**: em vez de enfrentar vilões tradicionais, Shopi precisa simplesmente conseguir realizar seu trabalho enquanto cada cliente transforma uma entrega comum em uma situação absurda.

> **Shopi não quer salvar o mundo. Ele só quer terminar a entrega.**

## 👥 Personagens

### 📦 Shopi

É o protagonista e entregador. Carismático, determinado e ligeiramente atrapalhado, Shopi carrega durante as fases a caixa que precisa entregar.

### 🚚 Etvaldo

É o ajudante de Shopi no caminhão de entregas. Personagem recorrente, Etvaldo participa da narrativa e frequentemente acaba envolvido em situações absurdas.

### 😡 Clientes / Bosses

Cada fase apresenta um cliente problemático que funciona como desafio narrativo e mecânico:

- **Tabacudo** — reclama de tudo.
- **Cleovasdo** — quer devolver a encomenda.
- **Osvaldêncio** — bloqueia caminhos.
- **Jocelvânio** — nunca está no endereço.
- **Ubiratânio** — pediu algo absurdo.
- **Edivaldir** — quer trocar a encomenda.

## 🗺️ Campanha

As seis fases atuais estão jogáveis:

| Fase | Local | Cliente | Problema |
|---|---|---|---|
| 1 | Prédio | Tabacudo | Reclama de tudo |
| 2 | Casa | Cleovasdo | Quer devolver a encomenda |
| 3 | Condomínio | Osvaldêncio | Bloqueia caminhos |
| 4 | Centro comercial | Jocelvânio | Nunca está no endereço |
| 5 | Shopping | Ubiratânio | Pediu algo absurdo |
| 6 | Centro de distribuição | Edivaldir | Quer trocar a encomenda |

A campanha foi testada pelo autor até a conclusão da Fase 6.

## 🎮 Gameplay atual

O jogo possui:

- 6 fases jogáveis;
- 3 níveis de dificuldade;
- plataformas e escadas;
- salto;
- vidas;
- checkpoints;
- pontuação;
- progressão entre fases;
- clientes como bosses;
- controles desktop;
- controles por toque para dispositivos móveis.

### Dificuldades

🟢 **Entrega Tranquila** — “É só entregar a caixa.” — ×1

🟡 **Entrega Complicada** — “Tem certeza que esse endereço está certo?” — ×1,5

🔴 **Entrega Impossível** — “Você chamou o gerente?” — ×2

Na Entrega Tranquila da Fase 1 não existem objetos caindo de cima. As dificuldades superiores aumentam a pressão, quantidade, velocidade ou comportamento dos obstáculos de acordo com a fase.

## 📱 Controles

### Desktop

- ← / → — movimentar
- ↑ / ↓ — subir e descer escadas
- Espaço — pular

### Celular

A versão atual possui controles por toque para movimentação e salto.

## 🏆 Placar e ranking

O jogo possui sistema de ranking e está evoluindo para dois níveis de pontuação:

- **Placar por fase:** melhor pontuação registrada em cada uma das seis fases, associada ao jogador e à dificuldade utilizada.
- **Placar geral:** soma das melhores pontuações registradas nas seis fases.

A evolução do sistema deve preservar os dados de ranking existentes e manter o melhor resultado de cada fase quando um novo resultado for inferior.

## 👥 Contador de visitantes

O contador global de visitantes continua como recurso planejado. Ele deve ser persistente, separado do ranking e não interferir na mecânica do jogo.

## 🎯 Itens colecionáveis

Os itens colecionáveis continuam como uma evolução planejada, não como recurso confirmado da versão atual. A proposta é ter dois itens por fase, descobertos por exploração e salto, com bônus de pontuação.

## 🎯 Identidade do jogo

A identidade de Shopi é construída a partir de:

- personagens inusitados;
- nomes inesperados;
- humor baseado em situações cotidianas;
- clientes como bosses;
- problemas de entrega transformados em desafios;
- Shopi e Etvaldo como dupla recorrente.

Jogos arcade clássicos são apenas uma referência de gênero. O projeto deve manter personagens, arte, design de fases, narrativa e identidade audiovisual próprios.

## 🛠️ Desenvolvimento

O **Base44** é utilizado como principal ferramenta de prototipagem e evolução do jogo.

O processo atual é:

**Ideia → Prompt → Base44 → Teste → Ajuste → Registro no GitHub**

As mudanças devem ser incrementais, permitindo testar e validar cada alteração antes de introduzir a próxima.

Cada mudança relevante deve ser registrada no histórico de versões e, quando aplicável, com seu prompt correspondente na pasta de prompts.

## 📁 Documentação

### Conceito e design
- [Conceito](docs/01_conceito.md)
- [Personagens](docs/02_personagens.md)
- [Fases e campanha](docs/03_fases.md)
- [Gameplay](docs/04_gameplay.md)
- [Clientes / Bosses](docs/05_clientes_bosses.md)

### Sistemas
- [Ranking e placares](docs/06_ranking.md)
- [Métricas](docs/07_metricas.md)
- [Base44 e processo de desenvolvimento](docs/08_base44.md)
- [Roadmap](docs/09_roadmap.md)

### Histórico de desenvolvimento
- [Changelog](CHANGELOG.md)
- [Prompt 01 — MVP inicial](prompts/01_mvp.md)
- [Prompt 02 — Controles por toque](prompts/02_controles_touch.md)
- [Prompt 03 — Ranking](prompts/03_ranking.md)
- [Prompt 04 — Contador de visitantes](prompts/04_contador_visitantes.md)
- [Prompt 05 — Fase 2: A Casa](prompts/05_fase_2_casa.md)
- [Prompt 06 — Sistema de dificuldade](prompts/06_dificuldade.md)
- [Prompt 08 — Placar por fase e placar geral](prompts/08_placar_fases_geral.md)

## 📊 Status atual

**Versão de desenvolvimento:** campanha de 6 fases jogável.

**Implementado e testado:** 6 fases, 3 níveis de dificuldade, Shopi, Etvaldo, seis clientes/bosses, plataformas, escadas, salto, vidas, checkpoint, pontuação, progressão de campanha, ranking e controles desktop/mobile.

**Próxima evolução:** validar a implementação do placar por fase e do placar geral; depois retomar itens colecionáveis, refinamentos de gameplay e demais melhorias do roadmap.

## 👨‍💻 Autor

**Filipe G Morais**

Projeto independente de experimentação em criação de jogos, tecnologia, design visual e desenvolvimento incremental com IA/no-code.

---

> Projeto em evolução. O GitHub registra as decisões de design, os prompts utilizados, as versões e o roadmap do desenvolvimento.
