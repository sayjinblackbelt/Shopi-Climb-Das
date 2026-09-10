# Ranking e placares

## Objetivo

O sistema de ranking registra os melhores desempenhos dos jogadores e incentiva novas partidas para melhorar pontuação e desempenho.

## Estrutura atual

O jogo possui uma campanha com **6 fases jogáveis** e está evoluindo o sistema de pontuação para dois níveis: **placar por fase** e **placar geral da campanha**.

### Placar por fase

Cada fase deve manter o melhor resultado registrado para cada jogador.

Dados associados ao resultado:

- nome/apelido do jogador;
- fase;
- pontuação;
- dificuldade utilizada;
- data do registro, quando disponível no sistema.

### Regra de recorde

Ao concluir uma fase:

- se a nova pontuação for maior que o recorde anterior daquela fase, o novo resultado passa a ser o recorde;
- se a nova pontuação for menor, o recorde anterior permanece;
- a pontuação deve permanecer associada à fase correta.

O objetivo é evitar que uma tentativa inferior apague o melhor desempenho já conquistado.

### Placar geral

O placar geral representa o desempenho acumulado na campanha.

**Regra definida:** soma das melhores pontuações registradas pelo jogador nas 6 fases.

Isso permite diferenciar o desempenho consistente ao longo de toda a campanha de uma pontuação isolada em uma única fase.

## Apresentação

O sistema deve permitir visualizar:

- ranking geral por pontuação acumulada;
- ranking específico da Fase 1;
- ranking específico da Fase 2;
- ranking específico da Fase 3;
- ranking específico da Fase 4;
- ranking específico da Fase 5;
- ranking específico da Fase 6;
- dificuldade utilizada em cada resultado, quando disponível.

Uma interface simples com seleção da fase é preferível a múltiplas telas independentes.

## Feedback ao jogador

Após concluir uma fase, o resultado deve apresentar, quando disponível:

- pontuação obtida na fase;
- melhor pontuação da fase;
- pontuação geral da campanha;
- indicação de novo recorde.

Mensagem sugerida para novo recorde:

**🏆 NOVO RECORDE!**

## Persistência

Os melhores resultados precisam permanecer disponíveis após sair da fase, retornar ao menu ou reabrir o jogo.

A implementação deve utilizar o mecanismo persistente disponível no projeto, e não depender somente de variáveis temporárias do navegador.

## Integridade

O sistema deve validar dados básicos de pontuação no backend disponível, quando possível, e não confiar exclusivamente em valores enviados pelo cliente.

Evitar expor dados pessoais desnecessários.

## Evoluções futuras

- melhores tempos;
- filtros por período;
- temporadas ou desafios especiais;
- estatísticas detalhadas de partidas;
- recordes adicionais por categoria.

Por enquanto, a prioridade é consolidar **placar por fase + placar geral** sem quebrar o ranking existente.