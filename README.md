# Segmentação de Clientes para Campanha de Marketing

Projeto acadêmico de análise de dados e aprendizado não supervisionado voltado à exploração e segmentação de clientes de uma campanha de marketing.

O objetivo é analisar características demográficas, familiares, financeiras e comportamentais dos clientes para identificar perfis e padrões que possam apoiar estratégias de comunicação, oferta e relacionamento mais direcionadas.

## Problema

Campanhas de marketing possuem públicos com perfis, comportamentos de compra e níveis de engajamento diferentes. Tratar todos os clientes da mesma forma pode reduzir a efetividade das ações e dificultar a definição de ofertas relevantes.

Este projeto explora dados de clientes para apoiar a identificação de segmentos com características semelhantes.

## Objetivo

- Explorar dados de clientes de uma campanha de marketing
- Preparar variáveis para análise e aprendizado não supervisionado
- Identificar padrões de consumo, renda, composição familiar e comportamento de compra
- Apoiar a criação de grupos de clientes com características semelhantes
- Gerar insights que possam contribuir para estratégias de marketing mais personalizadas

## Base de dados

O conjunto de dados utilizado foi adaptado de uma base de campanha de marketing para fins de aprendizado não supervisionado.

A base contém aproximadamente:

- **2.212 registros de clientes**
- **23 variáveis**

Entre as variáveis analisadas estão:

| Grupo | Exemplos de variáveis |
|---|---|
| Perfil demográfico | Educação, idade, estado civil ou condição de moradia |
| Perfil financeiro | Renda, gastos totais e gastos por categoria |
| Família | Crianças e adolescentes em casa, tamanho da família, indicador de parentalidade |
| Comportamento de compra | Compras pela web, catálogo, loja e compras com desconto |
| Engajamento digital | Visitas mensais ao site |
| Relacionamento | Tempo como cliente e recência de compra |

Algumas colunas presentes na base:

```text
Education
Income
Kidhome
Teenhome
Recency
MntWines
MntFruits
MntMeatProducts
MntFishProducts
MntSweetProducts
MntGoldProds
NumDealsPurchases
NumWebPurchases
NumCatalogPurchases
NumStorePurchases
NumWebVisitsMonth
Customer_For
Age
Spent
Living_With
Children
Family_Size
Is_Parent
```

## Tecnologias utilizadas

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Análise Exploratória de Dados (EDA)
- Aprendizado de Máquina Não Supervisionado
- Git e GitHub

> Adicione a biblioteca de agrupamento utilizada, como `scikit-learn`, somente se ela estiver realmente presente no notebook.

## Estrutura do repositório

```text
.
├── README.md
├── segmentacao-clientes-campanha-marketing.ipynb
├── marketing_campaign2.csv
├── requirements.txt
└── .gitignore
```

## Como executar localmente

### Pré-requisitos

- Python 3.10 ou superior
- Jupyter Notebook ou JupyterLab
- Git

### 1. Clone o repositório

```bash
git clone [https://github.com/diegovitor90/segmentacao-clientes-marketing.git](https://github.com/diegovitor90/segmentacao-clientes-marketing.git)
cd segmentacao-clientes-marketing
```

### 2. Crie e ative um ambiente virtual

```bash
python -m venv venv
```

#### Windows

```powershell
venv\Scripts\activate
```

#### Linux ou macOS

```bash
source venv/bin/activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Inicie o Jupyter

```bash
jupyter notebook
```

Depois, abra:

```text
segmentacao-clientes-campanha-marketing.ipynb
```

## Competências desenvolvidas

Neste projeto, pratiquei:

- Importação e manipulação de dados com Pandas
- Análise exploratória de dados
- Visualização de dados com Matplotlib e Seaborn
- Interpretação de variáveis demográficas e comportamentais
- Preparação de dados para aprendizado não supervisionado
- Análise de padrões de consumo e canais de compra
- Segmentação de clientes para apoio à tomada de decisão
- Documentação e versionamento com Git e GitHub

## Limitações atuais

Este é um projeto acadêmico voltado à exploração de dados e ao aprendizado de técnicas de segmentação.

Antes de utilizar resultados semelhantes em campanhas reais, seria necessário:

- Confirmar a origem, qualidade e atualidade dos dados
- Tratar valores ausentes, duplicados e outliers de forma documentada
- Garantir conformidade com privacidade e proteção de dados
- Validar a estabilidade e utilidade dos grupos identificados
- Definir métricas de negócio para avaliar os segmentos
- Testar campanhas com grupos de controle
- Monitorar resultados, vieses e mudanças de comportamento ao longo do tempo

## Próximas melhorias

- Documentar todas as etapas de limpeza e transformação dos dados
- Incluir dicionário de dados detalhado
- Adicionar visualizações e conclusões de negócio ao README
- Documentar o algoritmo de agrupamento utilizado
- Avaliar a quantidade ideal de clusters
- Comparar resultados com diferentes abordagens de agrupamento
- Criar perfis descritivos para cada segmento identificado
- Desenvolver um dashboard para exploração dos segmentos

## Autor

**Diego Vitor Lopes Gonçalves Souza**

- Estudante de Engenharia de Software — UNDB
- Especialização em Inteligência Artificial — UNDB
- GitHub: [diegovitor90](https://github.com/diegovitor90)
