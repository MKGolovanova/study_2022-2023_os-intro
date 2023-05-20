---
## Front matter
title: "Индивидуальный проект. Этап 6"
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

Размещение двуязычного сайта на Github:

* Сделать поддержку английского и русского языков.
* Разместить элементы сайта на обоих языках.
* Разместить контент на обоих языках.
* Сделать пост по прошедшей неделе.
* Добавить пост на тему по выбору (на двух языках).


# Выполнение лабораторной работы

Я сделала поддержку английского и русского языков и разместила элементы сайта на обоих языках (рис. @fig:001, рис. @fig:002).

![Поддержка английского и русского языков на сайте](image/Снимок экрана от 2023-05-20 20-28-23.png){#fig:001 width=70%}

![Элементы сайта на английском и русском языках](image/Снимок экрана от 2023-05-20 20-43-21.png){#fig:002 width=70%}


Я разместила контент на обоих языках (рис. @fig:003, рис. @fig:004).

![Контент на английском и русском языках (1)](image/Снимок экрана от 2023-05-20 20-43-48.png){#fig:003 width=70%}

![Контент на английском и русском языках (2)](image/Снимок экрана от 2023-05-20 20-50-12.png){#fig:004 width=70%}

Я сделала пост по прошедшей неделе и добавила пост на тему по выбору (на двух языках) (рис. @fig:005, рис. @fig:006).

![Пост по прошедшей неделе и посты на двух языках](image/Снимок экрана от 2023-05-20 20-27-51.png){#fig:005 width=70%}

![пост на двух языках](image/Снимок экрана от 2023-05-20 20-21-43.png){#fig:006 width=70%}

# Выводы

Я выполнила 6 этап индивидуального проекта и научилась создавать собственный сайт.

# Список литературы{.unnumbered}

::: {#refs}
:::
