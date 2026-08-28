# Romaneio Data Matrix Caminhão

PWA para controle de paletes com leitura de Data Matrix, inclusão em paletes fechados e geração de romaneio total ou por caminhão.

## Arquivos principais
- index.html
- inicio.html
- manifest.json
- service-worker.js
- version.json
- export-utils.js
- icon-192.png
- icon-512.png

## Romaneio por caminhão

Na aba **Romaneio por Caminhão**, informe a placa, selecione os paletes e gere o Excel exclusivo do veículo. O Excel do romaneio total também inclui a placa associada a cada palete.

## Atualização automática
Quando publicar nova versão, aumente a versão em `version.json`, em `APP_VERSION` no `index.html` e troque o `CACHE_NAME` no `service-worker.js`.
