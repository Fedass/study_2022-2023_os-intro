---
## Front matter
title: "Лабораторная работа №4"
subtitle: "Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки"
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

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.


# Теоретическое введение

В операционной системе типа Linux взаимодействие пользователя с системой обычно
осуществляется с помощью командной строки посредством построчного ввода ко-
манд. При этом обычно используется командные интерпретаторы языка shell: /bin/sh;
/bin/csh; /bin/ksh.
 
# Выполнение лабораторной работы

1. Определите полное имя вашего домашнего каталога.
![im1](image/im1.png){#fig:001 width=70%}
2. Перейдите в каталог /tmp
![im2](image/im2.png){#fig:002 width=70%}
3. Выведите на экран содержимое каталога /tmp. Для этого используйте команду ls
с различными опциями. 
![im3](image/im3.png){#fig:003 width=70%}
![im4](image/im4.png){#fig:004 width=70%}
![im5](image/im5.png){#fig:005 width=70%}
4. Определите, есть ли в каталоге /var/spool подкаталог с именем cron?
![im6](image/im6.png){#fig:006 width=70%}
5. Перейдите в Ваш домашний каталог и выведите на экран его содержимое. Опре-
делите, кто является владельцем файлов и подкаталогов?
![im7](image/im7.png){#fig:007 width=70%}
6. В домашнем каталоге создайте новый каталог с именем newdir
![im8](image/im8.png){#fig:008 width=70%}
7. В каталоге ~/newdir создайте новый каталог с именем morefun. В домашнем каталоге создайте одной командой три новых каталога с именами
letters, memos, misk. Затем удалите эти каталоги одной командой
![im9](image/im9.png){#fig:009 width=70%}
![im10](image/im10.png){#fig:010 width=70%}
8. Удалите каталог ~/newdir/morefun из домашнего каталога. Проверьте, был ли
каталог удалён.
![im11](image/im11.png){#fig:011 width=70%}
9. С помощью команды man определите, какую опцию команды ls нужно использо-
вать для просмотра содержимое не только указанного каталога, но и подкаталогов,
входящих в него.
![im12](image/im12.png){#fig:012 width=70%}
10. Используя информацию, полученную при помощи команды history, выполните мо-
дификацию и исполнение нескольких команд из буфера команд.
![im13](image/im13.png){#fig:013 width=70%}


# Выводы

Научился работать с пользовательским интерфейсом системы Линукс.
