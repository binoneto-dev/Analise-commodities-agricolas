# Análise de Preços e Variação Percentual de matérias-primas agrícolas (Commodities)

## Visão Geral

Este projeto tem como objetivo analisar o comportamento dos **preços** e da **variação percentual (% Change)** de diferentes **commodities** ao longo do tempo, identificando padrões, relações e possíveis dependências entre elas.

A análise utiliza técnicas de **análise exploratória de dados (EDA)** e **correlação**, com foco em apoiar a tomada de decisão estratégica baseada em dados.

---

## Conjunto de Dados

O dataset é composto por informações de preços e variação percentual das seguintes commodities:

- **Coarse Wool** → Lã grossa
- **Fine Wool** → Lã fina
- **Cotton** → Algodão
- **Copra** → Copra (polpa seca do coco)
- **Hide** → Couro (pele animal)
- **Rubber** → Borracha
- **Wood Pulp** → Celulose
- **Softlog** → Madeira macia (toras de madeira macia)
- **Hard Log** → Madeira dura (toras de madeira dura)
- **Soft Sawnwood** → Madeira serrada macia
- **Hard Sawnwood** → Madeira serrada dura
- **Plywood** → Compensado (madeira compensada)

Para cada commodity, foram analisadas:

- **Preço**
- **Variação percentual do preço (% Change)**

---

## Tecnologias Utilizadas

- **Python**
- **Pandas** – manipulação e tratamento de dados
- **NumPy** – operações numéricas
- **Matplotlib & Seaborn** – visualização de dados
- **Jupyter Notebook** – ambiente de análise

---

## Metodologia de Análise

### 1 Preparação dos Dados

- Padronização de datas
- Conversão de valores para tipo `float`
- Seleção das variáveis relevantes para análise

### 2 Análise Exploratória

- Identificação de commodities de **alta** e **baixa gama** de preços
- Avaliação da **volatilidade** por meio da variação percentual
- Observação da evolução dos preços ao longo dos anos

### 3 Análise de Correlação

- Cálculo da matriz de correlação entre as variações percentuais
- Visualização das correlações por meio de um **mapa de calor (heatmap)**

---

## Interpretação da Correlação

- **Correlação positiva**: quando duas commodities tendem a subir ou cair juntas.
- **Correlação negativa**: quando o aumento de uma está associado à queda da outra.
- **Correlação próxima de zero**: indica ausência ou fraqueza de relação entre as variáveis.

> Quanto maior o valor absoluto da correlação, maior a evidência de relacionamento entre as variações de preço.

---

## Principais Insights

- Foi possível **classificar as commodities entre alta e baixa gama** com base em seus preços médios.
- Identificamos commodities com **alta volatilidade**, caracterizadas por maiores variações percentuais ao longo do tempo.
- A maioria das commodities apresenta **correlações fracas**, indicando que seus preços tendem a variar de forma relativamente independente.
- Algumas correlações moderadas foram observadas, especialmente entre commodities do **setor madeireiro**, sugerindo influência de fatores comuns como oferta, demanda e condições macroeconômicas.
- O mapa de calor mostrou-se uma ferramenta eficiente para **visualização rápida de relações** entre variáveis.

---

## Possíveis Decisões Estratégicas

Com base nos dados analisados, este estudo pode apoiar decisões como:

- **Diversificação de portfólio**, reduzindo riscos associados à volatilidade
- **Planejamento de compras e estoques**, priorizando commodities menos instáveis
- **Monitoramento de grupos correlacionados**, antecipando impactos de mercado

---

## Conclusão

A análise demonstrou que, apesar de algumas relações entre commodities, grande parte dos preços se comporta de maneira independente. Isso reforça a importância de análises individuais, além de análises conjunturais, para uma tomada de decisão mais assertiva.

O uso de técnicas simples de EDA e correlação já fornece **insights relevantes**, mostrando o poder da análise de dados aplicada ao contexto econômico.

---

## Próximos Passos

- Aplicar modelos de **séries temporais**
- Criar **dashboards interativos** (Power BI / Looker Studio)
- Analisar impactos de variáveis macroeconômicas externas

---

## Autor

**Albino A Neto**
Estudante de Análise e Ciência de Dados
