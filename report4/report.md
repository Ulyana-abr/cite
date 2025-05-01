---
## Front matter
title: "Отчет по 4 этапу создания сайта"
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

Добавить к сайту ссылки на научные и библиометрические ресурсы

# Задание

1. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору

# Выполнение лабораторной работы

Регистрируюсь на соответствующих ресурсах (рис. 1-7):
 * [github](https://github.com/) (рис. [-@fig:001])
 
 ![github](/home/umabramova/cite/report4/image/1.jpg){#fig:001 width=70%}
 
 * [arXiv](https://arxiv.org/) (рис. [-@fig:002])
 
 ![arXiv](/home/umabramova/cite/report4/image/2.jpg){#fig:002 width=70%}
 
 * [Academia.edu](https://www.academia.edu/)  (рис. [-@fig:003])

 ![Academia.edu](/home/umabramova/cite/report4/image/3.jpg){#fig:003 width=70%}
 
 * [Mendeley](https://www.mendeley.com/) (рис. [-@fig:004])
 
 ![Mendeley](/home/umabramova/cite/report4/image/4.jpg){#fig:004 width=70%}
 
 * [ORCID](https://orcid.org/) (рис. [-@fig:005])
 
  ![ORCID](/home/umabramova/cite/report4/image/5.jpg){#fig:005 width=70%}
  
  * [ResearchGate](https://www.researchgate.net/)  (рис. [-@fig:006])
  
  ![ResearchGate](/home/umabramova/cite/report4/image/6.jpg){#fig:006 width=70%}
    
  * [eLibrary](https://elibrary.ru/) (рис. [-@fig:007])
  
   ![eLibrary](/home/umabramova/cite/report4/image/7.jpg){#fig:007 width=70%}
   
и размещаю на них ссылки на сайте  (рис. [-@fig:008])

![сайт](/home/umabramova/cite/report4/image/8.jpg){#fig:008 width=70%}

Пишу пост по прошедшей неделе и пост по теме "Оформление отчёта"  (рис. [-@fig:009])

![написание постов](/home/umabramova/cite/report4/image/9.jpg){#fig:009 width=70%}

Выгружаю их на сайт (рис. [-@fig:010])

![сайт](/home/umabramova/cite/report4/image/10.jpg){#fig:010 width=70%}

# Выводы

В результате я добавила к сайту ссылки на научные и библиометрические ресурсы.

# Список литературы{.unnumbered}

1.  [Операционные системы](https://esystem.rudn.ru/mod/page/view.php?id=1224217)
