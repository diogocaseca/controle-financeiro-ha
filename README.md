# Controle Financeiro — repositório de apps do Home Assistant

Empacota o [Controle Financeiro](https://github.com/diogocaseca/controle-financeiro)
como app (antigo “add-on”) do Home Assistant, com acesso pelo menu lateral via Ingress.

## Instalação

1. No Home Assistant: **Configurações → Apps → Loja de apps → ⋮ → Repositórios**.
2. Adicione a URL deste repositório no GitHub.
3. Instale **Controle Financeiro** e clique em **Iniciar**. A imagem é construída no
   próprio Home Assistant, então a primeira instalação demora alguns minutos.
4. Abra **Finanças** no menu lateral. Pelo menu do HA o app abre sem pedir senha (dá para mudar na opção **Exigir login**).

## Publicando uma nova versão

1. Faça commit e push no repositório do programa.
2. Em `controle_financeiro/Dockerfile`, troque `APP_COMMIT` pelo novo commit.
3. Suba `version` em `controle_financeiro/config.yaml` e anote no `CHANGELOG.md`.
4. Faça push. O Home Assistant mostra a atualização disponível.

## Testando localmente

```bash
docker build -t controle-financeiro-ha controle_financeiro
```
