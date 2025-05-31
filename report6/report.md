---
## Front matter
title: "Отчет по 6 этапу создания сайта"
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

Размещение двуязычного сайта на Github.

# Задание


1.  Сделать поддержку английского и русского языков.
2.  Разместить элементы сайта на обоих языках.
3.  Разместить контент на обоих языках.
4.  Сделать пост по прошедшей неделе.
5.  Добавить пост на тему по выбору (на двух языках).



# Выполнение лабораторной работы
Добавляю настройки для двух языков (рис. [-@fig:001]).

![настройки](/home/umabramova/cite/report6/image/1.jpg){#fig:001 width=70%}


Создаю файлы about.md для структуры файловой системы, а также разделяю структуру на английские и русские файлы (рис. [-@fig:002], [-@fig:003])

![Создание файловов](/home/umabramova/cite/report6/image/2.jpg){#fig:002 width=70%}

![разделение структуры](/home/umabramova/cite/report6/image/3.jpg){#fig:003 width=70%}

Настраиваю переключение языков (рис. [-@fig:004])

![написание поста](/home/umabramova/cite/report6/image/4.jpg){#fig:004 width=70%}

Перевожу посты, доклады, проекты на английский и русский (рис. [-@fig:005], [-@fig:006], [-@fig:007])

![Перевод постов](/home/umabramova/cite/report6/image/5.jpg){#fig:005 width=70%}

![Перевод докладов](/home/umabramova/cite/report6/image/6.jpg){#fig:006 width=70%}

![Перевод проектов](/home/umabramova/cite/report6/image/7.jpg){#fig:007 width=70%}

## просмотр изменений
Смотрю как выглядит оформление в зависимости от языка  (рис. [-@fig:008], [-@fig:009], [-@fig:010], [-@fig:011]).

![английский](/home/umabramova/cite/report6/image/8.jpg){#fig:008 width=70%}

![английский](/home/umabramova/cite/report6/image/9.jpg){#fig:009 width=70%}

![русский](/home/umabramova/cite/report6/image/10.jpg){#fig:010 width=70%}

![русский](/home/umabramova/cite/report6/image/11.jpg){#fig:011 width=70%}

# Выводы

В результате я выполнила все задания по проекту.

# Список литературы{.unnumbered}
1. [Операционные системы](https://esystem.rudn.ru/mod/page/view.php?id=1224217)
