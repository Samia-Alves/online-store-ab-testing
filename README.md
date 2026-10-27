# Online Store — Priorização de Hipóteses e Teste A/B

## Sobre o projeto

Neste projeto de análise de negócios, avaliei oportunidades de crescimento de uma loja online. O trabalho divide-se em duas partes: **priorização de hipóteses de marketing** e **análise dos resultados de um teste A/B**, com foco na conversão e nas receitas.

Projeto desenvolvido durante a formação em **Data Analytics da TripleTen (Sprint 9)**.

## Objetivos

- Priorizar hipóteses de crescimento utilizando os frameworks **ICE** e **RICE**.
- Comparar o desempenho dos grupos A e B num teste A/B.
- Analisar a receita acumulada, o valor médio dos pedidos e a conversão.
- Identificar valores atípicos e comparar resultados com e sem esses valores.
- Aplicar testes estatísticos para apoiar uma decisão de negócio.

## Ferramentas e competências

**Python**, **pandas**, **NumPy**, **Matplotlib**, **SciPy**, **Jupyter Notebook**, análise exploratória de dados, estatística, testes A/B e priorização ICE/RICE.

## Dados utilizados

O estudo utiliza três conjuntos de dados:

- `hypotheses_us.csv` — hipóteses de marketing e respetivas pontuações de alcance, impacto, confiança e esforço.
- `orders_us.csv` — pedidos, receitas e grupos do teste A/B.
- `visits_us.csv` — visitas diárias por grupo.

**Nota:** os ficheiros CSV não estão incluídos neste repositório. O notebook mantém os caminhos de dados do ambiente de formação (`/datasets/`); para executar a análise localmente, é necessário obter os dados e adaptar esses caminhos.

## Etapas da análise

1. Importação, exploração e preparação dos dados.
2. Priorização de hipóteses com ICE e RICE.
3. Evolução da receita e do valor médio dos pedidos por grupo.
4. Análise das taxas de conversão.
5. Identificação de anomalias e filtragem dos dados.
6. Testes de significância estatística.
7. Recomendação final para o negócio.

## Principais conclusões

- O **grupo B** apresentou uma **taxa de conversão estatisticamente superior** à do grupo A, tanto nos dados brutos como nos filtrados.
- Não foi identificada uma **diferença estatisticamente significativa no valor médio dos pedidos** entre os grupos.
- Com base nos resultados, a recomendação apresentada no estudo é **parar o teste e considerar o grupo B como líder**.

## Consultar a análise

Abre o ficheiro [`Online_Store_AB_Testing.ipynb`](Online_Store_AB_Testing.ipynb) para acompanhar o raciocínio completo, os gráficos, os testes estatísticos e as conclusões.

---

*Projeto académico de portefólio — Data Analytics | TripleTen*
