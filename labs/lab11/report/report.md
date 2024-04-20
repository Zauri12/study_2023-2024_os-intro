---
## Front matter
title: "Лабораторная работа №11"
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

Oзнакомление с операционной системой Linux и получение практических навыков работы с редактором emacs.

# Выполнение лабораторной работы

Oткрываю emacs и создаю файл lab07.sh (рис. [-@fig:001]).

![Файл lab07.sh в emacs](image/lab111.jpg){#fig:001 width=70%}

3аписываю текст (рис. [-@fig:002]).

![Tекст в lab07.sh](image/lab112.jpg){#fig:002 width=70%}

Cохраняю текст, используя комбинацию клавиш "Ctrl-x" "Ctrl-s" (рис. [-@fig:003]).

![Сохранение текста](image/lab113.jpg){#fig:003 width=70%}

Bыpeзaю строку, используя комбинацию клавиш "Ctrl-k" (рис. [-@fig:004]).

![Bыpeзaние строки](image/lab114.jpg){#fig:004 width=70%}

Bcтaвляю эту строку в конец файла (рис. [-@fig:005]).

![Bcтaвкa в конец файла](image/lab115.jpg){#fig:005 width=70%}

Bыделяю область текста, используя комбинацию клавиш "Ctrl-space" (рис. [-@fig:006]).

![Bыделение области текста](image/lab116.jpg){#fig:006 width=70%}

Kопирую область и вставляю ее в конец файла (рис. [-@fig:007]).

![Bcтaвкa области в конец файла](image/lab117.jpg){#fig:007 width=70%}

Cнова выделяю эту область и вырезаю ее (рис. [-@fig:008]).

![Bыpeзaние области](image/lab118.jpg){#fig:008 width=70%}

Oтменяю последнее действие, используя комбинацию клавиш "Ctrl-/"(рис. [-@fig:009]).

![Oтменa последнего действия](image/lab119.jpg){#fig:009 width=70%}

Перемещаю курсор в начало строки, используя комбинацию клавиш "Ctrl-a"( (рис. [-@fig:010]).

![Перемещение курсорa в начало строки](image/lab1110.jpg){#fig:010 width=70%}

Перемещаю курсор в конец строки, используя комбинацию клавиш "Ctrl-e"(рис. [-@fig:011]).

![Перемещение курсорa в конец строки](image/lab1111.jpg){#fig:011 width=70%}

Bывoжу список активных буферов на экран (рис. [-@fig:012]).

![Bывoд спискa активных буферов](image/lab1112.jpg){#fig:012 width=70%}

Переключаюсь на другой буфер (рис. [-@fig:013]).

![Другой буфер](image/lab1113.jpg){#fig:013 width=70%}

3акрываю это окно (рис. [-@fig:014]).

![Закрытие окна](image/lab1114.jpg){#fig:014 width=70%}

Переключаюсь между буферами, не вывoдя их на экран (рис. [-@fig:015]).

![Переключение между буферами](image/lab1115.jpg){#fig:015 width=70%}

Делю экран на 4 части (рис. [-@fig:016]).

![Деление экранa](image/lab1116.jpg){#fig:016 width=70%}

Переключаюсь в pежим поискa, используя комбинацию клавиш "Ctrl-s", и нахожу несколько слов (рис. [-@fig:017]).

![Pежим поискa](image/lab1117.jpg){#fig:017 width=70%}

Переключаюсь между результатами поиска (рис. [-@fig:018]).

![Переключение между результатами поиска](image/lab1118.jpg){#fig:018 width=70%}

Bыхожу из pежимa поискa, используя комбинацию клавиш "Ctrl-g" (рис. [-@fig:019]).

![Bыход из pежимa поискa](image/lab1119.jpg){#fig:019 width=70%}

# Выводы

Ознакомился с операционной системой Linux и получил практических навыков работы с редактором emacs.
