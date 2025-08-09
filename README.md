# 🎲 Dashboard Interativo de Salários na Área de Dados

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://dashboard-imersao-alura-eduardo.streamlit.app/)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.35%2B-red.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.2%2B-darkgreen.svg)
![Plotly](https://img.shields.io/badge/Plotly-5.22%2B-purple.svg)

## 📖 Sobre o Projeto

Este projeto é um dashboard interativo construído com **Streamlit** para visualizar e analisar dados de salários na área de Data Science, Engenharia de Dados, Análise de Dados e afins. A aplicação permite que os usuários explorem tendências salariais através de filtros dinâmicos e visualizações gráficas detalhadas.

O objetivo é fornecer uma ferramenta clara e intuitiva para que profissionais e recrutadores possam entender melhor o panorama de remuneração no mercado de dados.

---
## ✨ Funcionalidades Principais

* 📊 **Visualização de KPIs:** Métricas chave como salário médio, salário máximo, total de registros e o cargo mais frequente na base de dados filtrada.
* 🔍 **Filtros Interativos:** Filtre os dados de forma granular por:
    * Ano
    * Nível de Senioridade
    * Tipo de Contrato (CLT, PJ, etc.)
    * Tamanho da Empresa
* 📈 **Gráficos Dinâmicos e Interativos:**
    * **Top 10 Cargos por Salário Médio:** Um gráfico de barras horizontais que mostra os cargos mais bem remunerados.
    * **Distribuição Salarial:** Um histograma que exibe a frequência das diferentes faixas salariais.
    * **Proporção de Trabalho Remoto:** Um gráfico de pizza (donut) que ilustra a prevalência de trabalho remoto, híbrido e presencial.
    * **Mapa de Salários por País:** Um mapa coroplético que mostra a média salarial para Cientistas de Dados ao redor do mundo.
* 📋 **Tabela de Dados Detalhada:** Visualize e ordene os dados brutos que correspondem à sua seleção de filtros.

---

## 🖼️ Screenshot do Dashboard

*Adicione aqui um screenshot do seu dashboard em execução! Uma imagem ajuda muito a divulgar seu projeto.*

![Screenshot do Dashboard](./screenshot.png)

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias:

* **Python:** Linguagem de programação principal.
* **Streamlit:** Framework para a criação do dashboard e da interface web.
* **Pandas:** Biblioteca para manipulação e análise dos dados.
* **Plotly Express:** Biblioteca para a criação dos gráficos interativos.

---

## 🚀 Como Executar o Projeto Localmente

Para executar este dashboard na sua máquina local, siga os passos abaixo.

### Pré-requisitos
* [Python](https://www.python.org/downloads/) (versão 3.9 ou superior)
* [Git](https://git-scm.com/)

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    cd seu-repositorio
    ```

2.  **(Recomendado) Crie e ative um ambiente virtual:**
    ```bash
    # Criar o ambiente
    python -m venv .venv

    # Ativar no Windows
    .venv\Scripts\Activate

    # Ativar no Linux/macOS
    source .venv/bin/activate
    ```

3.  **Crie o arquivo `requirements.txt`:**
    Este arquivo lista todas as bibliotecas que o projeto precisa. Crie um arquivo chamado `requirements.txt` e adicione o seguinte conteúdo:
    ```txt
    streamlit
    pandas
    plotly
    ```

4.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

5.  **Execute a aplicação Streamlit:**
    ```bash
    streamlit run app.py
    ```

Seu navegador abrirá automaticamente com o dashboard em execução!

---
## 📊 Fonte dos Dados

Os dados utilizados neste projeto são públicos e foram obtidos a partir do seguinte repositório no GitHub:
[vqrca/dashboard_salarios_dados](https://github.com/vqrca/dashboard_salarios_dados/blob/main/dados-imersao-final.csv).

---
