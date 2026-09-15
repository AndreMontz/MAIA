# Cartografia do Centro de Piracicaba

centro-network.json contém um recorte derivado do OpenStreetMap, obtido em
15/09/2026: 1316 nós e 276 vias. Recorte de consulta:
-47.657,-22.734,-47.640,-22.718 (oeste, sul, leste, norte).
As vias completas podem ultrapassar o recorte.

Fonte: https://api.openstreetmap.org/api/0.6/map?bbox=-47.657,-22.734,-47.640,-22.718

© OpenStreetMap contributors. Dados sob Open Database License (ODbL):
https://www.openstreetmap.org/copyright e https://opendatacommons.org/licenses/odbl/1-0/

O extrator software/scripts/prepare-map.py remove metadados de contribuidores e
seleciona vias caminháveis. Para atualizar, baixe o XML para o caminho de entrada
temporário de sua escolha e execute python software/scripts/prepare-map.py entrada.xml software/frontend/public/geo/centro-network.json e remova o XML intermediário antes de publicar.
Mantenha fonte, data e atribuição. Este recorte não verifica acessibilidade
de calçadas, sentidos de circulação ou condições atuais.

Referências de coordenadas da Prefeitura:
https://piracicaba.sp.gov.br/wp-content/uploads/2025/08/Lista-PQM-Piracicaba-lat-e-long-google-maps.pdf

Todas as ocorrências SIM-PIRA são inventadas, independentes dos dados cartográficos.
Os tiles online seguem https://operations.osmfoundation.org/policies/tiles/ .

