# 🎬 Desafio de Data Science – Predição de Filmes  

Este repositório contém a solução do desafio proposto pela **Indicium/Lighthouse** para o processo seletivo de Data Science.  

O objetivo é analisar um dataset cinematográfico e desenvolver um modelo preditivo capaz de estimar a **nota IMDb** de um filme, considerando variáveis relacionadas a **gênero, críticas, número de votos e faturamento**.  

---

## 📌 Descrição do Desafio  

- Exploração dos dados (EDA) para levantar hipóteses e entender correlações.  
- Respostas a perguntas de negócio, como:  
  - Qual filme recomendar sem conhecer o perfil da pessoa?  
  - Quais fatores influenciam no faturamento?  
  - É possível extrair insights do campo *Overview*?  
- Construção de um modelo para prever a **nota IMDb**.  
- Geração de previsões, incluindo o exemplo do filme *The Shawshank Redemption*.  
- Salvamento do modelo em **formato `.pkl`**.  

---

## 📂 Estrutura do Repositório  

- **LH_CD_VINICIUS_SASAKI.ipynb**  
  (Notebook com EDA, modelagem e respostas)
    
- **modelo_imdb.pkl**  
  (Modelo final salvo em formato PKL)
  
- **requirements.txt**
  (Pacotes e versões utilizados)
  
- **README.md**  
  (Este arquivo)
  
---

## ⚙️ Tecnologias Utilizadas  

- Python 
- pandas  
- numpy  
- matplotlib / seaborn  
- scikit-learn  
- xgboost  
- joblib  

---

## 🚀 Como Executar  

1. **Clone o repositório**  
   ```bash
   git clone https://github.com/vinisasaki/LH_CD_VINICIUS_SASAKI.git
   cd LH_CD_VINICIUS_SASAKI
   ```
2. **Crie um ambiente virtual e instale as dependências**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   pip install -r requirements.txt
   ```
3. **Execute o notebook**
   ```bash
   jupyter notebook LH_CD_VINICIUS_SASAKI.ipynb
   ```
## 🚀 Como Executar no Google Colab

1. **Abra o notebook no Colab**  
   - Acesse https://colab.research.google.com  
   - Selecione **GitHub**, e copie a URL do repositório: 
     ```
     [https://github.com/vinisasaki/titanic-descriptive-analysis](https://github.com/vinisasaki/indicium-lighthouse-challenge)
     ```  
   - Abra `LH_CD_VINICIUS_SASAKI.ipynb`.

2. **Carregue o dataset**  
   - Faça o upload do `train.csv` (localizado em `titanic_dataset/`) pelo painel de Arquivos à esquerda, ou  
   - Monte o seu Google Drive e carregue-o via código:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     df = pd.read_csv('/content/drive/MyDrive/data/train.csv')
     ```

3. **Execute as células**  
   - Execute cada célula em ordem.
   - As bibliotecas Pandas, Seaborn e Matplotlib já estão pré instaladas no Colab.
