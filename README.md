## Análise Exploratória de Dados (EDA) - Hotel Booking Demand

 Este repositório contém a **1ª Etapa do Projeto Acadêmico** da disciplina **Fundamentos de Data Science e Inteligência Artificial**.

---

## Sobre o Projeto

O objetivo deste projeto é realizar uma Análise Exploratória de Dados (EDA) detalhada sobre o *dataset* **Hotel Booking Demand** (obtido no Kaggle), investigando os principais fatores e padrões comportamentais associados ao **cancelamento de reservas hoteleiras** (`is_canceled`).

Esta entrega prepara a base limpa e pré-processada para a construção de modelos preditivos de Machine Learning na próxima etapa do curso.

---

## Equipe e Instituição

*Disciplina: Eletiva - Fundamentos de Data Science e IA  
*Professor: Kelvin Frade Ribeiro  

Integrantes da Equipe:
  * [Luiz Claudio Martins]
  * [Gabriel Normandio]
  * [Pethrus Souza]
  

---

## Estrutura do Notebook (`eda_projeto_ia.ipynb`)

O arquivo principal segue as diretrizes do template oficial e está estruturado nas seguintes etapas:

1. **Escolha e Motivação:** Apresentação da base de dados e justificativa de escolha.
2. **Descrição e Classificação das Variáveis:** Mapeamento do conjunto de dados (119.390 registros e 32 colunas) e classificação das variáveis.
3. **Avaliação Descritiva e Pré-processamento:** Limpeza de valores nulos, remoção de inconsistências e conversão de tipos.
4. **Análises e Gráficos:**
   * **4.1 Distribuição dos Valores:** Análise de frequências (`is_canceled` e `lead_time`).
   * **4.2 Dependência entre Variáveis:** Relação do cancelamento com o tipo de hotel e modalidade de depósito.
   * **4.3 Correlação entre Variáveis:** Matriz de correlação de Pearson e *heatmap* com os principais achados.
5. **Conclusões:** Resumo executivo, *insights* estratégicos e próximos passos.

---

## Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python 3
* **Ambiente:** Google Colab
* **Manipulação de Dados:** `pandas`
* **Visualização de Dados:** `matplotlib`, `seaborn`

---

## Como Executar o Projeto

1. Baixe o arquivo `eda_projeto_ia.ipynb` deste repositório.
2. Abra o [Google Colab](https://colab.research.google.com/).
3. Faça o upload do notebook `eda_projeto_ia.ipynb`.
4. Envie o arquivo `hotel_bookings.csv` para a pasta de arquivos da sessão do Colab.
5. Execute todas as células no menu: **Ambiente de Execução > Executar tudo**.
```

---
