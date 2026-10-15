# https://developers.home-assistant.io/docs/apps/configuration#app-dockerfile
FROM ghcr.io/home-assistant/base:3.23

# Commit do repositório do programa que esta versão do app instala.
# Para atualizar: troque o commit, suba "version" no config.yaml e registre no CHANGELOG.
ARG APP_REPO=https://github.com/diogocaseca/controle-financeiro
ARG APP_COMMIT=caac88b21fe35326511202d3fe77f89a6b028152

RUN \
    apk add --no-cache python3 tzdata \
    && python3 -m venv /opt/venv \
    && /opt/venv/bin/pip install --no-cache-dir "${APP_REPO}/archive/${APP_COMMIT}.tar.gz"

COPY rootfs /

LABEL \
    io.hass.type="app" \
    org.opencontainers.image.title="Home Assistant App: Controle Financeiro" \
    org.opencontainers.image.source="https://github.com/diogocaseca/controle-financeiro"
