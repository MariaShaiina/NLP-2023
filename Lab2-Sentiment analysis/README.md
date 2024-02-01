Анализ тональности (англ. sentiment analysis) — это процесс анализа цифрового текста, чтобы определить, является ли эмоциональный тон сообщения положительным, отрицательным или нейтральным. 

<img src="https://github.com/MariaShaiina/NLP-2023/blob/0c361376c543ddaf6cb7a19d11d9d9b71c666531/Lab2-Sentiment%20analysis/sentiment-img.png" width="644" height="474">

В данной лабораторной работе используются методы векторизации (TF-IDF) и классификации для создания модели, способной определить настроение отзыва на основе его текста. Качество классификации оцениваем для следующих моделей:
1. Метод опорных векторов [SVC](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html).
2. Случайный лес [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html).

В качестве входных данных к лабораторной работе взят широко известный набор данных IMDB, содержащий 50K обзоров фильмов [imdb-dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). Откликами являются значения двух классов positive и negative
