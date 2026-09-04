# 📦 Shopi — Entregas Impossíveis

> Um jogo arcade 2D de plataforma vertical em que Shopi, um entregador carregando uma encomenda, precisa fazer seu trabalho enquanto enfrenta clientes absurdamente problemáticos.

🇧🇷 **Português** · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)

[![Jogar](https://img.shields.io/badge/🎮-Jogar%20agora-orange)](https://shopi-climb-dash.base44.app/)
[![Status](https://img.shields.io/badge/status-protótipo%20jogável-brightgreen)](#status-atual)
[![Desenvolvido com](https://img.shields.io/badge/desenvolvido%20com-Base44-blue)](#desenvolvimento)

## 🎮 Jogue agora

[**Abrir Shopi Climb Dash**](https://shopi-climb-dash.base44.app/)

O protótipo atual funciona diretamente no navegador, em computadores e dispositivos móveis.

## 🧾 Sobre o projeto

**Shopi — Entregas Impossíveis** é um projeto independente de jogo 2D desenvolvido de forma incremental com Base44 e documentado no GitHub.

A proposta combina plataforma vertical, escadas, obstáculos, pontuação e comédia situacional.

O diferencial está nos **clientes problemáticos**: em vez de enfrentar vilões tradicionais, Shopi precisa simplesmente conseguir realizar seu trabalho enquanto cada cliente transforma uma entrega comum em uma situação absurda.

> **Shopi não quer salvar o mundo. Ele só quer terminar a entrega.**

## 👥 Personagens

### 📦 Shopi

É o protagonista e entregador. Carismático, determinado e ligeiramente atrapalhado, Shopi carrega durante as fases a caixa que precisa entregar.

### 🚚 Etvaldo

É o ajudante de Shopi no caminhão de entregas. Personagem recorrente, Etvaldo participa da narrativa e frequentemente acaba envolvido em situações absurdas.

### 😡 Tabacudo

É o primeiro cliente problemático. Reclama de tudo e dificulta a chegada de Shopi ao topo do prédio.

## 🏢 Primeira fase

### Fase 1 — O Prédio

Shopi precisa subir pelo prédio, desviar dos objetos lançados por Tabacudo, encontrar Etvaldo e tentar concluir a entrega.

A fase utiliza:

- plataformas;
- escadas;
- obstáculos com diferentes comportamentos;
- vidas;
- checkpoint;
- pontuação;
- progressão vertical;
- encontro final com o cliente.

## 📱 Plataformas e controles

### Desktop

- ← / → — movimentar
- ↑ / ↓ — subir e descer escadas
- Espaço — pular

### Celular

A versão atual possui **controles por toque**, mantendo a experiência compatível com a versão desktop.

## 🏆 Ranking

O jogo possui um **ranking de líderes** para comparar o desempenho dos jogadores.

Futuramente, o sistema poderá evoluir para rankings por fase, recordes pessoais e estatísticas adicionais.

## 👥 Contador de visitantes

A próxima versão planejada inclui um **contador global de visitantes**, persistente entre sessões e dispositivos e separado do ranking de jogadores.

## 🗺️ Campanha planejada

| Fase | Local | Cliente | Problema |
|---|---|---|---|
| 1 | Prédio | Tabacudo | Reclama de tudo |
| 2 | Casa | Cleovasdo | Quer devolver a encomenda |
| 3 | Condomínio | Osvaldêncio | Bloqueia caminhos |
| 4 | Centro comercial | Jocelvânio | Nunca está no endereço |
| 5 | Shopping | Ubiratânio | Pediu algo absurdo |
| 6 | Centro de distribuição | Edivaldir | Quer trocar a encomenda |

Cada fase deverá apresentar um novo local, um cliente com personalidade própria e uma situação de entrega que se transforma em desafio de gameplay.

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
- [Ranking](docs/06_ranking.md)
- [Métricas](docs/07_metricas.md)
- [Base44 e processo de desenvolvimento](docs/08_base44.md)
- [Roadmap](docs/09_roadmap.md)

### Histórico de desenvolvimento
- [Changelog](CHANGELOG.md)
- [Prompt 01 — MVP inicial](prompts/01_mvp.md)
- [Prompt 02 — Controles por toque](prompts/02_controles_touch.md)
- [Prompt 03 — Ranking](prompts/03_ranking.md)
- [Prompt 04 — Contador de visitantes](prompts/04_contador_visitantes.md)

## 📊 Status atual

**Versão:** 0.1.2 — protótipo jogável.

**Implementado:** primeira fase, Shopi, Etvaldo, Tabacudo, controles desktop, controles por toque e ranking de líderes.

**Próximo passo:** implementar o contador global de visitantes e iniciar a revisão de qualidade da primeira fase.

## 👨‍💻 Autor

**Filipe G Morais**

Projeto independente de experimentação em criação de jogos, tecnologia, design visual e desenvolvimento incremental com IA/no-code.

---

> Projeto em evolução. O GitHub registra as decisões de design, os prompts utilizados, as versões e o roadmap do desenvolvimento.
