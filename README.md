# 📊 Dashboard de Análise Financeira

<!-- Exemplo de imagem do topo -->

## 📌 Descrição

Este projeto consiste em um **Dashboard Interativo para análise** de dados financeiros, permitindo a visualização e interpretação de métricas essenciais como:

 - Receitas

 - Despesas

 - Lucro líquido

 - Comparação de períodos

 - Distribuição por categorias
   
 - Visualização da Bolsa de valores
   
 - Comparação de investimentos e dividendos

O objetivo é fornecer uma visão clara e dinâmica para auxiliar na tomada de decisões financeiras.

## 🚀 Funcionalidades

 - 📈 Gráficos Interativos (linhas, barras, pizza, etc.)

 - 📊 Filtros Dinâmicos por data, categoria e região

 - 🏦 Análise de Receita x Despesa

 - 📅 Comparação Anual e Mensal

 - 📤 Exportação de Relatórios (PDF e Excel)

## 🛠️ Tecnologias Utilizadas

 - **Linguagem:** Python
   
 - **Frontend (UI/UX):** React + Tailwind

 - **Bibliotecas:**

   - pandas (manipulação de dados)

   - plotly (gráficos interativos)

   - dash (interface web)

   - openpyxl (exportação Excel)

  - **Banco de Dados:** PostgreSQL

  - **Outros:** Docker, Git

<pre>📦 dashboard-financeiro
├── 📁 backend                # Parte em Python (API + lógica de dados)
│   ├── 📁 data               # Arquivos CSV/Excel
│   ├── 📁 src
│   │   ├── app.py            # API principal (FastAPI ou Flask)
│   │   ├── data_processing.py # Funções de tratamento de dados
│   │   ├── charts.py         # Criação dos gráficos (opcional: gerar dados e enviar p/ frontend)
│   │   └── config.py         # Configurações do projeto
│   ├── requirements.txt      # Dependências Python
│   ├── Dockerfile            # Docker para backend
│   └── README.md
│
├── 📁 frontend               # Parte em React + Vite + Tailwind (interface)
│   ├── 📁 public             # Arquivos estáticos (favicon, etc.)
│   ├── 📁 src
│   │   ├── App.jsx           # Componente principal
│   │   ├── main.jsx          # Ponto de entrada do React
│   │   ├── index.css         # Tailwind base
│   │   └── components/       # Botões, gráficos, tabelas, etc.
│   ├── package.json          # Dependências JS
│   ├── vite.config.js        # Configuração do Vite
│   └── tailwind.config.js    # Configuração do Tailwind
│
└── README.md                 # Documentação geral do projeto
</pre>

## 📸 Demonstração

Exemplo de Tela do Dashboard:


Gráfico Interativo de Receita vs Despesa:


## 📦 Como Instalar e Rodar
<!-- 1️⃣ Clonar o repositório
git clone https://github.com/seuusuario/dashboard-financeiro.git
cd dashboard-financeiro

2️⃣ Criar ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

3️⃣ Instalar dependências
pip install -r requirements.txt

4️⃣ Executar aplicação
python src/app.py


Acesse http://localhost:8050 no navegador. -->

## 📊 Fonte dos Dados

- Os dados utilizados neste projeto são reais, extraídos de relatórios públicos e bases como:

- Banco Central do Brasil

- IBGE

- Yahoo Finance

## 🤝 Contribuindo

**Contribuições são bem-vindas!**
 - Para contribuir:

 - Faça um fork do repositório

 - Crie uma nova branch (git checkout -b minha-feature)

 - Faça suas alterações e commit

 - Envie um pull request

## 📝 Licença

Este projeto está sob a licença MIT.
Veja o arquivo LICENSE para mais detalhes.
