# Main — design reference

This is a design mockup created in a visual design tool (an appifact
design canvas), exported as a standalone page. Treat it as a REFERENCE
MOCKUP, not production code: the markup and inline styles carry the
design's precise values — colors, font sizes, spacing, radii, shadows,
layout — which an implementation should replicate faithfully in its own
components and styling system rather than copy wholesale.

## Contents

- `Main.dc.html` — the artboard (a Design Component: an `<x-dc>`
  template + a small logic class). The values to replicate live in its
  inline `style="…"` attributes and the `<helmet><style>` block.
- `tiago-uniforme-medalhas.jpg` — referenced resource
- `2018-entrevista-tv-robotica-1.jpg` — referenced resource
- `2018-entrevista-tv-robotica-2.jpg` — referenced resource
- `2018-premiacao-no-palco.jpg` — referenced resource
- `2019-arena-de-competicao.jpg` — referenced resource
- `2019-equipe-testando-robo.jpg` — referenced resource
- `2019-entrega-de-certificados-1.jpg` — referenced resource
- `2019-entrega-de-certificados-2.jpg` — referenced resource
- `2022-colegio-militar-campo-grande.jpg` — referenced resource
- `2022-competicao-1.jpg` — referenced resource
- `2022-competicao-2.jpg` — referenced resource
- `2022-competicao-3.jpg` — referenced resource
- `2022-competicao-4.jpg` — referenced resource
- `2022-apresentacao-em-auditorio.jpg` — referenced resource
- `2022-cerimonia-de-premiacao.jpg` — referenced resource
- `2023-ensinando-estudantes.jpg` — referenced resource
- `2018-evento-robotica-1.jpg` — referenced resource
- `2018-evento-robotica-2.jpg` — referenced resource
- `equipe-robotica-prototipos.jpg` — referenced resource
- `2022-delegacao-com-bandeira.jpg` — referenced resource
- `2023-sala-de-estudos.jpg` — referenced resource
- `2020-amigos.jpg` — referenced resource
- `pregando-na-praca.jpg` — referenced resource
- `2020-oracao-na-varanda.jpg` — referenced resource
- `2021-grupo-ao-ar-livre.jpg` — referenced resource
- `2023-intervalo-com-deus-1.jpg` — referenced resource
- `2023-sala-de-aula.jpg` — referenced resource
- `2023-colegas-1.jpg` — referenced resource
- `2023-colegas-2.jpg` — referenced resource
- `2023-intervalo-com-deus-2.jpg` — referenced resource
- `2023-intervalo-com-deus-3.jpg` — referenced resource
- `2023-intervalo-com-deus-4.jpg` — referenced resource
- `2023-intervalo-com-deus-5.jpg` — referenced resource
- `2023-intervalo-com-deus-6.jpg` — referenced resource
- `2023-intervalo-com-deus-7.jpg` — referenced resource
- `2023-intervalo-com-deus-8.jpg` — referenced resource
- `2023-intervalo-com-deus-9.jpg` — referenced resource
- `2022-orfanato-legiao-de-honra-1.jpg` — referenced resource
- `2022-orfanato-legiao-de-honra-2.jpg` — referenced resource
- `palacio-da-alvorada-equipe-do-ime.jpg` — referenced resource
- `cursinho-farias-brito-ime-ita.jpg` — referenced resource
- `residencia-ifce-1.svg` — referenced resource
- `residencia-ifce-2.svg` — referenced resource
- `residencia-ifce-3.svg` — referenced resource
- `2019-tela-programacao-do-robo.jpg` — referenced resource
- `despedida-do-laboratorio.jpg` — referenced resource
- `primeira-vez-vendendo-na-praia.jpg` — referenced resource
- `corrida-orientacao.jpg` — referenced resource
- `kung-fu-1.jpg` — referenced resource
- `supino.jpg` — referenced resource
- `medalhas-esporte.jpg` — referenced resource
- `support.js`, `vendor/react*.js` — the runtime that renders the
  component in a browser; not part of the design.

## Viewing

Serve the folder (e.g. `python3 -m http.server`) and open `Main.dc.html`;
some browsers block the scripts over file://.
