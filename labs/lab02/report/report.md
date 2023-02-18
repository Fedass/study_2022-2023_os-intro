---
## Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: "Первоначальная настройка git"
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

  Изучить идеологию и применение средств контроля версий.
  Освоить умения по работе с git.


# Теоретическое введение


    Система контроля версий Git представляет собой набор программ командной строки. Доступ к ним можно получить из терминала посредством ввода команды git с различными опциями.
    Благодаря тому, что Git является распределённой системой контроля версий, резервную копию локального хранилища можно сделать простым копированием или архивацией.


# Выполнение лабораторной работы

1. Задали имя и email владельца репозитория.
![im1](image/im1.png){#fig:001 width=70%}
2. Задали имя первоначальной ветки и ввели параметры autocrl, safecrlf
![im2](image/im2.png){#fig:001 width=70%}
3. Создали ssh ключ размером 4096 бит.
![im3](image/im3.png){#fig:001 width=70%}
4. Создали ssh ключ по алгоритму ed25519:
![im4](image/im4.png){#fig:001 width=70%}
5. Создали pgp ключ.
![im5](image/im5.png){#fig:001 width=70%}
6. Скопировали ssh ключ.
![im6](image/im12.png){#fig:001 width=70%}
7. Скопировали pgp ключ.
![im7](image/im6.png){#fig:001 width=70%}
8. Настроили автоматические подписи коммитов git.
![im8](image/im7.png){#fig:001 width=70%}
9. Авторизировались на github.
![im9](image/im8.png){#fig:001 width=70%}
10. Создали репозиторий курса на сервере.
![im10](image/im9.png){#fig:001 width=70%}
11. Перешли в каталог курса.
![im11](image/im10.png){#fig:001 width=70%}
12. Подключили курс на github.
![im12.1](image/im11.png){#fig:001 width=70%}
![im12.2](image/im13.png){#fig:001 width=70%}
![im12.3](image/im14.png){#fig:001 width=70%}
13. Отправили файлы на сервер.
![im13](image/im15.png){#fig:001 width=70%}
14. Ssh, pgp ключи.
![im14](image/im16.png){#fig:001 width=70%}
15. Репозиторий курса.
![im15](image/im17.png){#fig:001 width=70%}


# Выводы

В результате получили навыки работы с системой git.

