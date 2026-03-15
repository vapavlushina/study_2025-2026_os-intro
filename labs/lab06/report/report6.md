---
## Front matter
title: "Архитектура компьютеров и операционные системы"
subtitle: "Лабораторная работа №6"
author: "Павлушина В.А."

## Generic otions
lang: ru-RU\
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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Задание

1.Выполнить навигацию по файловой системе.
2.Получить справочную информацию.
3.Выполнить управление каталогами.
4.Сделать анализ содержания каталогов.
5.Работа с history.
6.Комбинировать команды.

# Теоретическое введение

Команда **man** используется для просмотра (оперативная помощь) в диалоговом режиме руководства (manual) по основным командам операционной системы
типа Linux.
Формат команды:
`man <команда>`

Команда **cd** используется для перемещения по файловой системе операционной системы типа Linux.
Формат команды:
`cd [путь_к_каталогу]`

Команда **pwd**. Для определения абсолютного пути к текущему каталогу используется
команда *pwd* (print working directory).

Команда **ls**. Команда *ls* используется для просмотра содержимого каталога.
Формат команды:
`ls [-опции] [путь]`

Команда **mkdir**. Команда *mkdir* используется для создания каталогов.
Формат команды:
`mkdir имя_каталога1 [имя_каталога2...]`

Команда **rm**. Команда *rm* используется для удаления файлов и/или каталогов.
Формат команды:
`rm [-опции] [файл]`

Команда **history**. Для вывода на экран списка ранее выполненных команд используется команда history. Выводимые на экран команды в списке нумеруются. К любой
команде из выведенного на экран списка можно обратиться по её номеру в списке,
воспользовавшись конструкцией !<номер_команды>.

# Выполнение лабораторной работы



# Выводы

# Cписок литературы{.unnumbered}

::: {#refs}
:::
