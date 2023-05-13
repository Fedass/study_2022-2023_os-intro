---
## Front matter
title: "Отчет по 4 этапу ип."
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

1. Регистрация на научных платформах.
2. добавление ссылок на страницу сайта
3. Создание поста про прошедшую неделю.
4. Создание поста про оформление отчета.

# Задание

1. Зарегистрироваться на научных платформах.
2. Добавить ссылок на страницу сайта
3. Создать поста про прошедшую неделю.
4. Создать поста про оформление отчета.



# Выполнение лабораторной работы

1. Зарегистрировался на научных платформах и добавил ссылки на страницу сайта.
![im1](image/im1.png){#fig:001 width=70%}
2. Написал информацию про прошедшую неделю.
![im2](image/im2.png){#fig:002 width=70%}
3. Пост про прошедшую неделю.
![im3](image/im3.png){#fig:003 width=70%}
4. Написал информацю про оформление отчета.
![im4](image/im4.png){#fig:004 width=70%}
5. Пост про оформление отчета.
![im5](image/im5.png){#fig:005 width=70%}


# Выводы

Выполнил все необходимые задания.

