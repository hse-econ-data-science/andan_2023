# Анализ данных на python (коллекция весна 2023)


## Полезные ссылки

- [Таблица с вашими оценками](https://docs.google.com/spreadsheets/d/1chu9ANEewsm-wZiNVHwrsbN0qNSKIHh5ejXfqiRMxaw/edit?usp=sharing)
- Youtube-каналы с записями семинаров: [канал Филиппа](https://www.youtube.com/watch?v=6PVAmajrghM&list=PLNKXA-74YGLhJIw9hp8_YroThDOLaX0oN), [канал Максима](https://www.youtube.com/channel/UCnidfAv0RmXnzwxXMDlYz2Q)
- Материалы для каждого семинара лежат в папках `/sem*`
- Если вы хотите скачать из репозитория конкретную папку, просто вставьте ссылку на неё [в сервис для скачки.](https://minhaskamal.github.io/DownGit/#/home)
- Любые вопросы можно задавать в общий чат. Там можно найти поддержку и пофлудить. [![TG1](https://img.shields.io/badge/Telegram-chat-blue)](https://t.me/+_2BivfQyHHYxMzJi) 
- Канал с основными объявлениями [![TG1](https://img.shields.io/badge/Telegram-chat-blue)](https://t.me/+VyQGUa12HZg4MjAy)
- [Репозиторий с материалами курса по python](https://github.com/hse-econ-data-science/dap_2022-23) из прошлого семестра (там же инструкция по установки анаконды и тп)


## Идеология курса

Добро пожаловать на курс по анализу данных. Основная цель этого курса - научить вас работе с данными. Мы научимся анализировать таблицы, строить красивый визуал, проверять гипотезы, симулировать случайные величины, а также посмотрим на базовые концепции машинного обучения. 

На семинарах мы будем активно использовать различные понятия из теории вероятностей и математической статистики. Лекции и семинары по ним лучше не прогуливать ;) 


## Домашние задания и контрольные

**Домашки:** 

- ДЗ-1: [генерации случайных величин и numpy](https://nbviewer.org/github/hse-econ-data-science/andan_2023/blob/main/hw/hw01-hakuna_matata.ipynb)
- ДЗ-2: [EDA в pandas: анализируем чеки и ищем VaR](https://nbviewer.org/github/hse-econ-data-science/andan_2023/blob/main/hw/hw02-we_bare_bears.ipynb)
- ДЗ-3: [Определяем пол клиента по транзакциям](https://nbviewer.org/github/hse-econ-data-science/andan_2023/blob/main/hw/hw03-logreg_must_suffer.ipynb)
- ДЗ-4: [АБ-тестирование](https://nbviewer.org/github/hse-econ-data-science/andan_2023/blob/main/hw/hw04/hw04-red_or_blue.ipynb)

**Мини-самостоялки:**

- МСР-1: [вариант-1](https://docs.google.com/forms/d/e/1FAIpQLSeJv1OaW0apfPrUUZ60uR-4FcaUHcpsQmyzD6VYa1h8sSw3RA/viewform?usp=sf_link) [вариант-2](https://docs.google.com/forms/d/e/1FAIpQLSd3ycy3Xw9xwB3IoGV1Px3QsZcOBSlMQtWUkfFeNPx1gimI3Q/viewform?usp=sf_link)
- МСР-2: [вариант-1](https://docs.google.com/forms/d/e/1FAIpQLSc_93B3KvS6EAIB0fgjlgReYG7Mhg_8BJ9av3qnI1ARqduQiw/viewform?usp=sf_link) [вариант-2](https://docs.google.com/forms/d/e/1FAIpQLSdnJqzXdV1ClBsfrNOqihWKmZICPawtz_c8QaluzUCf--j-EA/viewform?usp=sf_link)
- МСР-3: [вариант-1](https://docs.google.com/forms/d/e/1FAIpQLSeNnPq1Czp749xYpuWnwcZkDoHqCDmX81Fq7knYmimiQ_aPXw/viewform?usp=sf_link) [вариант-2](https://docs.google.com/forms/d/e/1FAIpQLSfkWWI3Kdk0BJs5wnUlkfbS_NnGr-P7etLlY0ASoppefUVGqw/viewform?usp=sf_link) 
- Если есть желание, можно порешать [тесты из мидтёрмов и экзаменов по МО](https://github.com/Vasyka/intro-ml-bi/tree/main/exams)
- МСР-4: [вариант-1](https://docs.google.com/forms/d/e/1FAIpQLSeFHEUBLVnCkmNPy4-4kBOs1D5ImAvmX4RJABhu8P8zjSdlBg/viewform?usp=sf_link) [вариант-2](https://docs.google.com/forms/d/e/1FAIpQLSfAmEOPY9iwyiUdPF85DONiola0ErGN4wFxK51bkw983b5D0A/viewform?usp=sf_link)


## Большой план маленьких побед


- [__sem01__](./sem01_intro) Вспоминаем питон на задачах про симуляции! Говорим про распределения. Вводимся в scipy и matplotlib.
- [__sem02__](./sem02_numpy) Вводимся в numpy 
- [__sem03__](./sem03_eda) Вводимся в pandas и визуализацию
- [__sem04__](./sem04_CLT&LLN) Метод моментов, ЦПТ, доверительные интервалы.
- [__sem05__](./sem05_pandas_adv) Больше EDA и разной визуализации!
- [__sem06__](./sem06_intro_ml) Базовое машинное обучение. Вводим основные понятия ML. Говорим про KNN.  
- [__sem07__](./sem07_regression) Разбираемся с линейной регрессией и как её обучить.
- [__sem08__](./sem08_regularization_gridsearch) Обсуждаем решуляризацию и подбор гиперпараметров
- [__sem09__](./em09_logreg) Что такое классификация и логистическая регрессия?
- [__sem10__](./sem10_clf_metr) Метрики классификации. Roc-auc.
- [__sem11__](./sem11_ab) АБ-тестирование, гипотезы, критерии.
- [__sem12__](./sem12_more_ab) Больше гипотез и критериев! Непараметрические тесты.
- [__sem13__](./sem13_bootstrap) Семинар про бустрап.
- [__sem14__](./sem14_maxlik) Метод максимального правдоподобия.
- [__sem15__](./sem15_fun) Резервный семинар на всякий случай. 


## Самый важный раздел

Вы поулчаете две оценки. Одну за курс, вторую за независимый экзамен. Оценка за курс ставится по формуле: 


```
Итог = Округление(0.1 * МСР + 0.4 * ДЗ + 0.3 * П + 0.2 * КР)
```

- МСР — мини-тесты на парах 
- ДЗ — домашние работы (их будет 4 штуки, по каждой логической части курса)
- П — свой проект длинной в семестр (расскажем детали позже)
- КР — контрольная в виде демо-варианта независимого экзамена

Обратите внимание, что отдельная оценка будет ставиться за независимый экзамен. Чтобы его сдать придётся заботать не только питон, но ещё и матстат с тревером. 


## Лицензия

Весь контент, созданный для этого курса распространяются на правах лицензии [MIT License](https://github.com/hse-econ-data-science/dap_2020_fall/blob/master/LICENSE) либо на правах лицензии [WTFPL](http://www.wtfpl.net/) на ваш выбор. Материалы публикуются как общественное достояние.
