---
## Front matter
title: "Отчет по 5 этапу создания сайта"
subtitle: "Дисциплина:Операционные системы"
author: "Абрамова Ульяна Михайловна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Добавить к сайту все остальные элементы.

# Задание


1. Сделать записи для персональных проектов.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору.


# Выполнение лабораторной работы
## Добавление информации
Создаю свой проект в каталоге content/project (рис. [-@fig:001]).

![проект](/home/umabramova/cite/report5/image/1.jpg){#fig:001 width=70%}

## написание постов
Пишу пост по прошедшей неделе (рис. [-@fig:002])

![написание поста](/home/umabramova/cite/report5/image/2.jpg){#fig:002 width=70%}

Пишу пост на тему «Языки научного программирования” (рис. [-@fig:003])

![написание поста](/home/umabramova/cite/report5/image/3.jpg){#fig:003 width=70%}

## просмотр изменений
Смотрю изменения на сайте (рис. [-@fig:004], [-@fig:005]).

![просмотр постов](/home/umabramova/cite/report5/image/4.jpg){#fig:004 width=70%}

![просмотр добавленной информации](/home/umabramova/cite/report5/image/5.jpg){#fig:005 width=70%}


# Выводы

В результате я добавила к сайту все остальные элементы.

# Список литературы{.unnumbered}
1. [Операционные системы](https://esystem.rudn.ru/mod/page/view.php?id=1224217)
