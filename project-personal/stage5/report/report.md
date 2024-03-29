---
## Front matter
title: "Индивидуальный проект. Этап 5"
subtitle: "Операционные системы"
author: "Голованова Мария Константиновна"

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

Научиться создавать собственный сайт.

# Задание

Добавить с сайту все остальные элементы:
* Сделать записи для персональных проектов.
* Сделать пост по прошедшей неделе.
* Добавить пост на тему по выбору:
  Языки научного программирования.

# Выполнение лабораторной работы

Я сделала записи для персональных проектов (рис. @fig:001).

![Записи для персональных проектов](image/Снимок экрана от 2023-05-13 17-39-08.png){#fig:001 width=70%}

Я сделала пост по прошедшей неделе (рис. @fig:002).

![Пост по прошедшей неделе](image/Снимок экрана от 2023-05-13 17-38-35.png){#fig:002 width=70%}

Я добавила пост на тему "Языки научного программирования" (рис. @fig:003).

![Пост на тему "Языки научного программирования"](image/Снимок экрана от 2023-05-13 17-38-49.png){#fig:003 width=70%}

# Выводы

Я выполнила 5 этап создания собственного сайта.

# Список литературы{.unnumbered}

::: {#refs}
:::
