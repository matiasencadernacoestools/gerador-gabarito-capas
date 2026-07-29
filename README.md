# Gerador de Capas de Álbuns

Protótipo local em HTML, CSS e JavaScript puro.

## Como testar

1. Abra `index.html` num navegador moderno.
2. O tamanho inicial é **25 x 50**.
3. Escolha o tamanho nominal e a quantidade de lâminas.
4. Ative ou desative textos e cotas.
5. Exporte em PNG 300 dpi ou PSD 300 dpi com guias reais do Photoshop.

## Regras aplicadas

- Dorso = quantidade de lâminas × 0,1 cm
- Altura útil = altura real + 1 cm
- Largura útil = largura real + 2 cm + dorso
- Dobra superior/inferior = 2,25 cm
- Dobra esquerda/direita = 2 cm
- Lombadas = marcações a 2,5 cm das laterais do dorso
- As lombadas não alteram o tamanho final

## Observação

O projeto é autocontido e não depende de bibliotecas externas, o que facilita os testes locais e a publicação posterior no GitHub Pages.


## Tamanhos especiais

Os tamanhos especiais usam medidas fixas e ignoram o algoritmo padrão de lâminas.

- 10 x 30 (autocolante)
  - Total: 15,20 x 40,60 cm
  - Útil: 11,60 x 34,02 cm
  - Dorso: 1,50 cm
  - Lombadas: 1,50 cm
  - Dobras superior/inferior: 1,80 cm
  - Dobras esquerda/direita: 3,29 cm

- O PSD inclui guias externas nos quatro limites do tamanho total do documento.

- As guias externas usam os limites exatos do documento, evitando diferenças de um pixel nas medidas do Photoshop.
