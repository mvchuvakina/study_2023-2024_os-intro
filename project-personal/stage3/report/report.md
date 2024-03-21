---
## Front matter
title: "Отчет по третьему этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Чувакина Мария Владимировна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Продолжить работы со своим сайтом. Редактировать его в соответствии с требованиями. Добавить данные о своих достижениях.

# Задание

1. Добавить информацию о навыках (Skills).
2. Добавить информацию об опыте (Experience).
3. Добавить информацию о достижениях (Accomplishments).
4. Сделать пост по прошедшей неделе.
5. Добавить пост на тему по выбору.

# Теоретическое введение

Hugo - генератор статических страниц для интернета.
**Статические сайты:**
1. Статические сайты состоят из уже готовых HTML-страниц.
2. Эти страницы собираются заранее, а не готовятся для пользователя «на лету». Для этого используют генераторы статичных сайтов.
3. Так как это почти чистый HTML, то такие сайты быстрее загружаются и их проще переносить с сервера на сервер.
4. Минус: если нужно что-то обновить на странице, то сначала это правят в исходном файле, а потом запускают обновление в генераторе.
5. Ещё минус: такие страницы не подходят для интернет-магазинов или сайтов с личным кабинетом, потому что в статике нельзя сформировать страницу для каждого отдельного пользователя.

# Выполнение лабораторной работы

Захожу в терминал, перехожу в директорию ~/work/blog, ввожу команду ~/bin/hugo server для запуска локального сервера (рис.1).

![Запуск локального сервера](image/01.png){#fig:001 width=70%}

Перехожу в директорию ~/work/blog/content, открываю файл _index.md, в нем будет осуществляться дальнейшая работа (рис.2).

![Путь, по которому работаем](image/02.png){#fig:002 width=70%}

В блоке features, там, где заголовок Skills прописала навыки. Иконки для навыков искала, найдя в интернете официальную библиотеку иконок fas, так можно найти и иконки из библиотеки fab (рис.3).

![Добавление навыков](image/03.png){#fig:003 width=70%}

Далее добавила свой опыт в блоке Experience, добавила даты и нужную информацию (рис.4).

![Добавление опыта](image/04.png){#fig:004 width=70%}

Далее в Accomplishments добавила достижения (рис.5).

![Добавление достижений](image/05.png){#fig:005 width=70%}

Добавила пост на тему по выбору (язык разметки Markdown) в папке posts (рис.6).

![Добавление поста на тему по выбору](image/06.png){#fig:006 width=70%}

Добавила пост по прошедшей неделе в папке posts (рис.7).

![Добавление поста по прошедшей неделе](image/07.png){#fig:007 width=70%}

Закрываю локальный сервер с помощью клавиш Ctrl+C и собираю сайт с изменениями, введя команду ~/bin/hugo без аргументов (рис.8).

![Закрытие локального сервера](image/08.png){#fig:008 width=70%}

Отправляю изменения на GitHub (рис.9).

![Отправка изменений на Git](image/09.png){#fig:009 width=70%}

Теперь перехожу в директорию blog/public и отправляю изменения на GitHub, чтобы глобальный сайт тоже был обновлен (рис.10).

![Отправка изменений на Git](image/10.png){#fig:010 width=70%}

Проверяю, что все сделано корректно (рис.11).

![Результат выполнения работы](image/11.png){#fig:011 width=70%}

# Выводы

В процессе выполнения третьего этапа индивидуального проекта я научилась редактировать данные о себе, а также писать посты и добавлять их на сайт.


