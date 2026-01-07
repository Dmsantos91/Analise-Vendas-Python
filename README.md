# 📊 Análise de Vendas e Lucratividade E-commerce

## 📝 Sobre o Projeto
Este projeto consiste em uma **Análise Exploratória de Dados (EDA)** realizada sobre um dataset de vendas de varejo. O objetivo principal foi identificar padrões de consumo, sazonalidade de vendas e correlação entre volume de vendas e lucratividade.

O projeto passa por todas as etapas de uma análise de dados: carregamento, limpeza/tratamento de tipos de dados (datetime), criação de visualizações individuais e consolidação em um dashboard gerencial.

## 🛠️ Tecnologias Utilizadas
* **Python** (Linguagem principal)
* **Pandas** (Manipulação e tratamento de dados)
* **Matplotlib & Seaborn** (Visualização de dados)
* **Google Colab** (Ambiente de desenvolvimento)

## 📂 Estrutura do Projeto
* `analise_vendas.ipynb`: O notebook contendo todo o código e as análises.
* `sales_data_updated.csv`: O conjunto de dados utilizado (necessário para rodar o script).

## 📈 Visualizações Geradas
Durante a análise, foram criados os seguintes gráficos para responder a perguntas de negócio:
1.  **Histograma:** Para entender a distribuição de preços dos produtos vendidos.
2.  **Gráfico de Linha:** Para analisar a evolução das vendas ao longo do tempo (Tendência e Sazonalidade).
3.  **Gráfico de Barras:** Para comparar a performance de vendas por categoria de produto.
4.  **Scatter Plot (Dispersão):** Para verificar a correlação entre Vendas Totais e Lucro.
5.  **Dashboard Consolidado:** Uma visão unificada (Subplots) de todos os indicadores.

## 💡 Principais Insights e Conclusões
Com base nos dados analisados, chegamos aos seguintes diagnósticos de negócio:

* **Faixa de Preço Ideal:** A maior concentração de vendas ocorre em produtos com preço entre **$210 e $230**.
* **Sazonalidade:** Identificamos uma tendência geral de crescimento, mas com oscilações claras (picos e vales) que sugerem forte sazonalidade.
* **Performance por Categoria:** A categoria **"Fashion"** lidera o volume de vendas, enquanto a categoria **"Electronics"** apresenta o menor desempenho, exigindo revisão de estratégia.
* **Relação Volume x Lucro:** Existe uma correlação positiva clara: pedidos com maior volume de vendas tendem a gerar proporcionalmente mais lucro, validando estratégias de incentivo ao aumento do ticket médio.

## 🚀 Como Executar
1.  Clone este repositório.
2.  Certifique-se de que o arquivo `.csv` esteja na mesma pasta do notebook.
3.  Execute o arquivo `.ipynb` usando Jupyter Notebook, VS Code ou Google Colab.

---
Desenvolvido por **Diego Santos** Conecte-se comigo no LinkedIn: https://www.linkedin.com/in/diego-santos-45a72a109/
