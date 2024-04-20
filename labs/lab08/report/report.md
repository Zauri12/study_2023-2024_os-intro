---
## Front matter
title: "Лабораторная работа №8"
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

Ознакомление со средствами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков тестирования дисков и обслуживания файловых систем.

# Выполнение лабораторной работы

Вхожу в систему. Записываю в файл file.txt имена файлов, находящихся в каталоге /etc. Добавляю в этот же файл имена файлов из домашнего каталога. (рис. [-@fig:001]).

![Пункт 1](image/81.jpg){#fig:001 width=70%}

Ищу в домашнем каталоге файлы, имена которых начинаются с буквы "c". (рис. [-@fig:002]).

![Пункт 4](image/83.jpg){#fig:002 width=70%}

Пишу имена файлов из каталога /etc, начинающиеся с "h" (рис. [-@fig:003]).

![Пункт 5](image/84.jpg){#fig:003 width=70%}

3апускаю процесс в фоновом режиме, который записывает в файл ~/logfile файлы, имена которых начинаются с «log» (рис. [-@fig:004]).

![Пункт 6](image/85.jpg){#fig:004 width=70%}

Удаляю файл ~/logfile (рис. [-@fig:005]).

![Пункт 7](image/86.jpg){#fig:005 width=70%}

3апускаю редактор gedit в фоновом режимe (рис. [-@fig:006]).

![Пункт 8](image/87.jpg){#fig:006 width=70%}




# Выводы

Здесь кратко описываются итоги проделанной работы.

