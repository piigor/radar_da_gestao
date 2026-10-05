---
id: diagnóstico-executivo-vivacasa
title: "Diagnóstico Executivo VivaCasa"
type: Saída
namespace: vivacasa
lifecycle_state: research
summary: "Diagnóstico executivo fictício da VivaCasa para Q4 2026, com análise de receita, margem, ruptura, marketing, hipóteses, riscos, recomendacoes e plano de ação."
confidence: 0.76
retrieval_class: normal
export_class: private
created: 2026-09-10
aliases: [diagnóstico-executivo-vivacasa]
lineage:
  - "intake/processed/analise-completa-do-intake.md"
  - "data/indicadores/"
  - "knowledge/vivacasa/"
  - "projects/diagnostico-vivacasa-q4-2026/PLAN.md"
edges:
  - target: "[[análise-completa-do-intake-vivacasa]]"
    relation: "derived_from"
    confidence: 0.92
  - target: "[[problemas-estrategicos-q4-2026]]"
    relation: "derived_from"
    confidence: 0.86
  - target: "[[hipóteses-de-diagnóstico-vivacasa]]"
    relation: "informed_by"
    confidence: 0.82
  - target: "[[projeto-vivacasa-diagnóstico-q4-2026]]"
    relation: "supports"
    confidence: 0.8
---

# Diagnóstico Executivo VivaCasa

## 1. Aviso Sobre os Dados

Este diagnóstico usa dados fictícios e demonstrativos. Ele nao deve ser usado para decisao real sem validação humana, financeira, operacional e de fonte de dados.

- Tipo: Fato.
- Confiança: alta, 0,90.
- Fontes: `intake/processed/analise-completa-do-intake.md`, `knowledge/vivacasa/INDEX.md`, `projects/diagnostico-vivacasa-q4-2026/PLAN.md`.

## 2. Resumo Executivo

A VivaCasa aparece como uma varejista omnicanal fictícia com 12 lojas fisicas, comercio eletronico proprio e marketplaces selecionados. O diagnóstico indica uma combinação de quatro problemas: receita abaixo da meta, margem de contribuicao abaixo da meta, ruptura crescente e queda de conversão em canais pagos mesmo com aumento de investimento.

- Tipo: Fato observado.
- Confiança: media-alta, 0,78.
- Fontes: `intake/processed/analise-completa-do-intake.md`, `knowledge/vivacasa/concepts/modelo-de-negocio-vivacasa.md`, `knowledge/vivacasa/concepts/problemas-estrategicos-q4-2026.md`, `projects/diagnostico-vivacasa-q4-2026/PLAN.md`.

A causa mais provavel, ainda como hipótese, e que o crescimento esta limitado por desalinhamento entre demanda, disponibilidade, mix e margem. Midia paga pode estar levando trafego para produtos ou categorias sem disponibilidade ou contribuicao suficiente.

- Tipo: Hipótese.
- Confiança: media, 0,68.
- Fontes: `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`, `intake/processed/analise-completa-do-intake.md`.

Recomenda-se priorizar validação de formulas, reconciliação de fontes, controle de ruptura e leitura conjunta de campanhas, estoque e margem antes de ampliar midia ou descontos.

- Tipo: Recomendação.
- Confiança: media-alta, 0,76.
- Fontes: `intake/processed/analise-completa-do-intake.md`, `data/indicadores/margem-contribuicao.md`, `data/indicadores/ruptura.md`, `data/indicadores/cac-por-canal.md`.

## 3. Situação Atual

- Tipo: Fato. A empresa e descrita como varejista omnicanal de utilidades domesticas, organização, decoração acessivel e pequenos móveis. Confiança: 0,74. Fonte: `knowledge/vivacasa/concepts/modelo-de-negocio-vivacasa.md`.
- Tipo: Fato. O projeto deve analisar janeiro a agosto de 2026 contra o mesmo periodo de 2025, com foco em crescimento rentavel, margem, estoque, conversão e canal. Confiança: 0,78. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Fato. O projeto tem como objetivo identificar causas provaveis, validar indicadores e recomendar plano de ação de 90 dias. Confiança: 0,80. Fonte: `projects/diagnostico-vivacasa-q4-2026/PLAN.md`.
- Tipo: Fato. A diretoria nao possui visao integrada para decidir onde investir. Confiança: 0,76. Fonte: `projects/diagnostico-vivacasa-q4-2026/PLAN.md` e `knowledge/vivacasa/concepts/problemas-estrategicos-q4-2026.md`.

## 4. Análise de Receita Versus Meta

Receita liquida acumulada de janeiro a agosto de 2026:

```text
1.240.000 + 1.260.000 + 1.300.000 + 1.320.000 + 1.350.000 + 1.330.000 + 1.380.000 + 1.370.000
= R$ 10.550.000
```

Meta acumulada de janeiro a agosto de 2026:

```text
1.320.000 + 1.340.000 + 1.370.000 + 1.400.000 + 1.430.000 + 1.450.000 + 1.480.000 + 1.500.000
= R$ 11.290.000
```

Gap absoluto:

```text
R$ 10.550.000 - R$ 11.290.000 = -R$ 740.000
```

Gap percentual sobre a meta:

```text
-R$ 740.000 / R$ 11.290.000 = -6,55%
```

- Tipo: Fato calculado. A receita ficou R$ 740.000 abaixo da meta, ou 6,55% abaixo da meta acumulada. Confiança: 0,90. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Fato observado. A receita ficou abaixo da meta em todos os meses de janeiro a agosto de 2026. Confiança: 0,88. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Limitação. O indicador de receita liquida ainda exige confirmação de tratamento de frete, impostos e comissoes entre canais. Confiança: 0,75. Fonte: `data/indicadores/receita-liquida.md`.

## 5. Análise de Margem

Margem media simples de contribuicao:

```text
(30,4% + 30,1% + 29,8% + 30,2% + 30,5% + 30,7% + 30,6% + 30,9%) / 8
= 30,40%
```

Margem media ponderada por receita:

```text
soma de margem mensal x receita mensal / R$ 10.550.000
= 30,41%
```

- Tipo: Fato calculado. A margem media simples foi 30,40% e a ponderada foi 30,41%. Confiança: 0,88. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Fato observado. A margem de contribuicao mensal ficou abaixo da meta fictícia de 32% em todos os meses analisados. Confiança: 0,86. Fonte: `intake/processed/analise-completa-do-intake.md` e `data/indicadores/margem-contribuicao.md`.
- Tipo: Hipótese. Descontos, comissoes e midia podem estar reduzindo contribuicao em alguns canais. Confiança: 0,68. Fonte: `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`.
- Tipo: Recomendação. Validar a formula de margem de contribuicao antes de comparar canais, categorias ou campanhas. Confiança: 0,82. Fonte: `data/indicadores/margem-contribuicao.md` e `intake/processed/analise-completa-do-intake.md`.

## 6. Análise de Estoque e Ruptura

| Categoria | Ruptura jan | Ruptura ago | Variação | Confiança | Fonte |
|---|---:|---:|---:|---:|---|
| Organização | 8,2% | 11,8% | +3,6 p.p., +43,90% | 0,86 | `intake/processed/analise-completa-do-intake.md` |
| Cozinha e mesa | 7,1% | 10,3% | +3,2 p.p., +45,07% | 0,86 | `intake/processed/analise-completa-do-intake.md` |
| Decoração | 6,4% | 9,1% | +2,7 p.p., +42,19% | 0,86 | `intake/processed/analise-completa-do-intake.md` |
| Banheiro e lavanderia | 5,8% | 8,6% | +2,8 p.p., +48,28% | 0,86 | `intake/processed/analise-completa-do-intake.md` |
| Pequenos móveis | 4,9% | 7,8% | +2,9 p.p., +59,18% | 0,86 | `intake/processed/analise-completa-do-intake.md` |

- Tipo: Fato observado. A ruptura aumentou em todas as categorias analisadas. Confiança: 0,86. Fonte: `intake/processed/analise-completa-do-intake.md` e `knowledge/vivacasa/concepts/problemas-estrategicos-q4-2026.md`.
- Tipo: Hipótese. Rupturas de estoque podem estar prejudicando a conversão de itens de maior margem. Confiança: 0,68. Fonte: `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`.
- Tipo: Recomendação. Criar lista semanal de SKUs prioritarios em risco de ruptura e separar ruptura real de erro de cadastro, estoque reservado e atraso de integração. Confiança: 0,80. Fonte: `data/indicadores/ruptura.md`, `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`.

## 7. Análise de Marketing, Conversão e CAC

| Canal | Investimento jan | Investimento ago | Variação investimento | Conversão jan | Conversão ago | Variação conversão | CAC ago | Fonte |
|---|---:|---:|---:|---:|---:|---:|---:|---|
| Busca paga | R$ 82.000 | R$ 108.000 | +R$ 26.000, +31,71% | 2,8% | 2,5% | -0,3 p.p., -10,71% | R$ 45,19 | `intake/processed/analise-completa-do-intake.md` |
| Social paga | R$ 76.000 | R$ 99.000 | +R$ 23.000, +30,26% | 2,1% | 1,9% | -0,2 p.p., -9,52% | R$ 52,38 | `intake/processed/analise-completa-do-intake.md` |
| E-mail | R$ 18.000 | R$ 22.000 | +R$ 4.000, +22,22% | 7,1% | 7,8% | +0,7 p.p., +9,86% | R$ 18,44 | `intake/processed/analise-completa-do-intake.md` |
| WhatsApp autorizado | R$ 9.000 | R$ 14.000 | +R$ 5.000, +55,56% | 8,4% | 9,1% | +0,7 p.p., +8,33% | R$ 12,75 | `intake/processed/analise-completa-do-intake.md` |
| Organico | R$ 0 | R$ 0 | R$ 0, percentual nao aplicavel | 3,5% | 3,8% | +0,3 p.p., +8,57% | R$ 0,00 | `intake/processed/analise-completa-do-intake.md` |

- Tipo: Fato observado. Busca paga e social paga tiveram mais investimento e menor conversão de janeiro para agosto. Confiança: 0,86. Fonte: `intake/processed/analise-completa-do-intake.md`, `knowledge/vivacasa/concepts/canais-e-segmentos-vivacasa.md`.
- Tipo: Fato observado. E-mail e WhatsApp autorizado tiveram CAC menor e conversão superior aos canais pagos. Confiança: 0,80. Fonte: `intake/processed/recibo-processamento-diagnostico.md` e `intake/processed/analise-completa-do-intake.md`.
- Tipo: Limitação. O CAC informado nao pode ser recalculado de forma independente porque faltam clientes novos atribuidos por canal no arquivo de marketing processado. Confiança: 0,82. Fonte: `knowledge/vivacasa/concepts/canais-e-segmentos-vivacasa.md`, `data/indicadores/cac-por-canal.md`.
- Tipo: Recomendação. Nao ampliar midia paga antes de validar estoque dos produtos promovidos e separar receita atribuida de receita incremental. Confiança: 0,82. Fonte: `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`, `intake/processed/analise-completa-do-intake.md`.

## 8. Sinais da Pesquisa de Clientes

| Sinal | Resultado | Tipo | Confiança | Fonte |
|---|---:|---|---:|---|
| Encontrou o produto desejado | 78% | Fato observado | 0,74 | `intake/processed/analise-completa-do-intake.md` |
| Considerou o preco adequado | 71% | Fato observado | 0,74 | `intake/processed/analise-completa-do-intake.md` |
| Recomendaria a VivaCasa | 74% | Fato observado | 0,74 | `intake/processed/analise-completa-do-intake.md` |
| Relatou produto indisponivel | 19% | Fato observado | 0,76 | `intake/processed/analise-completa-do-intake.md` |
| Considerou a retirada em loja conveniente | 83% | Fato observado | 0,74 | `intake/processed/analise-completa-do-intake.md` |
| Avaliou positivamente a organização das lojas | 81% | Fato observado | 0,74 | `intake/processed/analise-completa-do-intake.md` |

- Tipo: Limitação. A pesquisa nao e probabilistica e seus resultados sao sinais para investigação, nao prova causal. Confiança: 0,84. Fonte: `intake/processed/analise-completa-do-intake.md`, `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`.
- Tipo: Hipótese. O relato de indisponibilidade reforca a necessidade de investigar ruptura, mas nao prova que ruptura causou queda de conversão. Confiança: 0,66. Fonte: `intake/processed/analise-completa-do-intake.md`.

## 9. Fatos Observados

- Tipo: Fato. Receita acumulada jan-ago 2026 de R$ 10.550.000 contra meta de R$ 11.290.000. Confiança: 0,90. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Fato. Gap acumulado de -R$ 740.000, ou -6,55% contra a meta. Confiança: 0,90. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Fato. Margem media simples de contribuicao de 30,40%, abaixo da meta fictícia de 32%. Confiança: 0,88. Fonte: `intake/processed/analise-completa-do-intake.md`, `data/indicadores/margem-contribuicao.md`.
- Tipo: Fato. Ruptura cresceu em todas as categorias analisadas. Confiança: 0,86. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Fato. Busca paga e social paga pioraram conversão mesmo com aumento de investimento. Confiança: 0,86. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Fato. A diretoria decidiu nao ampliar midia paga antes de validar estoque dos produtos promovidos. Confiança: 0,82. Fonte: `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`.

## 10. Hipóteses

- Tipo: Hipótese. A demanda paga pode estar sendo enviada para produtos com disponibilidade insuficiente. Confiança: 0,68. Fonte: `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`.
- Tipo: Hipótese. Ruptura pode estar prejudicando conversão em itens de maior margem. Confiança: 0,68. Fonte: `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`.
- Tipo: Hipótese. Mix concentrado em itens de baixo ticket pode limitar crescimento de margem. Confiança: 0,66. Fonte: `knowledge/vivacasa/concepts/modelo-de-negocio-vivacasa.md`.
- Tipo: Hipótese. Descontos, comissoes e midia podem estar reduzindo contribuicao em alguns canais. Confiança: 0,68. Fonte: `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`.

## 11. Causas Provaveis

- Tipo: Hipótese de causa provavel. Desalinhamento entre campanhas, disponibilidade e estoque promocionado pode explicar parte da queda de conversão paga. Confiança: 0,67. Fonte: `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`, `knowledge/vivacasa/concepts/problemas-estrategicos-q4-2026.md`.
- Tipo: Hipótese de causa provavel. Margem abaixo da meta pode estar ligada a custos variaveis, descontos, comissoes, frete variavel ou midia atribuida, mas a formula ainda e provisoria. Confiança: 0,64. Fonte: `data/indicadores/margem-contribuicao.md`, `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`.
- Tipo: Hipótese de causa provavel. Falta de painel unico e definicoes comuns pode estar gerando decisoes fragmentadas entre comercial, operações e financeiro. Confiança: 0,70. Fonte: `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`, `projects/diagnostico-vivacasa-q4-2026/PLAN.md`.

## 12. Riscos

- Tipo: Risco. Crescer receita por descontos que destruam margem. Confiança: 0,80. Fonte: `intake/processed/analise-completa-do-intake.md`, `projects/diagnostico-vivacasa-q4-2026/PLAN.md`.
- Tipo: Risco. Ampliar midia antes de corrigir disponibilidade, mix e estoque. Confiança: 0,82. Fonte: `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`, `intake/processed/analise-completa-do-intake.md`.
- Tipo: Risco. Usar indicadores com formulas diferentes entre areas. Confiança: 0,82. Fonte: `intake/processed/analise-completa-do-intake.md`, `data/indicadores/`.
- Tipo: Risco. Confundir receita atribuida com receita incremental. Confiança: 0,80. Fonte: `projects/diagnostico-vivacasa-q4-2026/PLAN.md`, `intake/processed/analise-completa-do-intake.md`.
- Tipo: Risco. Confundir ruptura real com falha de cadastro, estoque reservado ou atraso de integração. Confiança: 0,78. Fonte: `data/indicadores/ruptura.md`, `projects/diagnostico-vivacasa-q4-2026/PLAN.md`.

## 13. Recomendacoes Priorizadas

1. Tipo: Recomendação. Validar formulas de receita liquida, margem, ruptura, conversão e CAC antes de qualquer decisao de orcamento. Confiança: 0,86. Fonte: `data/indicadores/`, `intake/processed/analise-completa-do-intake.md`.
2. Tipo: Recomendação. Bloquear aumento de midia paga ate validar disponibilidade dos produtos promovidos. Confiança: 0,84. Fonte: `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`.
3. Tipo: Recomendação. Criar lista semanal de SKUs prioritarios em risco de ruptura, ligada a venda, margem e campanha. Confiança: 0,80. Fonte: `data/indicadores/ruptura.md`, `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`.
4. Tipo: Recomendação. Separar receita atribuida de receita incremental nos canais de marketing. Confiança: 0,80. Fonte: `intake/processed/analise-completa-do-intake.md`, `projects/diagnostico-vivacasa-q4-2026/PLAN.md`.
5. Tipo: Recomendação. Usar e-mail e WhatsApp autorizado como canais a investigar para eficiencia, sem concluir escala ate validar atribuicao e capacidade operacional. Confiança: 0,70. Fonte: `intake/processed/analise-completa-do-intake.md`, `knowledge/vivacasa/concepts/canais-e-segmentos-vivacasa.md`.

## 14. Plano de Ação de 90 Dias

| Horizonte | Ação | Tipo | Dono sugerido pela fonte | Indicador | Confiança | Fonte |
|---|---|---|---|---|---:|---|
| Dias 1 a 15 | Validar formulas de receita liquida, margem, ruptura, conversão e CAC | Recomendação | Financeiro, comercial, marketing e operações | Definicoes aprovadas | 0,84 | `data/indicadores/`, `projects/diagnostico-vivacasa-q4-2026/PLAN.md` |
| Dias 1 a 15 | Corrigir divergencia numerica do recibo anterior antes de usar em apresentação | Recomendação | Consultoria e financeiro | Receita, meta e gap corretos | 0,90 | `intake/processed/analise-completa-do-intake.md` |
| Dias 16 a 30 | Montar painel inicial com receita, meta, margem, ruptura, conversão e CAC, marcando fonte e status de validação | Recomendação | Consultoria com areas | Dashboard simples | 0,80 | `projects/diagnostico-vivacasa-q4-2026/PLAN.md`, `intake/processed/analise-completa-do-intake.md` |
| Dias 16 a 30 | Criar rotina semanal de SKUs prioritarios em risco de ruptura | Recomendação | Operações | Ruptura semanal | 0,80 | `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`, `data/indicadores/ruptura.md` |
| Dias 31 a 60 | Cruzar campanhas pagas com disponibilidade e margem dos produtos promovidos | Recomendação | Marketing, comercial e operações | Conversão, CAC e ruptura | 0,78 | `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`, `data/indicadores/cac-por-canal.md` |
| Dias 31 a 60 | Definir categorias prioritarias considerando receita, margem e ruptura | Recomendação | Comercial e operações | Margem por categoria e ruptura | 0,72 | `knowledge/vivacasa/concepts/modelo-de-negocio-vivacasa.md`, `intake/processed/analise-completa-do-intake.md` |
| Dias 61 a 90 | Formalizar cadencia mensal executiva com donos por indicador | Recomendação | Diretoria e areas | Revisao mensal executiva | 0,76 | `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md` |
| Dias 61 a 90 | Revisar politica de descontos por categoria com base em margem validada | Recomendação | Financeiro e comercial | Margem de contribuicao | 0,74 | `data/indicadores/margem-contribuicao.md`, `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md` |

## 15. Decisoes Solicitadas a Diretoria

- Tipo: Decisao solicitada. Aprovar definicoes oficiais de receita liquida e margem de contribuicao. Confiança: 0,84. Fonte: `projects/diagnostico-vivacasa-q4-2026/PLAN.md`, `data/indicadores/receita-liquida.md`, `data/indicadores/margem-contribuicao.md`.
- Tipo: Decisao solicitada. Aprovar SKUs prioritarios e criterio de ruptura monitorada. Confiança: 0,80. Fonte: `projects/diagnostico-vivacasa-q4-2026/PLAN.md`, `data/indicadores/ruptura.md`.
- Tipo: Decisao solicitada. Definir limite de midia antes da correcao de estoque. Confiança: 0,82. Fonte: `projects/diagnostico-vivacasa-q4-2026/PLAN.md`, `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`.
- Tipo: Decisao solicitada. Nomear responsaveis pelo plano de 90 dias. Confiança: 0,80. Fonte: `projects/diagnostico-vivacasa-q4-2026/PLAN.md`.
- Tipo: Decisao solicitada. Definir limite de desconto por categoria. Confiança: 0,74. Fonte: `knowledge/vivacasa/concepts/modelo-de-negocio-vivacasa.md`, `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`.

## 16. Perguntas em Aberto

- Tipo: Pergunta. Qual e a margem por categoria e canal? Confiança: 0,86. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Pergunta. Qual e a taxa de conversão por loja e no comercio eletronico? Confiança: 0,84. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Pergunta. Qual e o custo de aquisicao por canal depois de considerar devolucoes? Confiança: 0,84. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Pergunta. Como receita liquida deve tratar devolucoes, cancelamentos, descontos, frete, impostos e comissoes? Confiança: 0,84. Fonte: `intake/processed/analise-completa-do-intake.md`, `data/indicadores/receita-liquida.md`.
- Tipo: Pergunta. Como separar ruptura real de falha de cadastro, estoque reservado e atraso de integração? Confiança: 0,82. Fonte: `data/indicadores/ruptura.md`.
- Tipo: Pergunta. Qual receita atribuida por canal e incremental, e qual apenas atribuida por modelo de marketing? Confiança: 0,80. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Pergunta. Quem sera dono de cada indicador executivo apos o diagnóstico? Confiança: 0,76. Fonte: `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`.

## 17. Limitacoes

- Tipo: Limitação. Todos os dados sao fictícios e demonstrativos. Confiança: 0,90. Fonte: `intake/processed/analise-completa-do-intake.md`, `knowledge/vivacasa/INDEX.md`.
- Tipo: Limitação. O recibo processado anterior contem numeros divergentes dos calculos do CSV de vendas, por isso este diagnóstico usa os numeros corrigidos da análise completa. Confiança: 0,90. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Limitação. O CAC nao pode ser auditado integralmente porque faltam clientes novos atribuidos por canal. Confiança: 0,82. Fonte: `knowledge/vivacasa/concepts/canais-e-segmentos-vivacasa.md`, `data/indicadores/cac-por-canal.md`.
- Tipo: Limitação. A pesquisa de clientes nao e probabilistica e nao prova causalidade. Confiança: 0,84. Fonte: `intake/processed/analise-completa-do-intake.md`.
- Tipo: Limitação. Nao ha margem por SKU, canal e categoria nos arquivos usados. Confiança: 0,82. Fonte: `knowledge/vivacasa/concepts/problemas-estrategicos-q4-2026.md`.
- Tipo: Limitação. O namespace VivaCasa esta em `research` e nao deve ser lido como canon aprovado. Confiança: 0,82. Fonte: `knowledge/vivacasa/canon/core-doctrine.md`, `knowledge/vivacasa/INDEX.md`.

## 18. Fontes Utilizadas

- `intake/processed/analise-completa-do-intake.md`
- `intake/processed/recibo-processamento-diagnostico.md`
- `data/indicadores/receita-liquida.md`
- `data/indicadores/margem-contribuicao.md`
- `data/indicadores/ruptura.md`
- `data/indicadores/conversao.md`
- `data/indicadores/cac-por-canal.md`
- `knowledge/vivacasa/INDEX.md`
- `knowledge/vivacasa/canon/core-doctrine.md`
- `knowledge/vivacasa/concepts/modelo-de-negocio-vivacasa.md`
- `knowledge/vivacasa/concepts/canais-e-segmentos-vivacasa.md`
- `knowledge/vivacasa/concepts/problemas-estrategicos-q4-2026.md`
- `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`
- `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`
- `projects/diagnostico-vivacasa-q4-2026/PLAN.md`
