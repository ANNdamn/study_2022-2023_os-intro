---
## Front matter
title: "Отчёт по лабораторной работе"
subtitle: "Лабораторная работа №9"
author: "Дикач Анна Олеговна"

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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Выполнение лабораторной работы

1. открываю emacs и создаю файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f(рис. [-@fig:001])

![созданный файл](image/pic1.png){ #fig:001 width=70% }

2. ввожу текст программы. сохраняю файл с помощью комбинации Ctrl-x Ctrl-s. вырезаю строку echo $HELLO (С-k) и вставляю её в конец файла (C-y) (рис. [-@fig:002])

![переставленная строка](image/pic2.png){ #fig:002 width=70% }

3. выделяю область текста (C-space) и копирую область в буфер обмена (M-w) (рис. [-@fig:003])

![работа над текстом](image/pic3.png){ #fig:003 width=70% }

4. вставляю  область в конец файла (рис. [-@fig:004])

![вставка области](image/pic4.png){ #fig:004 width=70% }

5. вновь выделяю эту область и вырезаю её (C-w) (рис. [-@fig:005])

![вырезали область](image/pic5.png){ #fig:005 width=70% }

6. отменяю последнее действие (C-/) (рис. [-@fig:006])

![отмена действия](image/pic6.png){ #fig:006 width=70% }

7. перемещаю курсор: (рис. [-@fig:007]) (рис. [-@fig:008]) (рис. [-@fig:009]) (рис. [-@fig:010])

![перемещаю в начало строки (C-a)](image/pic7.png){ #fig:007 width=70% }

![перемещаю в конец строки (C-e) ](image/pic8.png){ #fig:008 width=70% }

![перемещаю в начало буфер (M-<)](image/pic9.png){ #fig:009 width=70% }

![перемещаю в конец буфера (M->)](image/pic10.png){ #fig:010 width=70% }

8. вывожу активные буферы на экран (C-x C-b) (рис. [-@fig:011])

![вывод](image/pic11.png){ #fig:011 width=70% }

9. перемещаюсь во вновь открытое окно (C-x) o со списком открытых буферов и переключаюсь на другой буфер (рис. [-@fig:012])

![теперь local](image/pic12.png){ #fig:012 width=70% }

10. закрываю окно (C-x 0) (рис. [-@fig:013])

![закрываю окно](image/pic13.png){ #fig:013 width=70% }

11. вновь переключаюсь между буферами, но уже без вывода их списка наэкран (C-x b)  (рис. [-@fig:014])

![переключение](image/pic14.png){ #fig:014 width=70% }

12.  делю фрейм на 4 окна: на два окна по вертикали (C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2)(рис. [-@fig:015])

![разделение фрейма](image/pic15.png){ #fig:015 width=70% }

13.  открываю в каждом из окон новый буфер (рис. [-@fig:016])

![новые буфера](image/pic16.png){ #fig:016 width=70% }

14. переключаюсь в режим поиска (C-s) и нахожу слово hello. переключаюсь между результатами поиска, нажимая C-s (рис. [-@fig:017])

![поиск слова и переключение](image/pic17.png){ #fig:017 width=70% }

15.  выхожу из режима поиска C-g (рис. [-@fig:018])

![выхожу из режима поиска](image/pic18.png){ #fig:018 width=70% }

# Вывод
 
Познакомилась с операционной системой Linux. Получила практические навыки работы с редактором Emacs.
