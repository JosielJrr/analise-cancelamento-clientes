# 📉 Análise de Cancelamento de Clientes

Este projeto é um estudo em Python que busca entender os principais motivos pelos quais clientes cancelam seus contratos com uma empresa fictícia de serviços. A ideia é aplicar análise de dados explorando todo o processo: do tratamento da base à geração de insights com visualizações gráficas.

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
   Simulação de estratégias para reduzir o cancelamento com base nos padrões identificados:
   - Clientes que ligam muitas vezes para o call center
   - Clientes com muitos dias de atraso
   - Clientes com contrato mensal

## 📈 Resultados

Após simular a resolução dos principais problemas, a taxa de cancelamento caiu consideravelmente. Os gráficos e filtros deixaram claro quais pontos precisam de atenção.

## 🚀 Tecnologias Usadas

- Python
- Jupyter Notebook
- Pandas
- Plotly
 
## 🛠️ Como rodar localmente

1. Instale os pré-requisitos:

   - [Git](https://git-scm.com/downloads)
   - [Git LFS](https://git-lfs.com/)
   - [Python](https://www.python.org/downloads/)
   - [Jupyter Notebook](https://jupyter.org/install)

2. Clone o repositório com Git LFS ativado:

```bash
git lfs install
git clone https://github.com/JosielJrr/analise-cancelamento-clientes.git
```

## ⚠️ Importante sobre arquivos grandes

Este projeto usa [Git LFS](https://git-lfs.com/) para armazenar arquivos grandes como notebooks e bases de dados.
Se o Git LFS não estiver instalado, esses arquivos não serão baixados corretamente.

## 📌 Observação

Este projeto tem fins educacionais. Os dados são fictícios e a proposta é praticar análise de dados com Python.

> Projeto criado na **Jornada Python** da [Hashtag Programação](https://www.youtube.com/@HashtagProgramacao).
