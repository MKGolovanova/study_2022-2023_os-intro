---
## Front matter
title: "Индивидуальный проект. Этап 4"
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

* Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
-  eLibrary : https://elibrary.ru/;
- Google Scholar : https://scholar.google.com/;
- ORCID : https://orcid.org/;
- Mendeley : https://www.mendeley.com/;
- ResearchGate : https://www.researchgate.net/;
- Academia.edu : https://www.academia.edu/;
- arXiv : https://arxiv.org/;
- github : https://github.com/.
* Сделать пост по прошедшей неделе.
* Добавить пост на тему по выбору:
- Оформление отчёта.
- Создание презентаций.
- Работа с библиографией.

# Выполнение лабораторной работы

1. Я зарегистрировалась на соответствующих ресурсах и разместить на них ссылки на сайте (рис. @fig:001).

![Ссылки на ресурсы на сайте](image/Снимок экрана от 2023-04-29 22-59-57.png){#fig:001 width=70%}

2. Я сделала пост по прошедшей неделе (рис. @fig:00).

![Пост по прошедшей неделе](image/Снимок экрана от 2023-04-29 23-06-14.png){#fig:002 width=70%}

3. Я добавила пост на тему по выбору (выбрала тему "Оформление отчёта") (рис. @fig:003).

![Пост на тему "Оформление отчёта"](image/Снимок экрана от 2023-04-29 23-06-27.png){#fig:003 width=70%}

# Выводы

Я выполнила 4 этап создания собственного сайта.

# Список литературы{.unnumbered}

::: {#refs}
:::
