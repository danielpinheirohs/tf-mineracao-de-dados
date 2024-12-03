# Trabalho Final de Mineração de Dados

Este repositório contém os artefatos produzidos ao longo do trabalho final da disciplina de Mineração de Dados. Para facilitar o entendimento da ordem de precedência dos arquivos, organizamos as instruções a seguir:

---

## Estrutura do Projeto

1. **Pasta [`data`](./data)**: 
   Contém os dados utilizados e gerados pelos notebooks ao longo do trabalho.

2. **Limpeza dos Dados**:
   - Arquivo: [`limpeza.ipynb`](./limpeza.ipynb)
   - Com o dataset original [`UCMF.csv`](./data/UCMF.csv) em mãos, realizamos a limpeza dos dados para remover inconsistências e valores desnecessários.
   - **Output gerado**: [`UCMF_limpo.csv`](./data/UCMF_limpo.csv)

3. **Análise e Interpretação**:
   - Arquivo: [`analise_e_interpretacao.ipynb`](./analise_e_interpretacao.ipynb)
   - Com o dataset limpo (`UCMF_limpo.csv`), realizamos uma análise e interpretação inicial dos dados. Essa etapa foi essencial para identificar insights e direcionar as abordagens seguintes.

4. **Transformação dos Dados**:
   - Arquivo: [`transformacao.ipynb`](./transformacao.ipynb)
   - Após a análise, transformamos os dados para facilitar o uso em modelos, como árvores de decisão e outros algoritmos.
   - **Output gerado**: [`UCMF_preprocessado.csv`](./data/UCMF_preprocessado.csv)

5. **Modelagem e Aplicação de Algoritmos**:
   - Arquivo: [`modelagem.ipynb`](./modelagem.ipynb)
   - Com os dados transformados, aplicamos algoritmos e modelos de IA, incluindo:
     - **Decision Tree Classifier**
     - **Random Forest**
     - **Logistic Regression Classifier**
   - Além disso, realizamos análises gráficas para validação e interpretação dos resultados.

---

## Conclusão

Ao final do projeto, concluímos a modelagem dos dados com os melhores algoritmos e abordagens, apresentando tanto os resultados quantitativos quanto visuais. Todo o fluxo do trabalho pode ser acompanhado nos arquivos mencionados acima.

---

### Autores: Daniel Pinheiro | Pedro Saraiva | Anna Pietra | Carlos Henrique

