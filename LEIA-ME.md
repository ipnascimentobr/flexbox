# Páginas de streaming para estudo de CSS

## Como abrir
Extraia o ZIP inteiro. Abra flexbox-netflix/index.html ou grid-prime/index.html no navegador. Mantenha a pasta assets no local original. As fotos estão incluídas: as páginas funcionam sem internet.

## Conteúdo
- Flexbox, inspirado no estilo da Netflix: navegação e ações flexíveis, faixas de cards com rolagem horizontal.
- CSS Grid, inspirado no estilo do Prime Video: cabeçalho com áreas, destaque e catálogo em colunas responsivas.
- Nenhum framework, biblioteca, JavaScript, fonte remota ou CSS inline.
- Links navegam para as seções e para os títulos. Os elementos details e summary abrem sinopses pelo próprio HTML. Não há reprodução de filmes, login ou serviço de streaming.

## Experimentos para a aula
### Flexbox
1. No DevTools, mude flex-direction de row para column na .actions.
2. Troque justify-content em .section-heading e observe o alinhamento.
3. Ative flex-wrap: wrap na .catalog e retire overflow-x. Compare o resultado.
4. Troque flex: 0 0 230px por flex: 1 1 230px. Explique o efeito na última linha.
5. Observe o margin-left: auto do perfil e a regra de responsividade do menu.
### CSS Grid
1. Troque as colunas da .catalog por repeat(3, minmax(0, 1fr)).
2. Experimente 1fr 2fr e compare a largura das colunas.
3. Modifique 230px no minmax e identifique quando a quantidade de colunas muda.
4. Compare auto-fit com auto-fill utilizando poucos cards.
5. Observe grid-template-areas no cabeçalho em telas menores.

## Referências
Netflix: https://www.netflix.com/br/
Prime Video: https://www.primevideo.com/
MDN Flexbox: https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout/Basic_concepts
MDN CSS Grid: https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Grid_layout/Basic_concepts
Consulta em 05/10/2026. As referências orientam o estilo visual. As páginas usam marcas didáticas e títulos fictícios.

## Fotografias
Unsplash. Fotografias servem como ilustrações do catálogo fictício, sem associação com filmes reais.
Cinema: https://images.unsplash.com/photo-1440404653325-ab127d49abc1
Céu noturno, Taylor R: https://unsplash.com/photos/0fVGEcXqCBM
Cidade, Samuel Hagger: https://unsplash.com/photos/oLOrBZGLf1w
Montanha: https://images.unsplash.com/photo-1749548538343-218ff54b59cb
Floresta: https://images.unsplash.com/photo-1473448912268-2022ce9509d8
Lago: https://images.unsplash.com/photo-1501785888041-af3ef285b470
Deserto: https://images.unsplash.com/photo-1509316785289-025f5b846b35
Oceano: https://images.unsplash.com/photo-1518837695005-2083093ee35b
Licença: https://unsplash.com/license
