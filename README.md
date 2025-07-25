# 📊 Telecom X - Análise de Evasão de Clientes

Bem-vindo ao projeto **Churn de Clientes** da **Telecom X**, desenvolvido como parte de um desafio analítico para identificar os principais fatores que levam os clientes a cancelarem seus serviços.

---

## 🎯 Propósito da Análise

A **Telecom X** enfrenta um elevado índice de cancelamentos de contratos por parte de seus clientes. Este projeto tem como objetivo realizar uma **Análise Exploratória de Dados (EDA)** robusta, identificando os principais padrões, correlações e tendências que podem explicar a evasão de clientes (churn).

Através desta análise, espera-se fornecer uma base sólida de insights para que a equipe de Data Science possa avançar no desenvolvimento de **modelos preditivos** e propor **estratégias de retenção** mais eficazes.

---

## 🗂️ Estrutura do Projeto

A seguir, a organização dos arquivos e pastas:

📁 telecom-x-churn/
├── 📄 README.md # Este arquivo de documentação
├── 📊 Telecom_X_EDA.ipynb # Notebook principal com a análise e visualizações
├── 📁 data/
│ └── clientes.json (https://raw.githubusercontent.com/ingridcristh/challenge2-data-science/refs/heads/main/TelecomX_Data.json) # Base de dados bruta fornecida no github
├── 📁 imgs/
│ ├── churn_por_servico.png # Gráfico de cancelamento por tipo de serviço
│ ├── correlacao.png # Heatmap de correlação entre variáveis
│ └── outras_visualizacoes/ # Demais gráficos gerados durante a EDA
└── 📁 outputs/
└── relatorio_final.pdf # Relatório com insights e recomendações estratégicas

---

## 📈 Exemplos de Gráficos e Insights Obtidos

### 🔍 Cancelamento por Tipo de Serviço
![Churn por Serviço](imgs/churn_por_servico.png)

- **Insight**: Clientes que utilizam serviços como *Streaming TV* e *Suporte Técnico Online* apresentam maior taxa de churn.

---

### 🔥 Mapa de Correlação entre Variáveis
![Correlação](imgs/correlacao.png)

- **Insight**: Há forte correlação entre contratos mensais e evasão. Clientes com contratos mensais são mais propensos a cancelar o serviço.

---

### 💡 Outros Destaques:
- Clientes com faturas mais altas tendem a cancelar com mais frequência.
- O tempo de permanência do cliente está negativamente correlacionado com o churn.
- Serviços adicionais mal comunicados podem gerar cancelamentos por frustração ou má experiência.

---

## ⚙️ Como Executar o Notebook

Para replicar a análise localmente, siga os passos abaixo:

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Ana-Jessica/Challenge2_Alura.git
   cd Challenge2_Alura
