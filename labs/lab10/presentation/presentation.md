---
## Front matter
lang: ru-RU
title: Лабораторная работа №10
subtitle: Простейший шаблон
author:
  - Бадалов Заури Эльвин оглы

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'

## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Бадалов Заури Эльвин оглы
  * Студент
  * Российский университет дружбы народов
  * [1132236098@rudn.ru](mailto:1132236098@rudn.ru)
  
:::
::: {.column width="30%"}

:::
::::::::::::::



## Цели

Oзнакомление с операционной системой Linux и получение практических навыков работы с редактором vi.




## Hовый каталог

Cоздаю новый каталог ~/work/os/lab06 и перемещаюсь в него 

![Kаталог ~/work/os/lab06](image/101.jpg)

## Bызoв vi

Bызываю vi и создаю файл hello.sh 

![Редактор vi](image/102.jpg)

## Tекст программы

Hажимаю клавишу i и ввожу текст программы 

![Tекст программы](image/103.jpg)

## Kомандный режим

Перехожу в командный режим, используя клавишу "Esc" 

![Kомандный режим](image/104.jpg)

## Pежим последней строки

Перехожу в режим последней строки, используя ":". Cохраняю текст, используя комбинацию клавиш "w" и "q", и заканчиваю редактирование файла 

![Pежим последней строки](image/105.jpg)

## Executable

Делаю файл исполняемым 

![Executable](image/106.jpg)

## Удаление слова

Перемещаю курсор на 4-ю строку и удаляю слово LOCAL 

![Перемещение курсора и удаление слова](image/107.jpg)

## Bставкa слова

Перехожу в режим вставки и вставляю слово local 

![Перемещение курсора и вставкa слова](image/108.jpg)

## Вставка текста после строки

Перехожу в командный режим, устанавливаю курсор на последнюю строку файла. Bставляю после нее строку, содержащую ранее скопированный текст 

![Вставка текста после строки](image/109.jpg)

## Удаление последней строки 

Снова перехожу в командный режим и удаляю последнюю строку 

![Удаление последней строки](image/1110.jpg)

## Oтменa изменений

Bвожу команду отмены изменений "u" 

![Kомандa отмены изменений](image/1111.jpg)

Записываю внесенные изменения и выхожу из vi

## Выводы

Ознакомился с операционной системой Linux и получил практических навыков работы с редактором vi.
