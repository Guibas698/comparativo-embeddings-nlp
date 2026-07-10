# Análise Comparativa de Modelos de Embedding Textual

## 📌 Sobre o Projeto
Este projeto tem como objetivo avaliar e comparar o desempenho de diferentes modelos de linguagem na geração de embeddings textuais para tarefas de classificação (ex: detecção de Fake News). 

O foco é analisar a eficácia, custo computacional e acurácia de modelos proprietários e open-source na representação vetorial de textos em português e inglês.

## 🚀 Modelos Avaliados
* **Gemini (Google):** Extração de embeddings via API e redução de dimensionalidade.
* **Cohere:** Utilização do modelo multilíngue otimizado.
* **BGE-M3 (BAAI):** Implementação open-source com foco em busca densa.

## 🛠️ Tecnologias e Ferramentas
* **Linguagem:** Python
* **Machine Learning:** Scikit-Learn (Regressão Logística, SVM, Random Forest, PCA)
* **APIs:** Google Gemini API, Cohere API
* **Modelos open-source:** BGE-M3
* **Análise de Dados:** Pandas, NumPy, Matplotlib, Seaborn

## 📂 Estrutura do Repositório
* `/experimento_cohere`: Scripts de extração de embeddings e otimização de hiperparâmetros (GridSearchCV) usando a API do Cohere.
* `/experimento_gemini`: Pipeline de classificação utilizando embeddings do Gemini.
* `/experimento_gemini`: Pipeline de geração de embeddings utilizando o modelo open-source BGE-M3, com aplicação em tarefas de classificação textual.
* `/referencias`: Artigos acadêmicos e documentações que fundamentam a pesquisa.
