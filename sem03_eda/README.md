## Семинар про EDA

Тетрадка для семинара в колабе: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hse-econ-data-science/andan_2023/blob/main/sem03_eda/sem_03_pandas.ipynb)

- необязательные задачи в виде тестика с акциями **[ru]**


### Что посмотреть про таблицы?

- [Видеолекция про pandas](https://www.youtube.com/watch?v=OAy96yiWohk&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=1) от ODS и её [конспект на хабре](https://habr.com/ru/company/ods/blog/322626/) **[ru]**
- [Видеолекция про визуализацию](https://www.youtube.com/watch?v=uwQat1TV0JM&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=2) от ODS и её [конспект на хабре](https://habr.com/ru/company/ods/blog/323210/) **[ru]**
- [Семинар по pandas с ФКН,](https://github.com/esokolov/ml-course-hse/blob/master/2022-fall/seminars/sem01-pandas.ipynb) можно почитать его как туториал **[ru]**
- [Туториалы в официальной документации](https://pandas.pydata.org/docs/getting_started/10min.html) **[en]**
- [Pandas cheet shit](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) **[en]**
- [Интерактивное введение в pandas от Datacamp (надо в него залогиниться)](https://www.datacamp.com/tutorial/pandas-tutorial-dataframe-python) **[en]**
- [Туториалы по визуализации в pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html) **[en]**
- [Галерея графиков от seaborn](http://seaborn.pydata.org/examples/index.html) **[en]**


### Если вас ещё не тошнит от фила:

- Введение в pandas c курсеры от фила: [видос 1](https://www.youtube.com/watch?v=eZzhSZf3gSI&list=PLCf-cQCe1FRxW2QMJbWBl4SSkVAPhId_e&index=13) [видос 2](https://www.youtube.com/watch?v=xNU4m3K9Cr0&list=PLCf-cQCe1FRxW2QMJbWBl4SSkVAPhId_e&index=14) [видос 3](https://www.youtube.com/watch?v=drApVIF4G6c&list=PLCf-cQCe1FRxW2QMJbWBl4SSkVAPhId_e&index=15) [видос 4](https://www.youtube.com/watch?v=w_miR0t0-3w&list=PLCf-cQCe1FRxW2QMJbWBl4SSkVAPhId_e&index=16) [видос 5](https://www.youtube.com/watch?v=HTpNKYvOHc8&list=PLCf-cQCe1FRy1tXQaAQZ1evmt3eDVrDQy&index=5) **[ru]**
- [EDA в пандасе с курсеры от Фила](https://www.youtube.com/watch?v=PymcXqchbKc&list=PLCf-cQCe1FRyF7aY4CC0SGTIoP-52Dvck) **[ru]**
- Тетрадки к видосам выше [можно найти тут](https://github.com/FUlyankin/matstat-AB) **[ru]**


### Как визуализировать данные и заставить всех тебя ненавидеть

1. Заголовок графика для слабаков. По графику всегда понятно, какие данные и явления он описывает.
2. Ни в коем случае не подписывай ни одной оси у графика. Пусть смотрящий развивает свою интуицую! 
3. Единицы измерения совсем не обязательны. Какая разница, в чем измеряли количество - в людях или в литрах!
4. Чем меньше шрифт на графике, тем острее зрение смотрящего. 
5. На одном графике нужно стараться уместить всю информацию, которая у тебя есть в датасете. С полными названиями, расшифровками, сносками. Чем больше текста - тем информативнее!
6. При любой возможности используйте 3D и спецэффекты, пусть знают, что ты — прирожденный дизайнер. К тому же, так будет меньше визуальных искажений. 

Ну а если серьёзно, посмотрите: 

- [Правила хорошей визуализации от Хиндмана](https://robjhyndman.com/hyndsight/graphics/) **[en]**
- [Почему визуализация важна aka проект про динозавров](https://www.autodesk.com/research/publications/same-stats-different-graphs) **[en]**
* __Remove to improve: удаляем с визуализаций лишние элементы и делаем их лучше [en]:__ 
  * [Столбчатые диаграммы](https://www.darkhorseanalytics.com/portfolio/data-looks-better-naked-bar-charts)
  * [Таблицы](https://www.darkhorseanalytics.com/portfolio/2016/1/7/data-looks-better-naked-clear-off-the-table)
  * [Геоданные](https://www.darkhorseanalytics.com/portfolio/w24s5qofnzm4wqmsdfq98kwx035tew)
  * [Круговые диаграммы (смотреть до конца)](https://www.darkhorseanalytics.com/portfolio/2016/1/7/data-looks-better-naked-pie-charts) - благородные Леди и Джентельмены используют круговые диаграммы только [под угрозой расстрела](https://www.biostat.wisc.edu/~kbroman/presentations/IowaState2013/graphs_combined.pdf)


- [Примеры плохих визуализаций,](https://viz.wtf) ещё [примеры плохих визуализаций](https://badvisualisations.tumblr.com/), [ещё примеры плохого](https://www.biostat.wisc.edu/~kbroman/presentations/IowaState2013/graphs_combined.pdf) **[en]**
- [Примеры хороших визуализаций](https://www.reddit.com/r/dataisbeautiful/) **[en]**
- Статьи про визуализацию в блоге Александра Дьяконова: [нулевая,](https://dyakonov.org/2017/10/06/визуализация-часть-0/) [первая](https://dyakonov.org/2017/10/30/визуализация-часть-1/) и [вторая](https://dyakonov.org/2016/11/08/визуализации) **[ru]**
















