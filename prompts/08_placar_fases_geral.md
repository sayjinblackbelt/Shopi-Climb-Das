# Prompt 08 — Placar por fase e placar geral

## Objetivo

Evoluir o sistema atual de ranking do Shopi — Entregas Impossíveis para registrar e apresentar o melhor desempenho por fase e o desempenho acumulado da campanha.

## Regras principais

- Não reconstruir o jogo inteiro.
- Não remover ou quebrar o ranking existente.
- Preservar as 6 fases jogáveis.
- Preservar os 3 níveis de dificuldade.
- Preservar controles desktop e mobile.
- Preservar vidas, checkpoints, pontuação, progressão e demais sistemas atuais.
- Fazer a alteração de forma incremental e persistente.

## Placar por fase

Cada uma das 6 fases deve manter o melhor resultado do jogador.

Registrar, quando disponível:

- jogador/apelido;
- fase;
- pontuação;
- dificuldade utilizada;
- data do recorde.

### Regra de substituição

Quando o jogador concluir uma fase:

- se a nova pontuação for maior que o recorde anterior daquela fase, substituir o recorde;
- se a nova pontuação for menor, manter o recorde anterior;
- nunca apagar um melhor resultado por causa de uma tentativa inferior.

## Placar geral

Criar um placar geral da campanha.

O valor geral deve ser calculado como:

**melhor pontuação da Fase 1 + melhor pontuação da Fase 2 + melhor pontuação da Fase 3 + melhor pontuação da Fase 4 + melhor pontuação da Fase 5 + melhor pontuação da Fase 6**

O placar geral deve ser atualizado quando um recorde de qualquer fase for melhorado.

## Ranking

Manter duas formas de visualização:

### Ranking geral

Ordenar jogadores pela pontuação geral da campanha, do maior para o menor resultado.

### Ranking por fase

Permitir selecionar uma das 6 fases e visualizar os melhores resultados daquela fase.

Exibir a dificuldade utilizada junto do resultado quando essa informação estiver disponível.

## Resultado ao concluir uma fase

Após completar uma fase, apresentar de forma clara:

**ENTREGA CONCLUÍDA!**

Mostrar:

- pontuação obtida na fase;
- melhor pontuação da fase;
- indicação de novo recorde, quando ocorrer;
- pontuação geral da campanha;
- navegação para próxima fase, repetir, ranking e menu, respeitando o fluxo atual do jogo.

Quando houver novo recorde, utilizar uma mensagem destacada:

**🏆 NOVO RECORDE!**

## Persistência

Os dados devem permanecer disponíveis depois de:

- sair da fase;
- retornar ao menu;
- avançar para outra fase;
- fechar e reabrir o jogo.

Não usar somente variáveis temporárias de tela ou sessão para guardar os recordes.

## Dificuldade

Preservar os níveis existentes:

- Entrega Tranquila — ×1;
- Entrega Complicada — ×1,5;
- Entrega Impossível — ×2.

A dificuldade deve continuar influenciando a pontuação conforme as regras já implementadas.

Não criar rankings separados por dificuldade nesta etapa.

## Itens colecionáveis

Não implementar itens colecionáveis neste prompt. Essa é uma evolução separada e planejada para outra etapa.

## Segurança da alteração

- Não alterar física, controles ou layout além do necessário para exibir os placares.
- Não remover registros existentes.
- Não substituir o mecanismo persistente atual sem necessidade.
- Testar antes e depois da alteração.

## Critérios de aceitação

Considerar a evolução concluída somente se for possível verificar:

1. concluir qualquer fase e registrar a pontuação;
2. melhorar o recorde da fase e ver o novo valor salvo;
3. concluir a fase com pontuação menor e manter o recorde anterior;
4. visualizar ranking da fase;
5. visualizar ranking geral;
6. confirmar que o placar geral é a soma das melhores pontuações das 6 fases;
7. fechar e reabrir o jogo e verificar que os recordes permanecem;
8. testar o fluxo em desktop e mobile;
9. confirmar que os 3 níveis de dificuldade continuam funcionando.
