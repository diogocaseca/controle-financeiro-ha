# Controle Financeiro

## Primeiro acesso

Inicie o app e abra **Finanças** no menu lateral do Home Assistant. Como você já
está logado no HA, o app abre direto, sem pedir senha.

## Opções

- **Exigir login** (`exigir_login`): ligue para o app pedir o próprio usuário e
  senha também pelo menu do HA. O login inicial é **admin / admin**; troque a senha
  pelo ícone ⚙ no topo.

O acesso direto pela porta (aba **Rede**) sempre pede login. Se for habilitá-lo,
ligue antes **Exigir login** uma vez e troque a senha padrão.

## Dados e backup

Os dados ficam na pasta `/data` do app (`financas.db`). Ela entra nos backups do
Home Assistant automaticamente.

O próprio app também faz um backup por dia em `/data/backups` (ficam os 30 mais
recentes). Na tela **Backups** dá para fazer um backup na hora, baixar qualquer
um e restaurar. Antes de restaurar, o estado atual é guardado como
“Antes de restaurar”, para poder desfazer.

Para trazer um banco que você já usava no computador, restaure um backup do app
contendo o arquivo, ou peça ajuda para criar uma rotina de importação (ainda não
existe pela interface).

## Acesso direto

Por padrão o app só é acessível pelo Home Assistant. Para abrir pelo endereço
`http://<ip-do-ha>:<porta>`, defina uma porta na aba **Rede** do app.
