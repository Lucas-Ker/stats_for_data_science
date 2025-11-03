# Fundamentos de Estatística Aplicada à Ciência de Dados

![Status](https://img.shields.io/badge/Status-Em%20Andamento%20(Evergreen)-blue)

Read this README in [English 🇺🇸](https://github.com/Lucas-Ker/stats_for_data_science/blob/main/README.md).

---

## 📄 Sobre o Projeto

Diferente de um projeto de análise único, este repositório funciona como um **"jardim digital"** e um **portfólio vivo** da minha jornada de aprendizado em estatística.

O objetivo é documentar, aplicar e explicar conceitos estatísticos fundamentais usando datasets do mundo real. Cada notebook é um "estudo de caso" focado em responder a uma pergunta específica usando a ferramenta estatística correta.

Este é um projeto em **constante evolução**. Ele será atualizado regularmente com novos notebooks, técnicas mais avançadas e refatorações, refletindo meu crescimento e aprofundamento contínuo na carreira de Ciência de Dados.

**Dataset:** Os dados analisados neste projeto vêm do conjunto de dados "Video Game Sales with Ratings", disponível no [Kaggle](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings).

---

## 📚 Tópicos e Conceitos Aplicados (Índice)


Esse repositório é organizado por tópicos. Cada notebook foca em um pilar da estatística e demonstra sua aplicação prática.

1.  **Análise Exploratória de Dados (EDA):** Aprender a resumir, visualizar e entender as principais características de um conjunto de dados.

2.  **Distribuições de Dados & Inferência:** Construir a base teórica ao explorar probabilidade, variáveis aleatórias e as distribuições comuns usadas para modelar fenômenos do mundo real.

3.  **Experimentação & Teste de Hipóteses:** Aplicar uma estrutura científica para validar suposições e tomar decisões com base em dados.

4.  **Introdução ao Aprendizado de Máquina:** Usar nossa base estatística para construir e avaliar modelos preditivos para tarefas de regressão e classificação.


---

## 🛠️ Ferramentas Utilizadas

**- Linguagem:** Python 

**- Análise de Dados:** Pandas, NumPy 

**- Análise Estatística:** SciPy, Statsmodels 

**- Visualização:** Matplotlib, Seaborn 

**- Ambiente:** Jupyter Lab, Visual Studio Code 

**- Outros:** Git & GitHub

---

## 📂 Estrutura do Repositório

O projeto está organizado da seguinte forma:

```

├── notebooks/ Statistics_Fundamentals.ipynb           <- Contains all case studies in Jupyter
├── data/                <- Example datasets used in the notebooks
├── images/              <- Saved images and charts for the README
├── .gitignore
├── README.md            <- This file
└── requirements.txt     <- Project dependency list

```

--- ## 🚀 Como Executar o Projeto

1. **Clone o repositório:** 

```bash
git clone [https://github.com/Lucas-Ker/stats_for_data_science](https://github.com/Lucas-Ker/stats_for_data_science)
cd stats_for_data_science
```

2. **Crie e ative o ambiente virtual:** 

```bash
python3 -m venv venv
source venv/bin/activate
```

3. **Instale as dependências:** 

```bash
pip install -r requirements.txt
```

4. **Obtenha os Dados**

   Você precisa dos arquivos de dados brutos dentro da pasta `data/`. Siga os passos de download manual:

   * **a.** Vá para a página do conjunto de dados no Kaggle: [Video Game Sales with Ratings](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings).
   * **b.** Clique no botão “Download” para obter o arquivo `.zip` (provavelmente nomeado `archive.zip`).
   * **c.** Extraia o arquivo.
   * **d.** Copie o arquivo principal (por exemplo, `Video_Games_Sales_as_at_22_Dec_2016.csv`) para a pasta `data/` deste projeto.

5. **Execute os notebooks Jupyter:**

```bash
jupyter lab
```

* Abra a pasta `notebooks/` e explore os estudos de caso.

---

## 🌱 Próximas Etapas e Tópicos Planejados

Como este é um projeto em evolução, a lista de tópicos a serem adicionados é contínua. Os próximos estudos planejados incluem:

* Escrever uma seção sobre PCA e Métodos de Conjunto (Random Forests & XGBoost).

* Escrever uma seção sobre Validação Cruzada e Ajuste de Hiperparâmetros.

* Explorar Análise de Séries Temporais e algoritmos de Previsão.

* Implementar testes estatísticos mais avançados e suas aplicações.


---

## ✍️ Autor

* **Lucas Ker Soares Dias** 

* **LinkedIn:** [https://www.linkedin.com/in/lucas-ker/](https://www.linkedin.com/in/lucas-ker/)

* **GitHub:** [https://github.com/Lucas-Ker](https://github.com/Lucas-Ker)