---
## Front matter
title: "Отчёт по итоговому проекту №1"
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

Создание сайта.

# Задание

Создание сайта.

# Выполнение лабораторной работы

1. Скачал файл hugo, перенес в папку bin.
![im1](image/im1.png){#fig:001 width=70%}
2. Копировал репозиторий проекта.
![im2](image/im2.png){#fig:002 width=70%}
3. Клонировал данные в репозиторий.
![im3](image/im3.png){#fig:003 width=70%}
4. Запустил файл hugo в рабочем каталоге.
![im4](image/im4.png){#fig:004 width=70%}
5. Вывел содержимое.
![im5](image/im5.png){#fig:005 width=70%}
6. Выполнил команду hugo server.
![im6](image/im6.png){#fig:006 width=70%}
7. Создал репозиторий для сайта, перенес данные в предыдущий репозиторий.
![im7](image/im7.png){#fig:007 width=70%}
8. Закомментировал файл public, добавил его в blog.
![im8](image/im8.png){#fig:008 width=70%}
9. Загрузил данные на сервер.
![im9.1](image/im9.png){#fig:009 width=70%}
![im9.2](image/im10.png){#fig:010 width=70%}
10. Репозиторий сайта.
![im10](image/im11.png){#fig:011 width=70%}
11. Сам сайт.
![im11](image/im12.png){#fig:012 width=70%}



# Выводы

Выполнил первый этап проекта.

