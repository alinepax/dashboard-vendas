
## 📊 Dashboard de Vendas

Projeto de análise de vendas desenvolvido para fins de aprendizado e portfólio.  
Os dados foram tratados e explorados com Excel, Python (Pandas, Seaborn, Matplotlib) e visualizados no Power BI.

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
├── excel/
│   ├── dashboard_vendas.xlsx
│   └── imagem-vendas-excel.png
│
├── powerbi/
│   ├── dados_vendas.csv
│   ├── dashboard-vendas.pbix
│   └── painel-powerbi.png
│
├── python/
│   ├── img/
│   |   ├── distribuicao_vendas_regiao.png
│   |   ├── participacao_produto_vendas.png
│   |   ├── produtos_mais_vendidos.png
│   |   ├── receita_por_regiao.png
|   |   └── total_vendas_regiao.png
│   └── insights/
│   |   ├── distribuicao_vendas_regiao.md
│   |   ├── participacao_produto_vendas.md
│   |   ├── produtos_mais_vendidos.md
│   |   ├── receita_por_regiao.md
│   |   ├── ticket_medio.md
|   |   ├── total_vendas_categoria.md
|   |   └── total_vendas_regiao.png
│   ├── notebooks
│   └── requirements.txt
│
└── README.md
```


---

## 📈 Funcionalidades dos Dashboards

- KPIs principais: Faturamento, Quantidade Vendida e Ticket Médio  
- Filtros por Região e Produto  
- Gráficos dinâmicos e interativos  
- Layout limpo, moderno e personalizado com cores e ícones

---

## 🧰 Ferramentas Utilizadas

- ✅ Microsoft Excel
- ✅ Power BI Desktop
- ✅ Python (Pandas, Seaborn, Matplotlib)
- 🎨 Design de ícones (Canva/Figma)

---

## 🖼️ Prévia dos Dashboards

### 🟢 Excel

![Painel Excel](excel/imagem-dashboard-excel.png)

### 🔵 Power BI

![Painel Power BI](powerbi/painel-powerbi.png)

---

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

### 📌 Como Reproduzir o Projeto

#### 🧾 Requisitos

| Ferramenta     | Versão Recomendável |
|----------------|---------------------|
| Excel          | 2016 ou superior (com suporte a gráficos e segmentações) |
| Power BI       | Power BI Desktop (versão gratuita) – [Baixar aqui](https://powerbi.microsoft.com/pt-br/downloads/) |

#### 🗂️ Passos

##### 📗 Excel

1. Acesse a pasta `excel/` no repositório.
2. Baixe o arquivo `dashboard-vendas.xlsx`.
3. Abra no Excel (recomenda-se ativar edição e conteúdo, se solicitado).
4. Explore o dashboard e as segmentações interativas.

##### 📘 Power BI

1. Acesse a pasta `powerbi/` no repositório.
2. Baixe o arquivo `dashboard-vendas.pbix`.
3. Abra no **Power BI Desktop**.
4. Visualize o painel completo e interaja com os filtros e KPIs.

#### ⚠️ Observações

- Os dados utilizados estão disponíveis na pasta `powerbi/` no arquivo `dados_vendas.csv`.
- Não é necessário instalar complementos para abrir nenhum dos arquivos.
- As segmentações e filtros funcionam melhor se os arquivos forem abertos diretamente nos softwares indicados (Excel e Power BI Desktop).


---

## 👩‍💻 Sobre a Autora

Desenvolvido por **[Aline Paz](https://github.com/alinepax)**  
📫 Me encontre no [LinkedIn](https://www.linkedin.com/in/alinedapaz/)  
📧 Email para parcerias: aline.santospaz@gmail.com  
🎯 Este projeto faz parte do meu portfólio como profissional em transição para a área de Dados e Tecnologia.

---

⭐ Se você gostou, deixe uma estrela no repositório!
