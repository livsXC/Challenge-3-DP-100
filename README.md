# 🧊 Desafio: Previsão de Vendas de Sorvete com Machine Learning 🍦📈

Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever a quantidade de sorvetes vendidos em um dia com base na temperatura ambiente. O desafio simula a realidade de uma sorveteria chamada **Gelato Mágico**, localizada em uma cidade litorânea, onde a demanda por sorvete varia diretamente com o clima.

A proposta é usar técnicas de regressão preditiva para auxiliar no planejamento da produção diária, evitando desperdícios por excesso ou perda de vendas por falta de estoque. Além disso, o projeto envolve o registro do experimento utilizando **MLflow**, a construção de um pipeline reprodutível e a preparação para deploy em ambiente de nuvem.

---

## 🎯 Objetivos do Projeto

- Treinar um modelo preditivo de regressão com base na temperatura do dia.
- Analisar e visualizar a relação entre temperatura e vendas.
- Registrar o experimento com o **MLflow**, armazenando métricas e parâmetros.
- Criar uma estrutura organizada e reprodutível com pipeline de treinamento.
- Documentar e versionar o projeto em um repositório GitHub.

---

## 🧠 Tecnologias Utilizadas

- **Python**
- **Pandas** e **NumPy**
- **Matplotlib** e **Seaborn**
- **Scikit-learn**
- **MLflow**
- **Jupyter Notebook**

---

## 📁 Estrutura do Projeto

```bash
.
├── data/                  # Dados de entrada (CSV)
├── inputs/                # Frases e reflexões sobre o aprendizado
├── notebooks/             # Notebooks com análise e treinamento
├── pipeline/              # Código do pipeline automatizado
├── models/                # Modelo salvo
├── mlruns/                # Experimentos registrados com MLflow
├── README.md              # Documentação do projeto
├── requirements.txt       # Dependências do projeto
