---
## Front matter
title: "Лабораторная работа №5"
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

Здесь приводится формулировка цели лабораторной работы. Формулировки
цели для каждой лабораторной работы приведены в методических
указаниях.

Цель данного шаблона --- максимально упростить подготовку отчётов по
лабораторным работам.  Модифицируя данный шаблон, студенты смогут без
труда подготовить отчёт по лабораторным работам, а также познакомиться
с основными возможностями разметки Markdown. [@tuis]


# Выполнение лабораторной работы

Устанавливаю pass-otp (рис. [-@fig:001]).

![Установка pass-otp](image/51.jpg){#fig:001 width=70%}

Устанавливаю gopass (рис. [-@fig:002]).

![Установка gopass](image/52.jpg){#fig:002 width=70%}

Hастраиваю менеджер паролей (рис. [-@fig:003]).

![Настройкa](image/54.jpg){#fig:003 width=70%}

Устанавливаю browserpass (рис. [-@fig:004]).

![Установка browserpass](image/56.jpg){#fig:004 width=70%}

Добавляю новый пароль (рис. [-@fig:005]).

![Новый пароль](image/57.jpg){#fig:005 width=70%}

3аменяю пароль (рис. [-@fig:006]).

![Замена пароля](image/58.jpg){#fig:006 width=70%}

Устанавливаю дополнительное программное обеспечение (рис. [-@fig:007]).

![Установка дополнительного программного обеспечения](image/59.jpg){#fig:007 width=70%}

Устанавливаю шрифты (рис. [-@fig:008]).

![Установка шрифтов](image/510.jpg){#fig:008 width=70%}

# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
