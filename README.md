# Challenge Data Science - Telecom X 🚀
*Projeto de ETL e Análise Exploratória de Dados para redução de Churn*

## 📌 Introdução
Este projeto foi desenvolvido como parte do **Programa ONE (Oracle Next Education)** em parceria com a **Alura**. O objetivo central é analisar os dados da **Telecom X** para entender os motivos por trás da taxa de evasão de clientes (**Churn**) de **26,58%** e oferecer insumos para estratégias de retenção.

## ⚙️ Processo de ETL (Extração, Transformação e Carga)
A base de dados foi tratada seguindo as melhores práticas de Engenharia de Dados:
* **Extração**: Consumo de dados diretamente de uma API hospedada no GitHub em formato JSON.
* **Transformação**: 
    * Desaninhamento (flattening) de dicionários complexos em colunas individuais.
    * Conversão da coluna `Charges.Total` para o tipo numérico.
* **Limpeza**: Identificação e remoção de **11 valores nulos** críticos para a análise.

## 📊 Principais Insights (EDA)
Através da Análise Exploratória de Dados, identificamos padrões cruciais:
1.  **Sensibilidade ao Preço**: Clientes com faturas mensais elevadas apresentam uma propensão muito maior ao cancelamento.
2.  **Risco na Integração**: A maior parte da evasão ocorre nos primeiros meses de contrato (**baixo tenure**), indicando uma falha na retenção de novos assinantes.

## 💡 Sugestões Estratégicas
* Implementação de programas de fidelidade ou "boas-vindas" focados nos primeiros 6 meses de contrato.
* Revisão da tabela de preços para planos de alto valor, visando competitividade no mercado.

## 🛠️ Tecnologias Utilizadas
* **Python**
* **Pandas** (Manipulação de dados)
* **Seaborn / Matplotlib** (Visualização de dados)
