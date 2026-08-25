# EPT em números

Apresentação sobre a educação profissional técnica de nível médio no Brasil,
a partir dos microdados do Censo Escolar da Educação Básica (INEP), 2007–2025.

Página única, autocontida: os dados estão embutidos no próprio `index.html`.
Sem dependências externas, sem build.

## Conteúdo

14 slides cobrindo composição por forma de oferta, por área e por curso;
relação com o ensino médio; e variação da série histórica — no Brasil e nas 27 UFs.

## Fonte e método

- INEP, Censo Escolar da Educação Básica, microdados 2007–2025
- INEP, Suplemento de Cursos Técnicos, 2023–2025
- Variável de EPT: `QT_MAT_PROF_TEC`; ensino médio: `QT_MAT_MED`
- Filtro: `TP_SITUACAO_FUNCIONAMENTO = 1` (escolas em atividade); campos vazios tratados como zero
- Em 2025 a UF vem de `Tabela_Escola`, unida a `Tabela_Matricula` por `CO_ENTIDADE`
- Validação: os cinco componentes de 2024 somam 2.389.454 — o total dos microdados e da Sinopse Estatística 1.30

As ressalvas metodológicas estão no slide 13 da própria apresentação.
