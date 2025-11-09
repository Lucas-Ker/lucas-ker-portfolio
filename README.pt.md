Leia este README em [English 🇺🇸](README.md).

# Portfólio: Data Science — Lucas Ker

👋 Olá — bem-vindo ao meu portfólio. Eu construo pipelines analíticos reprodutíveis e ativos de Data Science prontos para produção que transformam dados ruidosos e em grande escala em resultados claros para negócios e pesquisa. Principais focos: EDA, feature engineering, modelagem preditiva e validação via Monte Carlo — com notebooks prontos para cliente, dashboards de KPI e resumos executivos de uma página.

---

## 1. Entregáveis prontos para cliente 📁

Estes ativos concisos estão prontos para revisão por hiring managers e líderes técnicos.

* **`reports/Olist_Executive_Summary.pdf`**  
  Um resumo executivo de 1 página, não técnico, com as principais conclusões e recomendações priorizadas do projeto Olist.

* **`notebooks/Olist_Client_Highlights.ipynb`**  
  Notebook Jupyter executável que apresenta os 3 principais insights do projeto (Logística, segmentação RFM e protótipo de modelo preditivo) em um walkthrough de ~2 minutos.

* **`notebooks/Stats_for_Business_Client.ipynb`**  
  Guia prático demonstrando como usar testes estatísticos (T-test, ANOVA, Chi-Square), exemplos de Monte Carlo e como interpretar resultados para questões de negócio.

---

## 2. Como executar estes notebooks 📝

Você pode executar os notebooks "Client-Ready" localmente.

1.  **Clone este repositório:**
    ```bash
    git clone https://github.com/Lucas-Ker/lucas-ker-portfolio.git
    cd lucas-ker-portfolio
    ```

2.  **Crie e ative um ambiente virtual (venv):**
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

3.  **Instale as bibliotecas necessárias:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Baixe os Dados Processados:**
    * O notebook do Olist depende de arquivos `.parquet` processados.
    * **[Clique aqui para baixar os dados (3 arquivos, ~30 MB) do Google Drive](https://drive.google.com/drive/folders/1UexfcZOujLVO8-RzY0O__pdOaewW9uVI?usp=drive_link)**
    * Crie uma pasta `data/` na raiz deste projeto.
    * Coloque os 3 arquivos `.parquet` baixados dentro da pasta `data/`.

5.  **Inicie o Jupyter:**
    ```bash
    jupyter lab
    ```
    Agora você pode abrir e executar os notebooks na pasta `notebooks/`.

---

## 3. Projetos Técnicos (Deep-Dive) 🔬

Estes são os repositórios completos, com múltiplos notebooks, onde o trabalho técnico foi realizado.

### Projeto Completo: Análise de E-commerce (Olist)
* **Repositório: [https://github.com/Lucas-Ker/olist-data-analysis-project](https://github.com/Lucas-Ker/olist-data-analysis-project)**

* **O que é:** O pipeline completo de 5 notebooks, desde a ingestão de dados brutos e ETL até testes estatísticos, segmentação RFM/K-Means e modelagem preditiva (Random Forest & Prophet).

* **Resultado Chave:** Um protótipo de modelo que sinaliza pedidos com alto risco de review negativo, atingindo **68% de recall** no conjunto de teste.

### Guia Prático: Estatística para Data Science
* **Repositório: [https://github.com/Lucas-Ker/stats_for_data_science](https://github.com/Lucas-Ker/stats_for_data_science)**

* **O que é:** Um guia prático sobre conceitos estatísticos, da teoria fundamental à aplicação prática em Python.


---

## 4. Competências principais 🧠

Machine Learning · Python · SQL · Análise de Dados · Modelagem Preditiva · Feature Engineering · Modelagem Estatística · Simulação Monte Carlo · Power BI · scikit-learn · Pandas · NumPy


---

## 5. Estrutura do repositório 📁

```

/notebooks
  ├─ Olist_Client_Highlights.ipynb
  └─ Stats_for_Business_Client.ipynb
/reports
  └─ Olist_Executive_Summary.pdf
requirements.txt
README.md

```

---

## 6. Contato / Contrate-me 📫

* **Upwork:** [Upwork](https://www.upwork.com/freelancers/~01570b8ebb7c97dbad)

* **LinkedIn:** [https://www.linkedin.com/in/lucas-ker/](https://www.linkedin.com/in/lucas-ker/)

* **Email:** [lucasker0107@gmail.com](mailto:lucasker0107@gmail.com)
