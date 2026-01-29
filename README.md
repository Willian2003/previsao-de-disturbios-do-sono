# Previsão da Qualidade do Sono

Este projeto busca prever a qualidade do sono de indivíduos, permitindo que profissionais avaliem o risco de distúrbios do sono com base em dados de saúde, hábitos diários e sinais fisiológicos.



## Estrutura do Repositório

```

previsao-da-qualidade-do-sono/
│
├── notebooks/
│ ├── 01_eda.ipynb
│ ├── 02_preprocessing.ipynb
│ ├── 03_training.ipynb
│ ├── 04_evaluation.ipynb
│ └── 05_inference.ipynb
│
├── data/
│ ├── Sleep_health_and_lifestyle_dataset.csv
│ └── dataframe.csv
│
├── models/
│ └── sleep_quality_model.pkl
│
├── results/
│ ├── linear_results.csv
│ ├── tree_results.csv
│ ├── rf_results.csv
│ ├── comparison.csv
│ └── comparison_overfit.csv
│
├── requirements.txt
└── README.md

```

## Instalação

Criar um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

pip install -r requirements.txt

```

## Execução do Pipeline

```

Os notebooks devem ser executados na seguinte ordem:

01_eda.ipynb
Análise Exploratória de Dados (EDA).

02_preprocessing.ipynb
Limpeza, transformação dos dados, codificação One-Hot e geração do arquivo dataframe.csv.

03_training.ipynb
Treinamento dos modelos de Regressão Linear, Árvore de Decisão e Random Forest, além do salvamento do modelo final.

04_evaluation.ipynb
Avaliação de desempenho, comparação entre modelos e análise de overfitting.

05_inference.ipynb
Carregamento do modelo treinado e realização de previsões para novos dados.

```

## Pesos do Modelo

Os pesos do modelo treinado estão salvos no arquivo:

models/sleep_quality_model.pkl


Esse arquivo é gerado no notebook 03_training.ipynb e utilizado no 05_inference.ipynb para realizar a inferência da qualidade do sono em novos pacientes.

```

## Métricas

As métricas de desempenho (RMSE, MAE e R²) e comparações entre modelos estão disponíveis na pasta:

results/

```

---
