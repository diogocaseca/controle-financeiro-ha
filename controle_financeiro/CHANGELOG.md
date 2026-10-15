# Changelog

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
