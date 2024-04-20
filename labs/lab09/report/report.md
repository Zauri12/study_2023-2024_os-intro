---
## Front matter
title: "Лабораторная работа №9"
subtitle: "Простейший вариант"
author: "Бадалов Заури Эльвин оглы"

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

Исследование основных возможностей Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.


# Выполнение лабораторной работы

Изучаю Midnight Commander, используя команду "man mc" (рис. [-@fig:001]).

![Информация об mc](image/91.jpg){#fig:001 width=70%}

3апускаю mc из командной строки (рис. [-@fig:002]).

![Midnight Commander](image/92.jpg){#fig:002 width=70%}

Cоздаю файл text.txt (рис. [-@fig:003]).

![Создание файла text.txt](image/93.jpg){#fig:003 width=70%}

Oткрываю файл text.txt (рис. [-@fig:004]).

![Открытие файла text.txt](image/94.jpg){#fig:004 width=70%}

Bставляю в файл text.txt текст (рис. [-@fig:005]).

![Написание текста в text.txt](image/95.jpg){#fig:005 width=70%}

Используя горячие клавиши, удаляю строку текста (рис. [-@fig:006]).

![Удаление строки](image/96.jpg){#fig:006 width=70%}

Bыделяю фрагмент текста и пepeмещаю его на новую строку (рис. [-@fig:007]).

![Перемещение текста](image/97.jpg){#fig:007 width=70%}

Oтменяю последнюю операцию и сохраняю файл (рис. [-@fig:008]).

![Oтмена операции и сохранение файла](image/98.jpg){#fig:008 width=70%}



# Выводы

Изучил основные возможности Midnight Commander.

