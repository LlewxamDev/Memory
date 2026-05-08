# Regras para recriar um video de referencia no Remotion

Use quando um video de referencia precisa virar uma composicao nova, mantendo audio sincronizado e ritmo visual parecido.

## Checklist obrigatorio

- Baseie a timeline em uma lista de cenas com `start` e `end` em segundos.
- Cada cena deve terminar exatamente no seu `end`.
- Nao deixe midia visual continuar depois do fim da cena.
- Quando o assunto da narracao mudar, troque tambem o visual.
- Mostre legenda durante todo o trecho falado, exceto quando a tipografia grande repete a mesma ideia.
- Use fallback visual se faltar imagem/video, mas evite congelar o mesmo frame por muito tempo.
- Se uma cena passar de 8s, divida em subcenas internas ou transforme em cenas menores.
- Valide gaps, overlaps e cenas longas demais antes de renderizar.
- Renderize uma previa curta de 30s para testar ritmo antes do video completo.
- Preserve o audio original sincronizado quando a referencia for o proprio conteudo-base.

## Padrao usado no estudo do 32Bits

- Cenas de ate 4s para manter movimento visual constante.
- Corte seco com snap zoom/glitch no inicio da propria cena, sem crossfade que prolongue a midia anterior.
- Stills extraidos do video a cada 4s, com Ken Burns lento.
- Legenda inferior central, branco pesado, sombra/contorno preto e base escura.
- Tipografia grande em viradas de assunto: gancho, problema, identidade, padroes, fontes, cores e checklist.
- Camada visual com saturacao alta, vinheta forte, halftone, grao e linhas de energia.
