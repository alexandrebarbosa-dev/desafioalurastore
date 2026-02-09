# 📊 Desafio Alura Store – Análise de Dados com Python (arquivo README produzido com o auxílio de IA, utilizando prompts criados por mim ao longo e ao fim do trabalho).

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do curso **Fundamentos de Python e Dados – G9 | ONE**.

O objetivo da análise foi auxiliar o Senhor João, proprietário da rede fictícia **Alura Store**, na decisão sobre qual das quatro lojas deve ser vendida para viabilizar um novo empreendimento.

A partir de dados reais simulados em arquivos CSV, foram realizadas análises utilizando **Python, Pandas e Matplotlib**, explorando métricas financeiras e de desempenho.

---

## 🎯 Objetivo da Análise

Identificar a loja com menor eficiência operacional e financeira com base nos seguintes critérios:

- Faturamento total
- Média de avaliação dos clientes
- Distribuição de vendas por categoria
- Produtos mais e menos vendidos
- Custo médio de frete

A decisão final foi fundamentada na análise comparativa desses indicadores.

---

## 🛠 Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib
- Google Colab

---

## 📂 Estrutura dos Dados

Cada loja possui um arquivo CSV contendo:

- Produto
- Categoria do Produto
- Preço
- Frete
- Data da Compra
- Vendedor
- Local da Compra
- Avaliação da compra
- Tipo de pagamento
- Quantidade de parcelas
- Coordenadas geográficas (lat, lon)

---

## 📊 Principais Análises Realizadas

### ✔ Faturamento Total por Loja
Cálculo da soma da coluna `Preço` para cada loja.

### ✔ Média de Avaliação dos Clientes
Cálculo da média da coluna `Avaliação da compra`.

### ✔ Vendas por Categoria
Agrupamento e contagem de produtos por categoria.

### ✔ Produtos Mais e Menos Vendidos
Ranking de vendas com filtros por volume mínimo.

### ✔ Custo Médio de Frete
Cálculo da média da coluna `Frete` por loja.

---

## 📈 Visualizações Geradas

Foram produzidos diferentes tipos de gráficos:

- Gráfico de barras (Faturamento)
- Gráfico de barras (Média de Avaliação)
- Gráfico de pizza (Categorias)
- Gráfico comparativo (Faturamento x Avaliação)

As visualizações auxiliaram na interpretação dos dados e na tomada de decisão final.

---

## 🧠 Conclusão da Análise

Após avaliação dos indicadores, concluiu-se que:

- A Loja 1 apresenta maior faturamento, porém menor avaliação média.
- A Loja 4 possui menor faturamento, mas avaliação superior à Loja 1.
- As categorias vendidas são semelhantes entre as lojas.
- O custo de frete não demonstrou impacto significativo no desempenho.

Com base nos dados analisados, a recomendação foi a venda da **Loja 4**, por apresentar o menor desempenho financeiro relativo, mantendo as unidades de maior geração de receita.

