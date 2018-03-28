# ISO-Breaker

https://muxidev.github.io/iso_breaker/

### Sobre
Ferramenta que facilita a abertura manual de uma ISO8583 a partir de um empacotador fornecido.

Use a planilha https://docs.google.com/spreadsheets/d/1OZhJ7eQVayX1PbC6F5Wm_Q4YP1Hx9_E4lJUsivQwWHc/edit#gid=0 para preencher as configurações do ISO Breaker

### Libraries
- [vue.js](https://github.com/vuejs/vue)
- [Bootstrap](https://github.com/twbs/bootstrap)
- [js-xlsx](https://github.com/sheetjs/js-xlsx)

### Release notes
- 1.05 Externaliza configurações de adquirentes
- 1.04 Exibe tamanho ao passar o mouse em cima de um valor
- 1.03 Adiciona opção de limpar só o histórico e corrige problema ao carregar histórico
- 1.02 Adiciona opção de Detalhes dos Campos
- 1.01 Adiciona histórico de ISOs
- 1.00 Refaz código com novo layout e usando Vue.js framework
- 0.15 Adiciona seleção de empacotador pre-loadeds
- 0.14 Correção de bug ao abrir log do VX680, correção de bug ao abrir log com tabs, correção de bitmap com IFA e outras melhorias de código
- 0.13 Correção de bug, adição de favicon, bitmap com tamanho fixo de caracteres e data formatada no bit12
- 0.12 Correção de bug da variavel "somador" no empacotador do muxiPAY, adição de "Não possui" no select do TPDU e melhorias de layout
- 0.11 Adição do tipo de subcampo do muxiPAY, ordenação dos subcampos do empacotador e correção de bugs
- 0.10 Correção do contador de Ls do separador (whitespace) dos subcampos que tava hardcoded e adição de seletor de tipo de subcampos
- 0.09 Adição do Tamanho HEX no localStorage, correção de bug nos LLNUM e adição de TPDU tamanho 2 bytes
- 0.08 Correção de bug e novo layout do resultado da ISO aberta
- 0.07 Correção do bug que não exibia os subcampos corretamente e adição do botão que apaga os dados do localStorage
- 0.06 Utilização do localStorage para persistir dados inseridos nas textareas e select do TPDU
- 0.05 Exibição dos Subcampos (quando declarados no empacotador)
- 0.04 Inclusão do Bitmap extendido e ajustes do código
- 0.03 Adaptação do layout para comportar outros projetos
- 0.02 Leitura do empacotador e ajustes do código
- 0.01 Primeiro release