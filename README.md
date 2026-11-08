# ValveFlow Sim

**Versão:** v0.0.1  
**Estado:** protótipo de modelagem e simulação visual 3D.

O **ValveFlow Sim** reúne visualização 3D de válvulas e bombas centrífugas, criação livre de tubulações e animação ilustrativa do escoamento em sistemas modelados.

## Executar

1. Abra o arquivo `index.html` em um navegador moderno com WebGL.
2. Use **Simulações** para explorar os componentes, fluidos, parâmetros e animações disponíveis.
3. Use **Modelagem** para criar tubulações e inserir bombas.
4. No ambiente Modelagem, utilize **Criar simulação**, selecione o fluido e os elementos desejados e pressione **Simular**.

> Algumas bibliotecas e fontes são carregadas por CDN; é necessária uma conexão com a internet para a interface carregar completamente.

## Conteúdo

- `index.html` — aplicação web em arquivo HTML único (código da última versão de trabalho, V15).
- `VERSION` — identificador da versão.
- `CHANGELOG.md` — histórico inicial.

## Escopo e limites

O escoamento, a cavitação e a animação do rotor são demonstrações visuais com cálculos simplificados. **O projeto ainda não realiza análise CFD multifásica validada**, nem dimensionamento normativo de flanges, bombas e tubulações. Verifique os modelos antes de qualquer aplicação de engenharia.

## Publicação

O projeto foi preparado com o commit inicial na branch `main` e a tag Git anotada `v0.0.1`. Repositório oficial: https://github.com/Carlosgmorais/Valve-Flow_Sim