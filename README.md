# 📉 Análise de Cancelamento de Clientes

Este projeto é um estudo em Python focado em entender os principais motivos que levam clientes a cancelarem seus contratos com uma empresa fictícia de serviços. A ideia aqui é aplicar análise de dados, explorando o processo completo: desde o tratamento da base até a geração de insights com visualizações gráficas.

## 🧠 Objetivo

Identificar padrões e comportamentos que levam ao cancelamento de clientes e simular possíveis soluções para reduzir essa taxa.

## 📊 Etapas da Análise

1. **Importação da Base**  
   Leitura do arquivo CSV contendo os dados dos clientes.

2. **Tratamento de Dados**

   - Remoção de colunas irrelevantes
   - Eliminação de valores nulos
   - Verificação e ajuste de tipos de dados

3. **Análise Inicial**  
   Cálculo da quantidade e percentual de clientes que cancelaram.

4. **Visualização Gráfica**  
   Geração de histogramas para cada variável, destacando a relação com o cancelamento.

5. **Análise Final (Simulação de Ações)**  
   Simulação de ações estratégicas para reduzir o cancelamento com base em padrões identificados:
   - Clientes que ligam muitas vezes para o call center
   - Clientes com muitos dias de atraso
   - Clientes com contrato mensal

## 📈 Resultados

Após simular a solução dos principais problemas, a taxa de cancelamento caiu consideravelmente. Os gráficos e filtros de dados deixaram evidente quais pontos precisam de atenção.

## 🚀 Tecnologias Usadas

- Python
- Jupyter Notebook
- Pandas
- Plotly
- Git LFS (para arquivos grandes)

## 🛠️ Como rodar localmente

1. Instale os pré-requisitos:

   - Git
   - Git LFS
   - Python
   - Jupyter Notebook

2. Clone o repositório com Git LFS ativado:

```bash
git lfs install
```

```bash
git clone https://github.com/JosielJrr/analise-cancelamento-clientes.git
```

## ⚠️ Importante sobre arquivos grandes

Este projeto usa Git LFS para armazenar arquivos grandes como notebooks e bases de dados.
Se você não tiver o Git LFS instalado, esses arquivos não serão baixados corretamente.

## 📌 Observação

Esse projeto tem fins educacionais. Os dados são fictícios e a ideia aqui é treinar habilidades de análise de dados com Python.

> Projeto criado na **Jornada Python** da [Hashtag Programação](https://www.youtube.com/@HashtagProgramacao).
