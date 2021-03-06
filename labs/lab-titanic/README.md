# Лабораторная работа 3: Титаник

## «Обработка и визуализация данных»
**Цель**: Научиться анализировать, обрабатывать, визуализировать данные. Тренировать алгоритмы машинного обучения и работать с Kaggle.

Порядок выполнения работы:

* Следуйте указаниям в ноутбуке  

## Дополнение
* ru.wikipedia.org/wiki/Крушение_«Титаника»

**Библиотеки**
1. matplotlib.org - Документация MatPlotLib
2. pandas.pydata.org/docs/ - Документация Pandas
3. https://scikit-learn.org/stable/ - Документация scikit-learn

**Визуализация**

* python-graph-gallery.com -  Галлерея питоновских графиков. Если вы хотите нарисовать график, но не знаете, что лучше подойдет - этот сайт может помочь. 
* seaborn.pydata.org/examples - Галлерея библиотеки seaborn
* matplotlib.org/stable/gallery - Галлерея библиотеки matplotlib

## Описание датасета

10 апреля 1912 года «Титаник» отправился из Саутгемптона в свой первый и единственный рейс. Совершив остановки во французском Шербуре и ирландском Квинстауне, корабль вышел в Атлантический океан с 1317 пассажирами и 908 членами экипажа на борту. 15 апреля корабль потерпел затонул, при этом погибло 1502 из 2224 находившихся на борту людей.

Одной из причин большого количества жертв был тот факт, что спасательных шлюпок не хватало на всех пассажиров и членов команды. Конечно, в спасении присутствовал некоторый элемент удачи, но некоторые группы пассажиров имели больше шансов - например женщины, дети или первый класс.

В этом соревновании мы строим модель, по некоторым параметрам предсказывающую, выживет человек или нет.

# Файлы

* train.csv - обучающая выборка
* test.csv - тестовая выборка
* sample_submission.csv - пример загруженного решения

## Параметры датасета

- **survival** - выжил ли человек в катастрофе или нет (0 = нет, 1 = да)
- **pclass** - Класс билета (1, 2, 3)
- **sex** - Пол
- **Age** - Возраст в годах
- **sibsp** - Количество братьев, сестер + супруга/супруг на борту
- **parch** -Количество родителей , детей на борту
- **ticket** - Номер билета
- **fare** - Цена билета
- **cabin** - Номер каюты
- **embarked** - Порт посадки (C = Cherbourg, Q = Queenstown, S = Southampton)