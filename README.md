# Previsão da Qualidade do Sono

Este projeto busca prever a qualidade do sono de indivíduos, permitindo que profissionais avaliem o risco de distúrbios do sono com base em dados de saúde, hábitos diários e sinais fisiológicos.

## Instalação e Execução

- Você precisará baixar os arquivos 01_eda.ipynb, 02_preprocessing.ipynb, 03_training.ipynb, 04_evaluation.ipynb, 05_inference.ipynb e sleep_quality_model.pkl.

- Para executar esse código basta clicar [aqui](00_main.ipynb), depois no ícone "Open in Colab" que aparecerá no topo do código. Após isso coloque os arquivos baixados no /content do google colab e, finalmente, ir em "Ambiente de execução" e clicar em "Executar tudo".

## Pesos do Modelo

Os pesos do modelo treinado estão salvos no arquivo:

sleep_quality_model.pkl


Esse arquivo é gerado no notebook 03_training.ipynb e utilizado no 05_inference.ipynb para realizar a inferência da qualidade do sono em novos pacientes.

```

## Métricas

As métricas de desempenho (RMSE, MAE e R²) e comparações entre modelos estão disponíveis na pasta:

results/

```

---
