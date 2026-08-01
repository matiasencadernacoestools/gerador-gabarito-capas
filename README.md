# Gerador de Capas — versão 2.10.16

## Correção

- Corrigidas as guias nativas do Photoshop no botão **BAIXAR PSD 300 DPI COM GUIAS E CAMADAS**.
- O novo exportador agora usa o mesmo conjunto completo de posições do botão tradicional:
  - limites externos;
  - dobras;
  - lombada do fundo;
  - início e fim do dorso;
  - lombada da frente.
- A camada rasterizada **GABARITO TÉCNICO** permanece separada e transparente.
- Nenhuma alteração foi feita na rotina do botão tradicional **BAIXAR PSD 300 DPI COM GUIAS**.
- Nenhuma alteração foi feita no cálculo visual das guias do sistema.

## Causa corrigida

A biblioteca `ag-psd` recebe as posições das guias em pixels e realiza internamente a conversão exigida pelo formato PSD. A versão anterior multiplicava novamente os valores por 32, colocando a maior parte das guias fora dos limites do documento.

## Arquivos a atualizar

- `index.html`
- `service-worker.js`
- `README.md`
