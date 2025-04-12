
## 📊 Dashboard de Vendas

Projeto de análise de vendas desenvolvido para fins de aprendizado e portfólio.  
Os dados foram tratados e explorados com Excel, Python (Pandas, Seaborn, Matplotlib, SQL (SQLite) e visualizados no Power BI.

OBS.: Os dados são fictícios e representam uma base de vendas com informações de regiões, produtos e valores.

### 🎯 Objetivos do projeto:
- Exibir **indicadores comerciais importantes** de forma clara e visual
- Criar painéis com foco em **tomada de decisão**
- Aplicar conceitos de **KPI** (indicadores de desempenho)
- Analisar os dados de vendas para gerar **insights estratégicos**, visualizações claras e treinar habilidades com ferramentas de dados.

Este é um projeto do meu portfólio como estudante de **Ciência de Dados**, com foco em **análise visual** e **interpretação de métricas de negócio**. Espero que goste! 💜

---

## 📁 Estrutura do Repositório

```
dashboard-vendas/
├── data/                         # Base de dados usada na análise
│   └── vendas.db                 # Banco de dados SQLite com os dados de vendas
|
├── excel/ 
│   ├── dashboard_vendas.xlsx     # Dashboard criado no Excel
│   └── imagem-vendas-excel.png   # Print do dashboard
│
├── powerbi/
│   ├── dados_vendas.csv          # Fonte de dados utilizada
│   ├── dashboard-vendas.pbix     # Dashboard criado no Power BI
│   └── painel-powerbi.png        # Print do painel no Power BI
│
├── python/
│   ├── img/                      # Gráficos gerados pelo Python
│   ├── insights/                 # Insights obtidos pela análise dos gráficos
│   ├── notebooks/                # Arquivo Python
│   └── requirements.txt          # Dependências para rodar os notebooks
|
├── sql/                          # Análise usando SQL no Jupyter
│   └── notebook-sql.ipynb        # Notebook com análises SQL usando SQLite
|
└── README.md                     # Documentação do projeto
```

---

## 🧰 Ferramentas Utilizadas

- ✅ Microsoft Excel — para criação de dashboards com Tabelas Dinâmicas e segmentações
- ✅ Power BI Desktop  — para visualizações interativas e filtros dinâmicos
- ✅ Python (Pandas, Seaborn, Matplotlib) — para análise exploratória e visualizações
- ✅ SQLite — consultas SQL usando banco de dados relacional
- ✅ Jupyter Notebook — ambiente interativo para execução das análises em Python e SQL
- 🎨 Design de ícones e layout — criados com Canva/Figma para deixar os dashboards mais visuais


---

## 📈 Funcionalidades dos Dashboards

- KPIs principais: Faturamento, Quantidade Vendida e Ticket Médio  
- Filtros por Região e Produto  
- Gráficos dinâmicos e interativos  
- Layout limpo, moderno e personalizado com cores e ícones

---

## 🖼️ Prévia dos Dashboards

### 🟢 Excel

![Painel Excel](excel/imagem-dashboard-excel.png)

### 🔵 Power BI

![Painel Power BI](powerbi/painel-powerbi.png)

## 📌 Índice de Insights (Python)

Abaixo estão os insights extraídos a partir da análise com Python. Cada item contém uma explicação e visualização gerada com bibliotecas como Pandas, Seaborn e Matplotlib:

- [Distribuição das Vendas por Região](python/insights/distribuicao_vendas_regiao.md): Entenda como as vendas estão distribuídas geograficamente.
- [Participação de Cada Produto nas Vendas](python/insights/participacao_produto_vendas.md): Veja quais produtos dominam a receita total.
- [Produtos Mais Vendidos](python/insights/produtos_mais_vendidos.md): Descubra quais itens lideram em volume de vendas.
- [Receita por Região](python/insights/receita_por_regiao.md): Compare o faturamento obtido em cada localidade.
- [Ticket Médio por Produto ou Região](python/insights/ticket_medio.md): Analise o valor médio gasto por cliente em cada compra.
- [Total de Vendas por Categoria](python/insights/total_vendas_categoria.md): Observe quais categorias geraram maior receita.

## 📌 Índice de Insights (SQLite)

Abaixo estão os insights extraídos a partir da análise com SQLite. Cada item contém uma explicação e visualização gerada com bibliotecas como Pandas, Seaborn e Matplotlib:

- [Produtos Mais Vendidos](sql/insights/produtos_mais_vendidos_sql.md): Descubra quais itens lideram em volume de vendas.
- [Receita por Categoria](sql/insights/total_vendas_categoria_sql.md): Compare o faturamento obtido de cada categoria.
- [Vendas por Região](sql/insights/vendas_por_regiao_sql.md): Compare o faturamento obtido em cada localidade.

## 📗 Detalhes da Versão Excel

Este projeto foi criado no Excel com foco na visualização de dados de vendas. Utilizei Tabelas Dinâmicas, Segmentações de Dados e formatações condicionais para destacar os principais indicadores.

### KPIs incluídos:
- **Faturamento Total**
- **Quantidade Vendida**
- **Ticket Médio**

### Gráficos:
- Gráfico de colunas (Faturamento por Região)
- Gráfico de colunas (Faturamento por Produto)

### Recursos adicionais:
- Segmentação de dados para facilitar a análise por região e produto
- Estilo visual padronizado com cores consistentes
- Disposição dos elementos priorizando clareza e foco nos KPIs

📎 Arquivo: `excel/dashboard-vendas.xlsx`  
🖼️ Imagem: `excel/imagem-dashboard-excel.png`

---

## 📘 Detalhes da Versão Power BI

O painel desenvolvido no Power BI tem como foco a visualização clara e interativa dos dados de vendas. Foram utilizados elementos visuais modernos, ícones personalizados e filtros dinâmicos para melhorar a experiência do usuário.

### KPIs incluídos:
- 💰 **Valor Total das Vendas**
- 📦 **Quantidade Vendida**
- 💳 **Ticket Médio**

### Gráficos utilizados:
- 📊 Gráfico de colunas agrupadas (Quantidade por Produto e por Região)
- 🥧 Gráfico de pizza (Participação das Regiões no Valor Total)
- 🔢 Cartões com KPIs (valores agregados)

### Interatividade:
- 🔘 Segmentações por Produto e Região
- 🔄 Interações entre gráficos e KPIs
- 🖼️ Ícones visuais personalizados para destacar as métricas

📎 Arquivo: `powerbi/dashboard-vendas.pbix`  
🖼️ Imagem: `powerbi/painel-powerbi.png`

---

## 📙 Detalhes da Versão Python

A etapa em Python foi responsável pelo tratamento e análise inicial dos dados de vendas. Utilizei bibliotecas como **Pandas**, **Seaborn** e **Matplotlib** para gerar visualizações e insights antes da construção dos dashboards finais.

### Bibliotecas utilizadas:
- `pandas` para manipulação de dados
- `matplotlib` e `seaborn` para visualizações
- `os` e `pathlib` para manipulação de diretórios

### Análises realizadas:
- 📍 Distribuição das vendas por região
- 💼 Receita total por categoria de produto
- 🧮 Cálculo do ticket médio
- 📊 Participação de cada produto nas vendas
- 🔍 Identificação dos produtos mais vendidos

📁 Os gráficos gerados estão na pasta: `python/img/`  
📄 Os insights estão descritos em: `python/insights/`  
📜 Para instalar as dependências, utilize o `requirements.txt`.

### Como executar:

1. Acesse a pasta `python/`
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook ou scripts disponíveis para visualizar os gráficos e análises geradas.

📎 Notebooks e scripts: `python/notebooks/`  
📜 Dependências: `python/requirements.txt`

---

## 🧮 Detalhes da Versão SQL (SQLite)

Além das análises em Python, o projeto conta com uma versão que utiliza **SQLite** para armazenar e consultar os dados de vendas de forma relacional. Essa etapa foi desenvolvida em um notebook Jupyter, demonstrando como a linguagem SQL pode ser aplicada para gerar insights com consultas diretas no banco de dados.

### Ferramentas e Tecnologias:
- `sqlite3` para criação e conexão com o banco de dados
- `pandas` para conversão dos dados e visualização das consultas
- `Jupyter Notebook` como ambiente interativo de análise

### Principais Consultas Realizadas:
- 🔹 **Faturamento total por produto**
- 🔹 **Média de vendas por região**
- 🔹 **Produtos mais vendidos**
- 🔹 **Análise por categoria**

📎 Notebook: `sql/notebook-sql.ipynb`  
🗃️ Banco de dados: `data/vendas.db`

### Como executar:

```bash
pip install notebook
cd sql/
jupyter notebook notebook-sql.ipynb
```

---

## 👩‍💻 Sobre a Autora

Desenvolvido por **[Aline Paz](https://github.com/alinepax)**  
📫 Me encontre no [LinkedIn](https://www.linkedin.com/in/alinedapaz/)  
📧 Email para parcerias: aline.santospaz@gmail.com  
🎯 Este projeto faz parte do meu portfólio como profissional em transição para a área de Dados e Tecnologia.

---

⭐ Se você gostou, deixe uma estrela no repositório!

---

## 📄 Licença

Este projeto está licenciado sob os termos da **[Licença MIT](https://opensource.org/licenses/MIT)**.  
Sinta-se à vontade para usar, modificar e compartilhar com os devidos créditos.
