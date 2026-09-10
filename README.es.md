# 📦 Shopi — Entregas Imposibles

> Un juego arcade 2D de plataformas verticales en el que Shopi, un repartidor que lleva una caja, intenta hacer su trabajo mientras enfrenta a clientes absurdamente problemáticos.

🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 **Español**

[![Jugar](https://img.shields.io/badge/🎮-Jugar%20ahora-orange)](https://shopi-climb-dash.base44.app/)
[![Estado](https://img.shields.io/badge/estado-6%20fases%20jugables-brightgreen)](#estado-actual)
[![Desarrollado con](https://img.shields.io/badge/desarrollado%20con-Base44-blue)](#desarrollo)

## 🎮 Jugar ahora

[**Abrir Shopi Climb Dash**](https://shopi-climb-dash.base44.app/)

El juego actual funciona en el navegador, tanto en computadora como en dispositivos móviles. Las seis fases de la campaña son jugables y fueron probadas hasta el final.

## 🧾 Sobre el proyecto

**Shopi — Entregas Imposibles** es un proyecto independiente de videojuego desarrollado de forma incremental con Base44 y documentado en GitHub.

El juego combina plataformas verticales, escaleras, obstáculos, puntuación, progresión de campaña y comedia situacional.

En lugar de villanos tradicionales, Shopi enfrenta a **clientes problemáticos** que convierten entregas normales en desafíos absurdos.

> **Shopi no quiere salvar el mundo. Solo quiere terminar la entrega.**

## 👥 Personajes

### 📦 Shopi
El protagonista y repartidor. Es decidido, carismático y un poco torpe. Durante las fases lleva la caja que debe entregar.

### 🚚 Etvaldo
El ayudante de Shopi en el camión y compañero recurrente. Forma parte de la historia y suele terminar en situaciones absurdas.

### 😡 Clientes / Bosses
La campaña actual presenta seis clientes problemáticos:

- **Tabacudo** — se queja de todo.
- **Cleovasdo** — quiere devolver la entrega.
- **Osvaldêncio** — bloquea los caminos.
- **Jocelvânio** — nunca está en la dirección indicada.
- **Ubiratânio** — pidió algo absurdo.
- **Edivaldir** — quiere cambiar la entrega.

## 🗺️ Campaña

Las seis fases actuales son jugables:

| Fase | Lugar | Cliente | Problema |
|---|---|---|---|
| 1 | Edificio | Tabacudo | Se queja de todo |
| 2 | Casa | Cleovasdo | Quiere devolver la entrega |
| 3 | Condominio | Osvaldêncio | Bloquea los caminos |
| 4 | Centro comercial | Jocelvânio | Nunca está en la dirección indicada |
| 5 | Centro comercial grande | Ubiratânio | Pidió algo absurdo |
| 6 | Centro de distribución | Edivaldir | Quiere cambiar la entrega |

El autor probó la campaña completa hasta terminar la Fase 6.

## 🎮 Gameplay actual

El juego incluye:

- 6 fases jugables;
- 3 niveles de dificultad;
- plataformas y escaleras;
- salto;
- vidas;
- checkpoints;
- puntuación;
- progresión de campaña;
- clientes como bosses;
- controles de computadora;
- controles táctiles para móviles.

### Dificultad

🟢 **Entrega Tranquila** — “Solo entrega la caja.” — ×1

🟡 **Entrega Complicada** — “¿Seguro que esta es la dirección correcta?” — ×1,5

🔴 **Entrega Imposible** — “¿Llamaste al gerente?” — ×2

En la Fase 1, Entrega Tranquila no tiene objetos que caen desde arriba. Las dificultades superiores aumentan la presión, cantidad, velocidad o comportamiento de los obstáculos según la fase.

## 📱 Controles

### Computadora

- ← / → — mover
- ↑ / ↓ — subir y bajar escaleras
- Espacio — saltar

### Móvil

La versión actual incluye controles táctiles para movimiento y salto.

## 🏆 Puntuaciones y clasificación

El juego ya cuenta con una tabla de líderes y está evolucionando hacia dos vistas de puntuación:

- **Puntuación por fase:** mejor puntuación registrada para cada una de las seis fases, asociada al jugador y a la dificultad utilizada.
- **Puntuación general:** suma de las mejores puntuaciones del jugador en las seis fases.

El nuevo sistema debe preservar los datos existentes y mantener el mejor resultado de cada fase cuando un nuevo intento tenga una puntuación menor.

## 👥 Contador de visitantes

El contador global de visitantes sigue planificado. Debe ser persistente, estar separado de la clasificación de jugadores y no interferir con la jugabilidad.

## 🎯 Coleccionables

Los objetos coleccionables siguen siendo una función planificada, no una función confirmada de la versión actual. La propuesta es tener dos objetos por fase, descubiertos mediante exploración y salto, con bonificaciones de puntuación.

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
- [Puntuaciones y ranking](docs/06_ranking.md)
- [Métricas](docs/07_metricas.md)
- [Base44 y proceso de desarrollo](docs/08_base44.md)
- [Roadmap](docs/09_roadmap.md)
- [Historial de cambios](CHANGELOG.md)
- [Prompt del MVP](prompts/01_mvp.md)
- [Prompt de controles táctiles](prompts/02_controles_touch.md)
- [Prompt del ranking](prompts/03_ranking.md)
- [Prompt del contador de visitantes](prompts/04_contador_visitantes.md)
- [Prompt de la Fase 2](prompts/05_fase_2_casa.md)
- [Prompt del sistema de dificultad](prompts/06_dificuldade.md)
- [Prompt de puntuación por fase y general](prompts/08_placar_fases_geral.md)

## 📊 Estado actual

**Estado de desarrollo:** campaña jugable de 6 fases.

**Implementado y probado:** 6 fases, 3 niveles de dificultad, Shopi, Etvaldo, seis clientes/bosses, plataformas, escaleras, salto, vidas, checkpoints, puntuación, progresión de campaña, clasificación y controles de computadora/móviles.

**Próximo paso:** validar la implementación de la puntuación por fase y de la puntuación general; después retomar los coleccionables, el refinamiento del gameplay y otras mejoras del roadmap.

## 👨‍💻 Autor

**Filipe G Morais**

Proyecto independiente de experimentación con diseño de juegos, tecnología, diseño visual y desarrollo incremental mediante herramientas de IA/no-code.
