Leia este README em [English 🇺🇸](README.md).

# Portfólio de Data Science — Lucas Ker

Olá! Este é o meu "hub" de portfólio, com entregáveis prontos para clientes e links para os projetos técnicos completos. Meu trabalho foca em construir pipelines analíticos reprodutíveis que transformam dados brutos em ações de negócio.

---

## 1. Entregáveis (Prontos para Revisão)

Estes são os ativos polidos e concisos, prontos para análise.

* **`reports/Olist_Executive_Summary.pdf`**
    Um relatório executivo em PDF de 1 página, não-técnico, resumindo os principais achados e recomendações do projeto Olist.

* **`notebooks/Olist_Client_Highlights.ipynb`**
    Um Jupyter Notebook limpo que demonstra os 3 principais insights do projeto (Logística, RFM e Modelo Preditivo) em um formato executável de 2 minutos.

* **`notebooks/Stats_for_Business_Client.ipynb`**
    Um guia prático demonstrando como usar testes estatísticos (Teste T, ANOVA, Qui-Quadrado) para responder perguntas comuns de negócio.

---

## 2. Como Executar os Notebooks

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

## 3. Projetos Técnicos (Deep-Dive)

Estes são os repositórios completos, com múltiplos notebooks, onde o trabalho técnico foi realizado.

### Projeto Completo: Análise de E-commerce (Olist)
* **Repositório: [https://github.com/Lucas-Ker/olist-data-analysis-project](https://github.com/Lucas-Ker/olist-data-analysis-project)**

* **O que é:** O pipeline completo de 5 notebooks, desde a ingestão de dados brutos e ETL até testes estatísticos, segmentação RFM/K-Means e modelagem preditiva (Random Forest & Prophet).

* **Resultado Chave:** Um protótipo de modelo que sinaliza pedidos com alto risco de review negativo, atingindo **68% de recall** no conjunto de teste.

### Guia Prático: Estatística para Data Science
* **Repositório: [https://github.com/Lucas-Ker/stats_for_data_science](https://github.com/Lucas-Ker/stats_for_data_science)**

* **O que é:** Um guia prático sobre conceitos estatísticos, da teoria fundamental à aplicação prática em Python.

---

## 4. Contato / Contrate-me

* **Upwork:** [Upwork]()

* **LinkedIn:** [https://www.linkedin.com/in/lucas-ker/](https://www.linkedin.com/in/lucas-ker/)

* **Email:** [lucasker0107@gmail.com](mailto:lucasker0107@gmail.com)
