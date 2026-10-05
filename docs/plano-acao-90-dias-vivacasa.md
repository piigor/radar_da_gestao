---
id: plano-ação-90-dias-vivacasa
title: "Plano de Ação 90 Dias VivaCasa"
type: Saída
namespace: vivacasa
lifecycle_state: research
summary: "Plano de ação fictício de 90 dias para VivaCasa, derivado do diagnóstico executivo e organizado por horizontes de execucao."
confidence: 0.76
retrieval_class: normal
export_class: private
created: 2026-09-10
aliases: [plano-ação-90-dias-vivacasa]
lineage:
  - "outputs/analysis/diagnostico-executivo-vivacasa.md"
  - "intake/processed/analise-completa-do-intake.md"
  - "data/indicadores/dicionario-de-indicadores-vivacasa.md"
  - "knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md"
  - "projects/diagnostico-vivacasa-q4-2026/PLAN.md"
edges:
  - target: "[[diagnóstico-executivo-vivacasa]]"
    relation: "derived_from"
    confidence: 0.9
  - target: "[[dicionario-de-indicadores-vivacasa]]"
    relation: "uses"
    confidence: 0.84
  - target: "[[governanca-e-responsabilidades-vivacasa]]"
    relation: "informed_by"
    confidence: 0.8
---

# Plano de Ação 90 Dias VivaCasa

> Dados fictícios e demonstrativos. Este plano nao transforma recomendacoes em decisoes aprovadas. Acoes marcadas com "Depende da diretoria" exigem aprovação executiva antes de execucao plena.

## Escopo e Prioridade

Este plano foi derivado do diagnóstico executivo da VivaCasa e prioriza, nesta ordem:

1. Reducao de ruptura.
2. Protecao da margem.
3. Revisao da midia paga.
4. Teste de retenção.
5. Definicao do dicionario de indicadores.

Periodo de referencia dos dados: janeiro a agosto de 2026. Horizonte recomendado: 90 dias apos aprovação executiva do plano.

## Primeiros 15 Dias

| Ação | Problema tratado | Responsavel | Prazo | Indicador | Meta | Dependencias | Risco |
|---|---|---|---|---|---|---|---|
| Montar lista inicial de SKUs e categorias prioritarias em risco de ruptura, com Organização, Cozinha e mesa, Decoração, Banheiro e lavanderia e Pequenos móveis como recortes iniciais | Ruptura crescente em todas as categorias analisadas | Operações, com apoio comercial | Dia 5 | Ruptura de SKU prioritario | Reducao fictícia de 30% nas rupturas dos itens prioritarios | Dados de estoque, e-commerce e calendario de campanhas; depende da diretoria para aprovar criterio de SKU prioritario | Tratar erro de cadastro ou estoque reservado como ruptura real |
| Suspender novos aumentos de midia paga ate checar disponibilidade dos produtos promovidos | Risco de investir em trafego para produtos sem disponibilidade | Marketing, operações e comercial | Dia 7 | Conversão digital, CAC por canal e ruptura | a validar para conversão e CAC; manter bloqueio ate validação de estoque promocionado | Depende da diretoria para confirmar limite de midia antes da correcao de estoque | Reduzir alcance sem plano de realocação para canais mais eficientes |
| Validar definicoes operacionais de receita liquida, margem de contribuicao, ruptura, conversão e CAC | Indicadores calculados de forma diferente entre areas | Financeiro, marketing, comercial e operações | Dia 10 | Dicionario de indicadores | Definicoes aprovadas ou marcadas como `a validar` com dono e fonte | Depende da diretoria para aprovar definicoes oficiais de receita e margem | Usar metricas provisorias como base de decisao definitiva |
| Reconciliar margem de contribuicao com custos variaveis conhecidos, incluindo comissoes, frete variavel e midia atribuida quando houver base suficiente | Margem media de contribuicao abaixo da meta fictícia de 32% | Financeiro, com validação comercial | Dia 12 | Margem de contribuicao | 32%, meta fictícia, somente apos formula validada | Fonte financeira, ERP, marketplaces, logistica e plataformas de marketing; depende da diretoria para aprovar formula oficial | Comparar margem por canal com custo incompleto |
| Definir desenho do teste de retenção em e-mail e WhatsApp autorizado sem ampliar escala ainda | Necessidade de testar canais com melhor eficiencia observada sem concluir causalidade | Marketing e CRM, com apoio comercial | Dia 15 | Conversão digital e CAC por canal | a validar | Base CRM autorizada, regra de atribuicao e exclusao de clientes ja impactados; depende da diretoria se houver uso de verba incremental | Confundir recompra natural com efeito incremental do teste |

## Dias 16 a 30

| Ação | Problema tratado | Responsavel | Prazo | Indicador | Meta | Dependencias | Risco |
|---|---|---|---|---|---|---|---|
| Implantar rotina semanal de ruptura com pauta de reposicao, transferencia entre lojas e revisao de campanhas ativas | Ruptura crescente e falta de ação coordenada entre estoque e campanhas | Operações, comercial e marketing | Dia 21 | Ruptura de SKU prioritario | Reducao fictícia de 30% nas rupturas dos itens prioritarios | Lista de SKUs prioritarios aprovada, estoque por localidade e calendario de campanhas | Gerar reuniao operacional sem decisao de reposicao |
| Criar semaforo de campanha paga: liberar, pausar ou revisar por disponibilidade, margem e conversão | Busca paga e social paga com mais investimento e menor conversão | Marketing, com operações e financeiro | Dia 24 | Conversão digital, CAC por canal, margem de contribuicao e ruptura | a validar para conversão e CAC; margem de 32% como referencia fictícia apos validação | Disponibilidade por produto promovido, margem validada e atribuicao por canal; depende da diretoria para regra de limite de verba | Cortar campanhas eficientes por leitura incompleta de atribuicao |
| Revisar descontos e promocoes de categorias com margem pressionada antes de buscar receita adicional | Risco de crescer receita por desconto que destrua margem | Financeiro e comercial | Dia 26 | Margem de contribuicao | 32%, meta fictícia, condicionada a formula aprovada | Formula de margem, dados de comissoes, frete, devolucoes e descontos; depende da diretoria para limite de desconto por categoria | Proteger margem reduzindo volume sem alternativa comercial |
| Publicar primeira versao operacional do dicionario de indicadores, com campos aprovados e pendencias visiveis | Falta de definicoes comuns para decisao executiva | Financeiro, marketing, comercial e operações | Dia 30 | Dicionario de indicadores | 100% dos indicadores do plano com fonte, dono, periodicidade e status de validação | Revisao das areas e decisao da diretoria sobre definicoes oficiais | Fechar definicao prematura para indicador ainda nao auditavel |
| Rodar piloto controlado de retenção em e-mail e WhatsApp autorizado com grupo comparavel e limite de investimento | Necessidade de testar canais de menor CAC informado sem assumir causalidade | Marketing e CRM | Dia 30 | Conversão digital e CAC por canal | a validar | Base autorizada, criterio de grupo de controle, regra de atribuicao e acompanhamento de devolucoes | Superestimar resultado por falta de grupo comparavel |

## Dias 31 a 60

| Ação | Problema tratado | Responsavel | Prazo | Indicador | Meta | Dependencias | Risco |
|---|---|---|---|---|---|---|---|
| Cruzar campanhas pagas com disponibilidade, ruptura e margem dos produtos promovidos | Hipótese de midia direcionando trafego para produtos sem disponibilidade ou baixa contribuicao | Marketing, operações e financeiro | Dia 40 | Conversão digital, CAC por canal, ruptura e margem de contribuicao | a validar para conversão e CAC; margem de 32% como referencia fictícia apos validação | Dados por SKU ou produto promovido, estoque, campanha e custos variaveis | Tomar correlação como causalidade sem teste |
| Priorizar reposicao e transferencia para categorias com maior aumento de ruptura e relevancia comercial | Ruptura alta podendo limitar conversão e receita | Operações e comercial | Dia 45 | Ruptura de SKU prioritario | Reducao fictícia de 30% nas rupturas dos itens prioritarios | Politica de estoque, lead time, disponibilidade em CD e lojas | Melhorar disponibilidade de itens com baixa margem ou baixa demanda |
| Revisar mix e comunicação de categorias de baixo ticket frente a margem validada | Hipótese de volume sem margem suficiente | Comercial e financeiro | Dia 50 | Margem de contribuicao e receita liquida | 32%, meta fictícia, condicionada a formula aprovada | Margem por categoria e canal, ainda ausente nas fontes atuais; depende da diretoria para mudancas de mix relevantes | Reduzir sortimento sem entender papel de atração da categoria |
| Avaliar resultado parcial do teste de retenção antes de escalar investimento | Canais de retenção parecem eficientes, mas precisam de validação incremental | Marketing e CRM, com financeiro | Dia 55 | Conversão digital e CAC por canal | a validar | Grupo de controle, deduplicação de clientes, tratamento de devolucoes e cancelamentos | Escalar canal por CAC informado sem lucro incremental |
| Preparar pacote executivo com impactos, pendencias e decisoes necessarias | Diretoria precisa decidir onde investir com visao integrada | Consultoria, financeiro, marketing, comercial e operações | Dia 60 | Receita liquida, margem, ruptura, conversão e CAC | Definicoes validadas ou pendencias explicitadas | Dados reconciliados e donos por indicador; depende da diretoria para priorização de trade-offs | Apresentar recomendação como fato aprovado |

## Dias 61 a 90

| Ação | Problema tratado | Responsavel | Prazo | Indicador | Meta | Dependencias | Risco |
|---|---|---|---|---|---|---|---|
| Formalizar cadencia mensal executiva com dono, fonte e regra de decisao por indicador | Ausencia de painel unico e governanca recorrente | Diretoria, financeiro, marketing, comercial e operações | Dia 70 | Dicionario de indicadores | Todos os indicadores executivos com dono, fonte, periodicidade, limite e pendencia documentada | Depende da diretoria para nomear responsaveis e aprovar cadencia | Criar ritual sem autoridade para resolver conflitos |
| Consolidar politica de midia paga condicionada a disponibilidade, margem e aprendizagem do teste de retenção | Risco de ampliar investimento sem corrigir disponibilidade ou medir incrementalidade | Diretoria e marketing, com financeiro e operações | Dia 75 | CAC por canal, conversão digital, margem de contribuicao e ruptura | a validar para CAC e conversão; margem de 32% como referencia fictícia apos validação | Depende da diretoria para limite de investimento e criterios de escala | Subinvestir em aquisicao por excesso de cautela ou superinvestir por leitura atribuida |
| Definir politica provisoria de descontos por categoria baseada em margem validada | Crescimento por desconto que destrua margem | Diretoria, financeiro e comercial | Dia 80 | Margem de contribuicao e receita liquida | 32%, meta fictícia, condicionada a formula aprovada | Margem por categoria, tratamento de devolucoes e papel estrategico das categorias | Proteger margem no agregado e perder competitividade em itens-chave |
| Decidir continuidade, escala ou encerramento do teste de retenção | Necessidade de transformar teste em decisao executiva somente apos evidencia | Diretoria, marketing e CRM | Dia 85 | Conversão digital, CAC por canal e receita liquida | a validar | Resultado do piloto, análise incremental e capacidade operacional | Escalar resultado nao incremental ou encerrar canal promissor cedo demais |
| Fechar revisao de 90 dias com pendencias, indicadores aprovados e backlog de melhorias de dados | Risco de voltar a decisoes fragmentadas apos o diagnóstico | Consultoria e diretoria, com todas as areas | Dia 90 | Receita liquida, margem de contribuicao, ruptura, conversão, CAC e dicionario de indicadores | Plano revisado com decisoes aprovadas, pendencias e proximos donos | Depende da diretoria para aprovar proximos passos e responsabilidades | Encerrar diagnóstico sem transferencia operacional para as areas |

## Acoes Que Dependem da Diretoria

- Aprovar criterio de SKU prioritario e ruptura monitorada.
- Confirmar limite de midia paga antes da correcao de estoque.
- Aprovar definicoes oficiais de receita liquida e margem de contribuicao.
- Aprovar limite de desconto por categoria, se houver politica provisoria.
- Nomear responsaveis finais por indicadores e cadencia mensal executiva.
- Decidir escala, continuidade ou encerramento do teste de retenção.

## Fontes Utilizadas

- `outputs/analysis/diagnostico-executivo-vivacasa.md`
- `intake/processed/analise-completa-do-intake.md`
- `data/indicadores/dicionario-de-indicadores-vivacasa.md`
- `data/indicadores/receita-liquida.md`
- `data/indicadores/margem-contribuicao.md`
- `data/indicadores/ruptura.md`
- `data/indicadores/conversao.md`
- `data/indicadores/cac-por-canal.md`
- `knowledge/vivacasa/concepts/governanca-e-responsabilidades-vivacasa.md`
- `knowledge/vivacasa/concepts/hipoteses-de-diagnostico-vivacasa.md`
- `knowledge/vivacasa/concepts/problemas-estrategicos-q4-2026.md`
- `projects/diagnostico-vivacasa-q4-2026/PLAN.md`

## Limitacoes

- Todos os dados sao fictícios e demonstrativos.
- O plano e recomendatorio e nao representa aprovação executiva.
- O CAC por canal ainda nao pode ser auditado de forma independente porque faltam clientes novos atribuidos por canal.
- Conversão e CAC seguem com meta `a validar`.
- Margem por SKU, categoria e canal ainda nao esta disponivel nas fontes atuais.
- A meta de margem de 32% e a reducao fictícia de 30% em rupturas prioritarias foram mantidas conforme o dicionario de indicadores, mas dependem de validação executiva antes de uso decisorio.
