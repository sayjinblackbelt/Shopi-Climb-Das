# Prompt 06 — Sistema de dificuldade

## Objetivo

Implementar três níveis globais de dificuldade sem reconstruir o jogo e sem remover funcionalidades existentes.

## Níveis

### 🟢 Entrega Tranquila

> É só entregar a caixa.

Multiplicador: **×1**

Experiência mais acessível, com menor quantidade/velocidade de obstáculos e maior tolerância a erros.

### 🟡 Entrega Complicada

> Tem certeza que esse endereço está certo?

Multiplicador: **×1,5**

Experiência intermediária, com quantidade e velocidade moderadas de obstáculos.

### 🔴 Entrega Impossível

> Você chamou o gerente?

Multiplicador: **×2**

Experiência mais desafiadora, com maior frequência, velocidade e comportamento dos obstáculos e clientes, sem se tornar injusta.

## Regra específica da Fase 1

Na **Entrega Tranquila**, não devem cair objetos de cima e Tabacudo não deve lançar objetos contra Shopi. A fase deve servir como introdução aos controles e à movimentação.

Nos níveis Complicada e Impossível, os objetos lançados por Tabacudo permanecem como parte do desafio.

## Integração

O sistema deve funcionar nas fases existentes, em desktop e mobile, preservando ranking, vidas, checkpoint, pontuação e demais sistemas já funcionais.