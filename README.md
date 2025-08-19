# TelecomX - Pt.2

## Descrição do Projeto
Este projeto realiza a **previsão de evasão de clientes (Churn Prediction)** para a empresa TelecomX. 
A análise inclui:
- Pré-processamento de dados (remoção de colunas irrelevantes, tratamento de valores ausentes, encoding)
- Análise exploratória e visualização de correlação
- Balanceamento de classes com SMOTE
- Criação de modelos preditivos: Regressão Logística e Random Forest
- Avaliação de desempenho dos modelos
- Identificação das variáveis mais importantes para evasão

O objetivo é auxiliar a empresa a identificar clientes com risco de evasão e propor estratégias de retenção.

---

## Estrutura de Pastas

TelecomX--Pt.2/
- TelecomX--Pt.2.ipynb      # Notebook principal
- LICENSE                      # Licença do projeto
- README.md                     # Este arquivo
- requirements.txt             # Dependências do Python

---

## Instalação das Dependências
Crie um ambiente virtual (opcional):

No Linux / Mac:
python -m venv venv
source venv/bin/activate

No Windows:
python -m venv venv
venv\Scripts\activate

Instale as bibliotecas necessárias:
pip install -r requirements.txt

---

## Como Rodar o Notebook
1. Abra o Jupyter Notebook:
jupyter notebook

2. Navegue até a pasta `notebooks` e abra `TelecomX--Pt.2.ipynb`.

3. Execute célula por célula, na seguinte ordem:
   1. Carregamento e exploração de dados
   2. Pré-processamento (remoção de colunas, encoding, tratamento de valores ausentes)
   3. Análise de correlação e gráficos direcionados
   4. Balanceamento com SMOTE
   5. Modelagem preditiva
   6. Avaliação dos modelos
   7. Interpretação das variáveis mais importantes

## Dataset
O dataset `dados_tratados.csv` contém informações dos clientes da TelecomX, como:
- Tempo de contrato (Tenure)
- Tipo de serviço
- Total gasto
- Variáveis de churn (`Churn`) e outras categorias

**Observação:** O arquivo deve estar na pasta `dados/` para que o notebook funcione corretamente.

## Autor
Braian Mezalira


