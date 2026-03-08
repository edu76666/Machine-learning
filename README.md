# 📊 Previsão de Score de Crédito com Machine Learning

Projeto de Machine Learning para prever o score de crédito de clientes (Poor, Standard ou Good) a partir de uma base com 100.000 registros.

Desenvolvido durante a **Jornada Python** da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com).

---

## 🔍 Sobre o Projeto

A partir de uma base com 100 mil clientes, dois modelos de Machine Learning foram treinados e comparados para prever o score de crédito. O modelo com melhor acurácia foi utilizado para classificar novos clientes.

**Resultados:**
- Random Forest: ~82% de acurácia
- KNN: ~73% de acurácia
- Modelo escolhido: **Random Forest**

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Fluxo do Projeto

1. Carregamento e visualização dos dados
2. Codificação de variáveis categóricas com `LabelEncoder`
3. Separação em treino e teste com `train_test_split`
4. Treinamento de dois modelos: `RandomForestClassifier` e `KNeighborsClassifier`
5. Comparação de acurácia entre os modelos
6. Previsão do score de novos clientes

---

## 📁 Estrutura do Projeto

```
score-credito-ml/
│
├── main.ipynb              # Notebook com o projeto completo
├── clientes.csv            # Base de dados de treinamento
└── novos_clientes.csv      # Base de novos clientes para previsão
```

---

## ▶️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/edu76666/score-credito-ml
```

2. Instale as dependências:
```bash
pip install pandas scikit-learn
```

3. Abra o notebook:
```bash
jupyter notebook main.ipynb
```

---

## 📌 Créditos

Projeto desenvolvido com base no conteúdo da **Jornada Python** da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com).