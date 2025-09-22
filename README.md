# 💳 Análise de Score de Crédito de Clientes

Este projeto tem como objetivo analisar uma base de clientes e calcular o **score de crédito** de cada um, classificando-os em três categorias:

- **Boa (Good)** → Clientes com bom histórico e baixo risco.  
- **Ok (Standard)** → Clientes medianos, risco moderado.  
- **Ruim (Poor)** → Clientes de alto risco de inadimplência.  

A análise foi feita em **Python** através de um Jupyter Notebook.

---

## 🚀 Objetivos do Projeto

- Avaliar clientes com base em informações financeiras e de perfil.  
- Calcular um **score de crédito** que auxilia em decisões de concessão de crédito.  
- Segmentar os clientes em **categorias de risco**.  
- Apoiar áreas de **financeiro, cobrança e marketing** na tomada de decisão.  

---

## 📂 Estrutura do Projeto

```
📦 projeto-score-credito
 ┣ 📜 inicial.ipynb       # Notebook principal com a análise
 ┣ 📜 clientes.csv        # Base com os clientes atuais
 ┣ 📜 novos_clientes.csv  # Base com novos clientes para análise
 ┗ 📜 README.md           # Documentação do projeto
```

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- [Pandas](https://pandas.pydata.org/) → Manipulação e análise de dados  
- [NumPy](https://numpy.org/) → Operações matemáticas  
- [Plotly](https://plotly.com/python/) / [Matplotlib](https://matplotlib.org/) → Visualizações  
- [Jupyter Notebook](https://jupyter.org/) → Ambiente de análise  

---

## 📊 Estrutura das Bases de Dados

### `clientes.csv`
Contém informações dos clientes atuais, como:
- **ID** → Identificação única do cliente  
- **Idade**  
- **Renda**  
- **Histórico de pagamento**  
- **Categoria de contrato**  
- **Score** → Avaliação calculada (Boa, Ok, Ruim)  

### `novos_clientes.csv`
Contém dados de potenciais clientes para os quais será calculado o score de crédito.

---

## 📈 Passos da Análise

1. **Carregar as bases de dados** (`clientes.csv` e `novos_clientes.csv`).  
2. **Tratar os dados** (remoção de inconsistências e valores nulos).  
3. **Definir critérios para cálculo do score** com base em variáveis como:
   - Atrasos em pagamentos.  
   - Histórico financeiro.  
   - Faixa de renda.  
   - Tipo de contrato.  
4. **Classificação do cliente** em:
   - **Boa (Good)** → baixo risco.  
   - **Ok (Standard)** → risco moderado.  
   - **Ruim (Poor)** → alto risco.  
5. **Geração de relatórios e gráficos** para visualizar a distribuição dos clientes por categoria de score.  

---

## ▶️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-score-credito.git
   ```
2. Instale as dependências:
   ```bash
   pip install pandas numpy matplotlib plotly notebook
   ```
3. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook inicial.ipynb
   ```
4. Execute as células em sequência para reproduzir a análise e calcular os scores.  

---

## 📊 Exemplos de Insights

- Percentual de clientes classificados como **Boa, Ok e Ruim**.  
- Correlação entre **renda** e **score de crédito**.  
- Identificação de variáveis mais relevantes no risco de inadimplência.  

---
