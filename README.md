# meu-portfolio
Aula de CSS | Flexbox

## PRINCIPAIS PROPRIEDADES E VALORES DO FLEX-CONTAINER

-- display: flex; (define o flex-container)

-- flex-direction: row / row-reverse / column / column-reverse; (direção)

-- flex-wrap: wrap / nowrap / wrap-reverse; (quebra da linha ou coluna)

-- flex-flow: flex-direction + flex-wrap

-- justify-content (acompanha eixo do flex-direction)
  flex-start (alinha no início*)
  flex-end (alinha no final*)
  space-around (espalha de modo centralizado, tendo as extremidades menores)
  space-evenly (espalha de modo centralizado, tendo todos espaçamento iguais)
  space-between (espalha de modo centralizado, colando as extremidades)
  *Observação: início e final dependem do flex-direction, não podemos associá-los à direta, esquerda nem topo nem bottom.*

-- align-items: alinha os itens no eixo perpendicular ou transversal ao eixo do flex-direction
   flex-start / flex-end / center / stretch