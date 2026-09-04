# 📦 Shopi — Entregas Impossíveis

> Um jogo arcade 2D de plataforma vertical em que Shopi, um entregador carregando uma encomenda, precisa fazer seu trabalho enquanto enfrenta clientes absurdamente problemáticos.

[![Jogar](https://img.shields.io/badge/🎮-Jogar%20agora-orange)](https://shopi-climb-dash.base44.app/)
[![Status](https://img.shields.io/badge/status-protótipo%20jogável-brightgreen)](#status-atual)
[![Plataforma](https://img.shields.io/badge/desenvolvimento-Base44-blue)](#desenvolvimento)

## 🎮 Jogue agora

**https://shopi-climb-dash.base44.app/**

O protótipo pode ser acessado diretamente pelo navegador, em desktop ou celular.

## 🧾 Sobre o projeto

**Shopi — Entregas Impossíveis** é um projeto independente de jogo 2D desenvolvido incrementalmente com o Base44 e documentado no GitHub.

A ideia combina plataforma vertical, escadas, obstáculos, pontuação e humor situacional.

O diferencial é o sistema de **clientes problemáticos**: em vez de enfrentar vilões tradicionais, Shopi precisa simplesmente conseguir realizar seu trabalho.

> **Shopi não quer salvar o mundo. Ele só quer terminar a entrega.**

## 👥 Personagens

### 📦 Shopi

Entregador protagonista. É carismático, determinado e ligeiramente atrapalhado. Durante as fases, carrega a caixa da entrega.

### 🚚 Etvaldo

Ajudante de Shopi no caminhão de entregas. É um personagem recorrente e parte importante da narrativa.

### 😡 Tabacudo

Primeiro cliente problemático. Reclama de tudo e dificulta a chegada de Shopi ao topo do prédio.

## 🏢 Primeira fase

### Fase 1 — O Prédio

Shopi precisa subir pelo prédio, desviando dos objetos lançados por Tabacudo, encontrar Etvaldo e tentar concluir a entrega.

A fase utiliza:

- plataformas;
- escadas;
- obstáculos com comportamentos variados;
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

A versão atual possui **controles por toque**.

## 🏆 Ranking

O jogo já possui um **ranking de líderes**, permitindo comparar o desempenho dos jogadores.

O ranking deverá evoluir posteriormente para diferentes fases e recordes.

## 👥 Contador de visitantes

**Próxima melhoria planejada:** adicionar um contador global de visitantes, persistente entre sessões e independente do dispositivo do jogador.

## 🗺️ Campanha planejada

| Fase | Local | Cliente | Problema |
|---|---|---|---|
| 1 | Prédio | Tabacudo | Reclama de tudo |
| 2 | Casa | Cleovasdo | Quer devolver a encomenda |
| 3 | Condomínio | Osvaldêncio | Bloqueia caminhos |
| 4 | Centro comercial | Jocelvânio | Nunca está no endereço |
| 5 | Shopping | Ubiratânio | Pediu algo absurdo |
| 6 | Centro de distribuição | Edivaldir | Quer trocar a encomenda |

A campanha será expandida gradualmente. Cada fase deve apresentar um local, cliente e problema próprios.

## 🎯 Identidade do jogo

O projeto busca uma identidade própria por meio de:

- personagens inusitados;
- nomes absurdos ou inesperados;
- humor de situações cotidianas;
- clientes como "bosses";
- problemas de entrega transformados em desafios de gameplay;
- Shopi e Etvaldo como dupla recorrente.

O projeto pode utilizar a linguagem dos arcades clássicos como referência de gênero, mas não deve copiar personagens, sprites, músicas, layouts ou outros elementos de obras existentes.

## 🛠️ Desenvolvimento

O **Base44** é utilizado como principal ferramenta de prototipagem e evolução do jogo.

Ciclo atual:

**Ideia → Prompt → Base44 → Teste → Ajuste → Registro no GitHub**

As alterações devem ser pequenas o suficiente para permitir teste e validação antes da próxima mudança.

## 📁 Documentação

- [Conceito](docs/01_conceito.md)
- [Personagens](docs/02_personagens.md)
- [Fases e campanha](docs/03_fases.md)
- [Gameplay](docs/04_gameplay.md)
- [Clientes / Bosses](docs/05_clientes_bosses.md)
- [Ranking](docs/06_ranking.md)
- [Métricas](docs/07_metricas.md)
- [Base44 e processo de desenvolvimento](docs/08_base44.md)
- [Roadmap](docs/09_roadmap.md)
- [Histórico de mudanças](CHANGELOG.md)

## 📊 Status atual

**Versão:** 0.1.0 — protótipo jogável.

**Recursos registrados:** primeira fase, Shopi, Etvaldo, Tabacudo, controles desktop, controles por toque e ranking de líderes.

**Próximo passo:** contador global de visitantes e revisão de qualidade da primeira fase.

## 👨‍💻 Autor

**Filipe G Morais**

Projeto independente de experimentação em criação de jogos, tecnologia, design e desenvolvimento incremental com IA/no-code.

---

> Projeto em evolução. A documentação acompanha as decisões de design, o roadmap e as principais mudanças realizadas durante o desenvolvimento.
