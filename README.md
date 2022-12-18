# О курсе

В этом курсе поставлен акцент на практике — наши занятия представляют собой семинары, на которых мы практикуемся писать код, а также разбираем неочевидные теоретические моменты. Каждые две недели студенты делают мини-проекты по программированию.

Предполагается, что студенты много работают самостоятельно, готовятся к семинарам. В этом репозитории собраны все необходимые ссылки, которые используются в курсе, а также программа семинаров и все материалы.

Курс **Python для анализа данных** состоит из 3 блоков:
1) Базовый Python — синтаксис и возможности языка Python, использование разнообразных библиотек (вы научитесь программировать и решать прикладные задачи с помощью Python)
2) Анализ данных на Python — numpy, pandas, matplotlib seaborn, jupyter notebook, anaconda (вы научитесь манипулировать таблицами, делать EDA — Exploratory Data Analysis и визуалировать данные красивыми графиками)
3) Продвинутый Python — продвинутые возможности языка и их использование для анализа данных

# 1 Базовый Python

### 1.1 Демонстрация возможностей Python

Дата: 25 декабря

Прямо на семинаре мы напишем достаточно сложный проект, а также в целом поговорим о том, где и как используется Python. По ходу занятия мы протестируем коллаборацию через IDE (возможность совместно редактировать код как в гугл документах), попрактикуемся в использовании IDE. Также у студентов будет возможность познакомиться друг с другом и поделиться ожиданиями от курса, рассказать, зачем каждому из участников нужно программирование.

### Домашнее задание к 1.2
- CS50, лекция 1
	- Бинарная система счисления
	- Алгоритмы
- CS50, лекция 1
	- Принципы написания кода
	- Алгоритмы и сэндвич с арахисовым маслом
	- Базовые элементы программирования с примерами на Scratch: переменные, массивы, циклы

### 1.2 Введение в программирование

Дата: 1 января

Разберёмся, как изученные в первых двух лекциях CS50 концепции реализованы в Python, попрактикуемся писать первые строчки кода.

Эти основы могут показаться бесполезными, но это не так. Уже на следующем семинаре мы разберем задачу, в которой потребуются эти знания :)

### Домашнее задание к 1.3
- Курс [Программирование на Python](https://stepik.org/course/67/syllabus) — модуль 1
	- Операторы
	- Переменные
	- Типы данных
	- Условия
	- Задачи по базовому синтаксису Python

### 1.3 Семинар по базовому синтаксису Python

На практике повторим материалы модуля 1, разберем задачи оттуда и посмотрим решения студентов. Кроме того, дополнительно разберем важные темы:
- Ловля исключений — try и except
- Почему сложение float бывает неточным?
- Строчки формата и f-strings

Кроме того, на этом семинаре мы попрактикуемся гуглить :)

### Проект к 1.4 — программа для расчета BMI

`description in progress`

### 1.4 Разбор проектов

Все желающие студенты кратко расскажут о своих проектах и продемонстрируют его возможности. Мы разберем код каждого из проектов и улучшим те аспекты, которые можно улучшить.

### Домашнее задание к 1.5
- Курс [Программирование на Python](https://stepik.org/course/67/syllabus) — модуль 2
	- Циклы
	- Строки
	- Списки

### 1.5 Циклы и коллекции

На практике повторим материалы модуля 2, разберем задачи оттуда и посмотрим решения студентов. Кроме того, дополнительно разберем важные темы:
- Коллекции в Python
	- set
	- tuple
- Полиморфизм на примере функции `len(collection)`
- Оператор in

### Проект к 1.6

`description in progress`

### 1.6 Разбор проектов

Все желающие студенты кратко расскажут о своих проектах и продемонстрируют его возможности. Мы разберем код каждого из проектов и улучшим те аспекты, которые можно улучшить.

### Домашнее задание к 1.7
- Курс [Программирование на Python](https://stepik.org/course/67/syllabus) — модуль 3
- Функции
- Словари
- Файлы
- Модули
- Введение в библиотеки для анализа данных

### 1.7 Семинар по Python и работе с данными

На практике повторим материалы модуля 3, разберем задачи оттуда и посмотрим решения студентов. Кроме того, дополнительно разберем важные темы:
- Введение в pandas
- Принципы устройства веб-приложений
- Немного о телеграм-ботах

### Проект к 1.8 — телеграм-бот, визуализирующий данные

`description in progress`

### 1.8 Разбор проектов

# 2 Библиотеки для анализа и визуализации данных

Подробная программа будет опубликована позже. В отличие от предыдущего блока, здесь будет много материалов на английском. Вот основные темы, которые мы затронем:
- Использование pandas для жонглирования таблицами
- Кастомизация графиков в matplotlib
- "Под капотом" у matplotlib
- Красивые визуализации — seaborn
- Что такое машинное обучение?
- Jupyter Notebook good practices

Кроме того, мы продолжим практиковаться в Python, решая задачи на [CodeSignal](https://app.codesignal.com/arcade)

# 3 Продвинутый Python

Подробная программа будет опубликована позже. Как и во втором блоке, здесь будет много материалов на английском. Вот основные темы, которые мы затронем:
- Написание хорошего кода
- Принципы ООП и их реализация в Python
- Немного красоты: NamedTuple, Dataclass
- Декораторы и их применение в анализе данных, `*args` и `**kwargs`
- Изменяемые и неизменяемые типы данных, их использование в функциях
- Коллекции и iterables в общем виде, comprehensions
- Типизация в Python
- Работа с памятью, генераторы и их применение при работе с данными
- Функциональное программирование на Python: lambda, map, filter, reduce
- Контекстные менеджеры, модули os и sys, работа с файлами
- Парсинг аргументов из командной строки
- Полезные библиотеки: logging, datetime, time
- Работа с API, парсинг json и html, экспорт данных через pickle
- Публикация собственных пакетов, тестирование, управление зависимостями в poetry
- Подготовка к техническим собеседованиям по Python

Завершив этот блок, вы, скорее всего, будете знать Python лучше среднего биоинформатика или специалиста по данным :)
