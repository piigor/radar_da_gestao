# Estudo de caso — VivaCasa

## Conclusão executiva

O caso fictício da VivaCasa demonstra que um diagnóstico executivo é mais valioso quando conecta desempenho comercial a restrições operacionais. A receita ficou abaixo da meta, a margem de contribuição permaneceu abaixo do objetivo fictício, a ruptura aumentou nas categorias e a conversão da mídia paga caiu apesar do investimento adicional.

A implicação prática é mudar a sequência de decisão. A empresa não deveria começar aumentando a geração de demanda. Primeiro, deveria reconciliar as definições dos indicadores, proteger os SKUs prioritários, conectar decisões de campanha à disponibilidade e à margem e testar canais de retenção com desenho incremental.

## Entradas

A demonstração usa cinco tipos de entrada:

| Input | O que contribui |
|---|---|
| Ata de reunião de diretoria | Contexto estratégico, decisões e hipóteses |
| CSV mensal de vendas | Receita, meta, margem, pedidos e ticket |
| CSV de estoque | Ruptura, dias de estoque, giro e margem por categoria |
| CSV de marketing | Investimento, receita atribuída, conversão e CAC |
| Pesquisa de clientes | Sinais direcionais de experiência e disponibilidade |

Todas as entradas são fictícias. Os arquivos são intencionalmente pequenos para que o leitor possa inspecionar os cálculos diretamente.

## Cadeia de evidências

### Receita

O arquivo mensal de vendas soma **R$ 10,55 milhões** de receita líquida de janeiro a agosto de 2026. A meta fictícia correspondente soma **R$ 11,29 milhões**. A diferença é de **R$ 740 mil**, ou **6,55% abaixo da meta**.

### Margem

A margem média simples de contribuição é de **30,40%**. A meta fictícia é de **32,00%**. O conjunto de dados não contém detalhes suficientes para auditar a margem por SKU ou canal; por isso, o output trata a fórmula como provisória.

### Disponibilidade

A ruptura aumentou em todas as categorias. Organização subiu de 8,2% para 11,8%; cozinha e mesa, de 7,1% para 10,3%; decoração, de 6,4% para 9,1%; banheiro e lavanderia, de 5,8% para 8,6%; e pequenos móveis, de 4,9% para 7,8%.

### Eficiência de marketing

A busca paga aumentou o investimento de R$ 82 mil para R$ 108 mil, enquanto a conversão caiu de 2,8% para 2,5%. O social pago aumentou de R$ 76 mil para R$ 99 mil, enquanto a conversão caiu de 2,1% para 1,9%.

E-mail e WhatsApp autorizado apresentam CAC informado menor e conversão maior no arquivo fictício. Esses resultados são tratados como sinais, não como prova de impacto incremental, porque o conjunto de dados não inclui experimento controlado nem denominador completo de clientes por canal.

## Diagnóstico

O diagnóstico mais plausível é um **problema de coordenação**, e não de um único canal. Geração de demanda, disponibilidade de produtos, economia da margem e definições de indicadores não estão sendo gerenciadas como um único sistema de decisão.

| Camada | Observação | Interpretação |
|---|---|---|
| Comercial | Receita abaixo da meta | O crescimento não acompanha o plano |
| Econômica | Margem abaixo da meta | Receita adicional pode não ser suficientemente rentável |
| Operacional | Ruptura aumentando | A demanda pode estar sendo perdida no nível do produto |
| Marketing | Conversão paga caindo | Mais investimento não está se traduzindo em melhor eficiência |
| Governança | Não há uma visão executiva única | As decisões podem ficar fragmentadas entre áreas |

## Resposta recomendada para 90 dias

O plano de ação prioriza quatro movimentos:

1. Criar uma rotina semanal de SKUs prioritários e ruptura.
2. Suspender a expansão incremental da mídia paga até verificar a disponibilidade dos produtos promovidos.
3. Validar a fórmula da margem de contribuição e o dicionário executivo de indicadores.
4. Executar um teste controlado de retenção em e-mail e WhatsApp autorizado.

Estas são recomendações, não decisões aprovadas. Um cliente real validaria os dados, responsáveis, permissões legais e a economia antes da execução.

## Por que isso é útil como demonstração pública

O valor do exemplo não está nos números fictícios. Está na **rastreabilidade do trabalho**. O leitor pode acompanhar o caminho do input bruto ao sinal calculado, do sinal à hipótese, da hipótese à recomendação e da recomendação ao plano de execução de 90 dias.
