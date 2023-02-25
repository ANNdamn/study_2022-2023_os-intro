---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Стадия 1"
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

- установить необходимое программное обеспечение
- скачать шаблон темы сайта
- разместить его на хостинге git
- установить параметр для URLs сайта
- разместить заготовку сайта на Github pages


# Выполнение лабораторной работы

1. скачиваю исполняемый файл hugo  (рис. [-@fig:001])

![исполняемый файл](image/pic1.png){ #fig:001 width=70% }

2. исполняемый файл hugo переношу в заранее созданный каталог bin

3. клонирую заранее созданный репозиторий (рис. [-@fig:002]) (рис. [-@fig:003])

![ссылка на репозиторий](image/pic2.png){ #fig:002 width=70% }

![команда для клонирования репозитория](image/pic3.png){ #fig:003 width=70% }

4. перехожу в blog и просматриваю файлы (рис. [-@fig:004])

![просмотр установленных файлов](image/pic4.png){ #fig:004 width=70% } 

5. команду ~/bin/hugo не удалось выполнить даже со сменой исполняемого файла (сменила все, что были в репозитории) (рис. [-@fig:005])

![ошибки работы файлов](image/pic5.png){ #fig:005 width=70% }


# Выводы

научилась скачивать исполняемый файл, клонировать созданный репозиторий и просматривать файлы каталога


