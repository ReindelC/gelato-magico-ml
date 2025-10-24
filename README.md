# 🍦 Prevendo Vendas de Sorvete com Machine Learning 📊

## 📌 Sobre o Desafio
Este projeto foi desenvolvido como parte do desafio **"Prevendo Vendas de Sorvete com Machine Learning"**.  
O objetivo é aplicar conceitos de **Machine Learning** para prever as vendas de sorvete com base na **temperatura do dia**, ajudando sorveterias a planejarem melhor sua produção, reduzindo desperdícios e aumentando os lucros.

---

## 🎯 Objetivos
- ✅ Treinar um modelo de regressão para prever vendas de sorvete a partir da temperatura.  
- ✅ Registrar e gerenciar o modelo usando **MLflow**.  
- ✅ Implementar o modelo para previsões em tempo real em ambiente de cloud computing.  
- ✅ Criar um pipeline estruturado para garantir reprodutibilidade.  

---

## 📂 Estrutura do Repositório
gelato-magico-ml │ ├── inputs/              # Arquivos de entrada (frases, dados, etc.) │   └── frases.txt │ ├── notebooks/           # Notebooks Jupyter com experimentos │   └── modelo_sorvete.ipynb │ ├── src/                 # Scripts de treinamento e predição │   ├── train.py │   ├── predict.py │   └── pipeline.py │ ├── requirements.txt     # Dependências do projeto └── README.md            # Documentação do projeto


---

## 🧪 Metodologia
1. **Coleta de dados**: foram utilizadas temperaturas médias e vendas diárias simuladas.  
2. **Pré-processamento**: divisão em treino e teste.  
3. **Treinamento**: modelo de **Regressão Linear**.  
4. **Avaliação**: métrica R² para medir a qualidade da previsão.  
5. **Registro**: uso do **MLflow** para versionamento do modelo.  
6. **Deploy**: criação de uma API simples com **FastAPI** para previsões em tempo real.  

---

## 📊 Resultados
- O modelo apresentou um **R² de aproximadamente 0.9**, indicando boa capacidade de previsão.  
- Observou-se que a cada aumento de **1°C**, as vendas crescem em média **X unidades** (valor obtido no treino).  

📷 *Aqui você pode inserir prints do notebook com gráficos de dispersão, linha de regressão e métricas.*  

---

## 💡 Insights
- O consumo de sorvete tem forte correlação com a temperatura.  
- Sabores refrescantes (limão, menta, frutas tropicais) tendem a vender mais em dias muito quentes.  
- Promoções em dias de calor extremo podem aumentar ainda mais a demanda.  
- Em dias nublados, sabores mais doces (como chocolate) mantêm boa saída.  

---
