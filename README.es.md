# 📦 Shopi — Entregas Imposibles

> Un juego arcade 2D de plataformas verticales en el que Shopi, un repartidor que lleva una caja, intenta hacer su trabajo mientras enfrenta a clientes absurdamente problemáticos.

🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 **Español**

[![Jugar](https://img.shields.io/badge/🎮-Jugar%20ahora-orange)](https://shopi-climb-dash.base44.app/)
[![Estado](https://img.shields.io/badge/estado-prototipo%20jugable-brightgreen)](#estado-actual)
[![Desarrollado con](https://img.shields.io/badge/desarrollado%20con-Base44-blue)](#desarrollo)

## 🎮 Jugar ahora

[**Abrir Shopi Climb Dash**](https://shopi-climb-dash.base44.app/)

El prototipo actual funciona en el navegador, tanto en computadora como en dispositivos móviles.

## 🧾 Sobre el proyecto

**Shopi — Entregas Imposibles** es un proyecto independiente de videojuego desarrollado de forma incremental con Base44 y documentado en GitHub.

El juego combina plataformas verticales, escaleras, obstáculos, puntuación y comedia situacional.

La idea central es sencilla: en lugar de luchar contra villanos tradicionales, Shopi tiene que completar su entrega mientras enfrenta clientes que hacen que el trabajo sea mucho más difícil de lo necesario.

> **Shopi no quiere salvar el mundo. Solo quiere terminar la entrega.**

## 👥 Personajes

### 📦 Shopi
El protagonista y repartidor. Es decidido, carismático y un poco torpe. Durante las fases lleva la caja que debe entregar.

### 🚚 Etvaldo
El ayudante de Shopi en el camión y compañero recurrente. Forma parte de la historia y suele terminar en situaciones absurdas.

### 😡 Tabacudo
El primer cliente problemático. Se queja de todo y dificulta que Shopi llegue hasta la parte superior del edificio.

## 🏢 Primera fase

### Fase 1 — El edificio

Shopi debe subir por el edificio, esquivar los objetos que Tabacudo lanza, encontrar a Etvaldo e intentar completar la entrega.

La fase utiliza:

- plataformas;
- escaleras;
- obstáculos con diferentes comportamientos;
- vidas;
- checkpoint;
- puntuación;
- progresión vertical;
- encuentro final con el cliente.

## 📱 Plataformas y controles

### Computadora

- ← / → — mover
- ↑ / ↓ — subir y bajar escaleras
- Espacio — saltar

### Móvil

La versión actual incluye controles táctiles para jugar en dispositivos móviles.

## 🏆 Clasificación

El juego cuenta con una tabla de líderes para comparar el rendimiento de los jugadores.

En futuras versiones, el sistema podrá incluir récords por fase y mejores marcas personales.

## 👥 Contador de visitantes

Está planificado un contador global de visitantes para la próxima versión. Debe funcionar entre sesiones y dispositivos sin interferir con el juego.

## 🗺️ Campaña planificada

| Fase | Lugar | Cliente | Problema |
|---|---|---|---|
| 1 | Edificio | Tabacudo | Se queja de todo |
| 2 | Casa | Cleovasdo | Quiere devolver la entrega |
| 3 | Condominio | Osvaldêncio | Bloquea los accesos |
| 4 | Centro comercial | Jocelvânio | Nunca está en la dirección indicada |
| 5 | Centro comercial grande | Ubiratânio | Pidió algo absurdo |
| 6 | Centro de distribución | Edivaldir | Quiere cambiar la entrega |

Cada fase tendrá su propio lugar, cliente y problema de gameplay.

## 🎯 Identidad del juego

La identidad de Shopi se construye alrededor de:

- personajes inusuales;
- nombres inesperados;
- situaciones cotidianas convertidas en comedia;
- clientes como bosses;
- problemas de entrega convertidos en desafíos de gameplay;
- Shopi y Etvaldo como dupla recurrente.

Los juegos arcade clásicos son únicamente una referencia de género. El proyecto debe mantener sus propios personajes, dirección artística, diseño de niveles e identidad audiovisual.

## 🛠️ Desarrollo

Base44 es la principal herramienta de prototipado y evolución del juego.

Flujo actual:

**Idea → Prompt → Base44 → Prueba → Ajuste → Documentación en GitHub**

Las modificaciones deben hacerse de forma incremental para probar cada versión antes de introducir la siguiente.

## 📁 Documentación

- [Concepto](docs/01_conceito.md)
- [Personajes](docs/02_personagens.md)
- [Fases y campaña](docs/03_fases.md)
- [Gameplay](docs/04_gameplay.md)
- [Clientes / Bosses](docs/05_clientes_bosses.md)
- [Ranking](docs/06_ranking.md)
- [Métricas](docs/07_metricas.md)
- [Base44 y proceso de desarrollo](docs/08_base44.md)
- [Roadmap](docs/09_roadmap.md)
- [Historial de cambios](CHANGELOG.md)
- [Prompt del MVP](prompts/01_mvp.md)
- [Prompt de controles táctiles](prompts/02_controles_touch.md)
- [Prompt del ranking](prompts/03_ranking.md)
- [Prompt del contador de visitantes](prompts/04_contador_visitantes.md)

## 📊 Estado actual

**Versión:** 0.1.2 — prototipo jugable.

**Implementado:** primera fase, Shopi, Etvaldo, Tabacudo, controles de computadora, controles táctiles y tabla de líderes.

**Próximo paso:** contador global de visitantes, revisión del gameplay y refinamiento de la primera fase.

## 👨‍💻 Autor

**Filipe G Morais**

Proyecto independiente de experimentación con diseño de juegos, tecnología, diseño visual y desarrollo incremental mediante herramientas de IA/no-code.
