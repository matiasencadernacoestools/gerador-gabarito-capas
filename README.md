# Gerador de Capas — versão 2.10.20

## Correção de centralização e snap

Os botões de centralização horizontal e as guias magnéticas agora usam os mesmos eixos corrigidos do gabarito:

- **Fundo:** centro entre a borda útil esquerda e a lombada do fundo.
- **Frente:** centro entre a lombada da frente e a borda útil direita.

A correção funciona para:

- textos;
- imagens;
- botão **Centralizar horizontalmente**;
- movimentação com snap;
- seleção múltipla movimentada com snap.

A tecla `Alt` continua permitindo movimentação livre, ignorando o snap.

Não foram alteradas:

- guias nativas do Photoshop;
- cálculos do dorso;
- dobras;
- lombadas;
- exportações PNG;
- rotinas PSD.

## Arquivos para atualizar no GitHub

- `index.html`
- `service-worker.js`
- `README.md`
