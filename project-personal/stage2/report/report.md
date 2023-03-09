---
## Front matter
title: "Отчёт по 2 этапу индивидуального проекта"
subtitle: "Создание сайта"
author: "Городянский Фёдор Николаевич"

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

Изменение главной страницы и создание 2 постов.

# Задание

1. Изменить главную страницу
2. Создать пост про первую неделю
3. Создать пост про гит.


# Выполнение лабораторной работы

1. В content/post открыли файл index.md и изменили имя и фамилию.
![im1](image/im1.png){#fig:001 width=70%}
2. Поменяли данные об авторе.
![im2](image/im2.png){#fig:002 width=70%}
3. Написали личную информацию.
![im3.1](image/im3.png){#fig:003 width=70%}
![im3.2](image/im4.png){#fig:004 width=70%}
4. Открыли файл index.md в папке week1 и прописали информацию.
![im4.1](image/im5.png){#fig:005 width=70%}
![im4.2 Пост про 1 неделю](image/im6.png){#fig:006 width=70%}
5. Открыли файл index.md в папке post2 и внесли изменения.
![im5.1](image/im7.png){#fig:007 width=70%}
![im5.2](image/im8.png){#fig:008 width=70%}
![im5.3 Пост про гит](image/im9.png){#fig:009 width=70%}

# Выводы

Внес личную информацию на главную страницу и создал 2 поста.

