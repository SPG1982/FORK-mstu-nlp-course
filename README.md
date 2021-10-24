# A Dive into Natural Language Processing

![](https://i.imgur.com/S0EftIF.jpg)

**МГТУ им. Баумана, осень 2021.**

## Лекция 1. Обзор современного машинного обучения

Расскажу про основные домены в DS, в каком состоянии они сейчас находятся и какие задачи сейчас актуальны на рынке (в ритейле, банках, промышленности, ИБ и т.д.).

_Upd. 09.10.2021_

🎬 https://www.youtube.com/watch?v=LT8QJcOFrwo

🗨️ https://docs.google.com/presentation/d/1YFy-Ia7qwkiQp8nlHk7__JIFeB-dAnzI

#### Основные виды данных

- Табличные данные и врменные ряды
- Видео и звук
- Картинки
- Текстовые данные

#### Типичные задачи ML

- Forecasting
- Anomaly detection
- Voice recognition
- Text to Speech
- Video captioning
- Object detection
- Segmentation
- Style transfer
- Image generation
- Noise reduction
- Super Resolution
- Machine translation
- NER
- Relation extraction
- Question answering
- Classification (spam, sentiment, etc.)
- Summarization
- Topic modelling

#### Open Data Science community

- https://ods.ai

## Семинар 1. Делаем семантический поиск

Рассмотрим основные инструменты, подходы и терминологию, которые используются в ML/DS. Разберем, как переводить текстовые данные в векторное пространство. Сделаем простой семантический поиск по текстам. Начнем работать с Colab.

_Update 16.10.2021_

🎬 https://www.youtube.com/watch?v=VJTXBDHpsus

⚡ https://colab.research.google.com/drive/1sBavnRdQTR7NDZDgLwv6_yVnu_UY_PL2?usp=sharing

#### Термины и понятия:

- Tokenization
- Lemmatization
- Stemming
- Distributional semantics
- Embedding
- Word2Vec
- GloVe
- fastText

## Лекция 2. Векторное представление текста. Embeddings.

Базовые подходы и техники, с которых начинается решение прикладных задач и часто же ими и заканчивается. Разберем основные алгоритмы. Статистические и нейросетевые подходы по переводу текстов в векторное пространство. Word2Vec.

_Update 24.10.2021_

🎬 https://www.youtube.com/watch?v=OV_QM_BuAhU

🗨️ https://docs.google.com/presentation/d/162aedK5-nubUV-Z59zQ5zMW5nnLyB8Gu

- One-hot encoding
- Bag of Words
- N-grams
- TF-IDF
- Distributional semantics
- Pointwise mutual information
- Matrix factorization
- SVD
- Word2Vec
- Subsampling
- Negative sampling

## Семинар 2. Основные задачи

Применим базовые подходы для решения задач.

## Лекция 3. Переломный момент в ML

Как повлиял механизм внимания на развитие ML. Расскажу про трансформеры, которые сейчас являются SOTA во многих областях.

## Семинар 3. Трансформеры и другие модели

Сделаем пару нейронок, потренируем их в Colab'e.

## Лекция 4. Большие и очень большие модели

С каждым годом крупные компании предобучают на кластерах GPU все большие модели. Многие из них доступны всем желающим. Как они устроены, можно ли обучить такие же самому и как сделать их fine-tuning.

## Семинар 4. Генерация текста и машинный перевод

Посмотрим на модели от OpenAI и Сбера. Посмотрим, почему из коробки они работают плохо и настроим их. Сделаем систему машинного перевода с какого-нибудь языка на русский.

