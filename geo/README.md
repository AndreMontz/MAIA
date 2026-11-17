# Cartografia de Piracicaba

piracicaba-network.json contém um recorte derivado do OpenStreetMap (Centro e
bairros vizinhos), obtido em 29/10/2026 em quatro blocos da API do OSM:
-47.667,-22.742,-47.630,-22.710 (oeste, sul, leste, norte).
As vias completas podem ultrapassar o recorte.

Fonte: https://api.openstreetmap.org/api/0.6/map?bbox=...

© OpenStreetMap contributors. Dados sob Open Database License (ODbL):
https://www.openstreetmap.org/copyright e https://opendatacommons.org/licenses/odbl/1-0/

O extrator software/scripts/prepare-map.py remove metadados de contribuidores,
seleciona vias caminháveis, travessias, semáforos e locais com nome. Para
atualizar, baixe os XML para um caminho temporário e execute
python software/scripts/prepare-map.py bloco1.osm [bloco2.osm ...] software/frontend/public/geo/piracicaba-network.json
e remova os XML intermediários antes de publicar.
Mantenha fonte, data e atribuição. Este recorte não verifica acessibilidade
de calçadas, sentidos de circulação ou condições atuais: as calçadas são inferidas.

Os exemplos simulados do mapa (identificadores SIM-) são inventados e
independentes dos dados cartográficos.
Os tiles online seguem https://operations.osmfoundation.org/policies/tiles/ .
