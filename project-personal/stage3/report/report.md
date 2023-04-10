---
## Front matter
title: "Индивидуальный проект"
subtitle: "3 этап"
author: "Дикач Анна Олеговна"

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

Внести корректировки в персональный сайт, создать пост о прошедшей неделе и о языке Markdown


# Выполнение лабораторной работы

1.  Добавляю  информацию о навыках (Skills)(рис. [-@fig:001])

![информация о навыках](image/pic1.png){ #fig:001 width=70% }

2. Добавляю информацию о опыте (Experience) (рис. [-@fig:002])

![информация о опыте](image/pic2.png){ #fig:002 width=70% }

3. Добавляю информацию о достижениях (Accomplishments) (рис. [-@fig:003])

![информация о достижениях](image/pic3.png){ #fig:003 width=70% }

4. Создаю пост о прошедшей неделе (рис. [-@fig:004])

![визуал поста](image/pic4.png){ #fig:004 width=70% }

5. Создаю пост о языке Markdown (рис. [-@fig:005])

![визуал поста о языке Markdown](image/pic5.png){ #fig:005 width=70% }

# Выводы

Сделала свой сайт актуальным и создала новые посты

