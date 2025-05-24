# Análise de Evasão de Clientes (Churn) - Telecom X

## Visão Geral do Projeto

Este projeto tem como objetivo principal analisar os dados da Telecom X para identificar os fatores que contribuem para a evasão de clientes (Churn). A compreensão desses fatores é crucial para que a empresa possa desenvolver estratégias de retenção mais eficazes, minimizando a perda de receita e otimizando os custos de aquisição de novos clientes.

O trabalho foi desenvolvido como parte de um desafio de Data Science e inclui etapas de extração, transformação e carregamento (ETL) dos dados, análise exploratória (EDA) e a elaboração de um relatório completo com conclusões e recomendações.

## Estrutura do Projeto

O projeto é composto por um único Jupyter Notebook:

-   `TelecomX_Churn_Analysis_Report.ipynb`: Contém todo o código-fonte para carregamento, limpeza, tratamento e análise dos dados, além de um relatório detalhado com os resultados e insights.

## Bibliotecas Utilizadas

As seguintes bibliotecas Python foram utilizadas neste projeto:

-   `pandas`: Para manipulação e análise de dados.
-   `numpy`: Para operações numéricas de alto desempenho.
-   `requests`: Para fazer requisições HTTP e carregar dados de uma URL externa.
-   `seaborn`: Para visualização estatística de dados.
-   `matplotlib.pyplot`: Para personalização e exibição de gráficos.

## Como Executar o Projeto

Para replicar a análise, siga os passos abaixo:

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)
    cd SEU_REPOSITORIO
    ```
    *(Substitua `SEU_USUARIO` e `SEU_REPOSITORIO` pelo seu nome de usuário e nome do repositório no GitHub)*

2.  **Crie e Ative um Ambiente Virtual (Recomendado):**
    ```bash
    python -m venv venv
    # No Windows:
    .\venv\Scripts\activate
    # No macOS/Linux:
    source venv/bin/activate
    ```

3.  **Instale as Dependências:**
    ```bash
    pip install pandas numpy requests seaborn matplotlib
    ```

4.  **Execute o Jupyter Notebook:**
    ```bash
    jupyter notebook TelecomX_Churn_Analysis_Report.ipynb
    ```
    Isso abrirá o Jupyter Notebook no seu navegador padrão. Você poderá executar todas as células para ver o fluxo da análise e o relatório final.

## Conclusões e Recomendações Principais

As principais descobertas do relatório indicam que:

* **Clientes com menor tempo de contrato (`tenure`)** são mais propensos a evadir.
* **Contratos mensais** estão fortemente associados a uma alta taxa de churn.
* O **método de pagamento "Electronic check"** também mostra uma correlação com maior churn.
* **Adesão a serviços adicionais** (segurança online, backup, suporte técnico) parece aumentar a retenção.
* **Clientes de Fibra Óptica** apresentaram uma taxa de churn surpreendentemente alta, indicando possíveis problemas de qualidade de serviço ou expectativa.

Com base nisso, são feitas recomendações como: programas de boas-vindas para novos clientes, incentivos para contratos mais longos, investigação de problemas com o método de pagamento "Electronic check", promoção de serviços adicionais e reavaliação da qualidade do serviço de fibra óptica.

Para mais detalhes sobre as análises e recomendações, consulte o relatório completo dentro do notebook.

---

**Autor:** Dragos Calin
**Data:** 24Maio de 2025
