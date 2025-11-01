<!-- markdownlint-disable first-line-h1 -->
<!-- markdownlint-disable html -->
<!-- markdownlint-disable no-duplicate-header -->

<h2>
<p align="center">
  <a href="">Natural Language Processing</a>
</p>
</h2>

<p align="center">
<a href="">Немного поупражняемся в NLP.</a>       
</p>

## Содержание
- [Классификация теста](#Classification)
- [Создание RAG](#RAG)

## [Classification](https://github.com/DEDMOPO3PEAHIMATOP/Deep-Learning/blob/main/NLP/TextClassification_(no_widjets).ipynb)
- Реализация классификации текста несколькими моделями (RNN, GRU, GRUx2, BDRNN)

## [RAG]()
- В данном проекте создадим туристический RAG, проведем EDA
  В качестве основных блоков будем использовать:
  - LLM - кванотванная модель **Llama t-pro-it-1.0-q4_k_s.gguf на архитектуре qwen2
  - будем использовать в качестве векторизатора BAAI/bge-m3
  - в качестве реранкера BAAI/bge-reranker-v2-m3
  - в качестве векторной базы данных будем использовать faiss
