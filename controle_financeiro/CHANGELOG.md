# Changelog

## 0.4.12

- Verbas de reembolso (valor 0): detalhes sem o "a receber".

## 0.4.11

- Mês: clicar numa verba (ex.: Limpeza) destaca ela e todos os gastos que descontam dela.

## 0.4.10

- Textos de ajuda dos campos agora aparecem numa dica (ⓘ) ao lado do nome do campo,
  economizando espaço na tela.

## 0.4.9

- Fixos: editar não sobrescreve mais os valores dos meses. Para mudar o valor,
  marque "Alterar o valor" na edição (os campos de valor só se habilitam assim).

## 0.4.8

- Fixos: campo "Ordem no mês". Nas tabelas do mês os fixos ficam no topo nessa ordem,
  com os demais lançamentos abaixo.

## 0.4.7

- Contas: formulário de nova conta acima da lista.

## 0.4.6

- Fixos, Parcelados e Dívidas & poupanças: formulário de inserção acima da tabela.

## 0.4.5

- Ano: mesma barra de navegação do mês (fixa embaixo, com "Agora" e seletor de ano).

## 0.4.4

- Mês: a barra de navegação fica fixa e centralizada na parte de baixo da tela, como no HA.

## 0.4.3

- Mês: nova barra de navegação no estilo do Home Assistant (calendário, "Agora",
  anterior/próximo e menu ⋮), fixa no topo ao rolar.

## 0.4.2

- Parcelas: sem botões de editar/excluir no mês; qualquer alteração é feita na compra,
  em Parcelados (o nome da parcela leva até ela).

## 0.4.1

- Parcelas: o valor não pode mais ser alterado mês a mês; muda só editando a compra.

## 0.4.0

- Trava da fatura do cartão: informe o dia de fechamento em Contas ("Fecha dia") e
  a fatura do mês trava sozinha nesse dia, evitando lançar no mês errado. No mês,
  dá para travar manualmente ou destravar até o fim do dia para corrigir.
- O banco existente é atualizado automaticamente ao iniciar.

## 0.3.2

- Backups: botão "Restaurar de um arquivo…" para restaurar um backup (.db) baixado
  desta ou de outra instalação. O arquivo é validado antes e fica na lista como "Importado".
- Backups gravados como arquivo único, sem arquivos -wal/-shm soltos na pasta.

## 0.3.1

- Backups: quantidade de backups automáticos guardados configurável na tela Backups.

## 0.3.0

- Backups: automático diário (mantém os 30 mais recentes), backup manual,
  download e restauração pela nova tela **Backups**. Antes de restaurar, o estado
  atual é guardado para poder desfazer.

## 0.2.4

- Fixos: botão para esconder/mostrar os fixos encerrados (lembrado no navegador).

## 0.2.3

- Parcelados: botão para esconder/mostrar as compras quitadas (lembrado no navegador).

## 0.2.2

- Resumo anual: meses ainda não abertos mostram o saldo previsto (fixos, parcelas
  e lançamentos já feitos), sem precisar visitar cada mês.

## 0.2.1

- Fixos: opção de excluir (apaga o fixo e tudo o que ele lançou em todos os meses).

## 0.2.0

- Parcelados: escolha uma verba (ex.: Limpeza) e o valor descontado dela por
  parcela, preenchido com o valor da parcela de sinal invertido (editável).
- Lançamentos do cartão: valor aplicado na verba pode ser diferente do valor da compra.
- O banco existente é atualizado automaticamente ao iniciar.

## 0.1.9

- Fixos: o "valor lançado no controle" é preenchido com o sinal invertido
  (ex.: -609,92/2 → 304,96).

## 0.1.8

- Verbas: gasto no cartão acima da verba vira entrada. Uma verba de valor 0
  funciona como reembolso (ex.: assinaturas da empresa pagas no cartão).

## 0.1.7

- Contas: opção "Marcação ✓" para ligar/desligar a marcação de confirmado por conta.

## 0.1.6

- Fixos: o "valor lançado no controle" recebe o resultado calculado do valor,
  com o mesmo sinal (ex.: -609,92/2 → -304,96), e é atualizado sempre que o valor muda.

## 0.1.5

- Corrige o botão ✓ aparecendo como um quadrado sem estilo: o navegador usava o
  CSS antigo em cache. O endereço do CSS agora muda a cada versão.

## 0.1.4

- Fixos: ao escolher um controle, o "valor lançado no controle" é preenchido
  com o valor do fixo de sinal invertido (editável).

## 0.1.3

- Marcação ✓ de confirmado em lançamentos e faturas (o "verde" da planilha),
  com total do que ainda falta confirmar no mês.
- O banco existente é atualizado automaticamente ao iniciar.

## 0.1.2

- Botão ✎ para editar qualquer registro: lançamentos do mês, fixos, parcelados,
  parcelas individuais e movimentos de dívidas & poupanças.

## 0.1.1

- Corrige a página sem formatação (CSS não carregava pelo menu do Home Assistant).
- Opção "Exigir login", desligada por padrão.

## 0.1.0

- Primeira versão: visão mensal (Nuconta + Nubank), fixos, parcelados, verbas,
  dívidas & poupanças e resumo anual.
