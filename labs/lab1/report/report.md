---
## Front matter
title: "Отчет по лабораторной работе №1"
subtitle: "Настройка пространства для лабораторных работ"
author: "Егорова Диана Витальевна"

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

Настроить пространство для лабораторных работ, чтобы была их структурированная сдача. 

# Задание

1. Настроить виртуальную машину
2. Связать GitHub по ssh-ключу
3. Скопировать предложенный шаблон для лабораторных работ


# Выполнение лабораторной работы

Создание новой виртуальной машины (рис. @fig:001).

![Создание виртуальной машины](image/1.png){#fig:001 width=70%}

Добавление носителя образ Rocky (рис. @fig:002).

![Добавление образа](image/2.png){#fig:002 width=70%}

Настройка основных параметров: язык, дата и время, администратор, хост сети (рис. @fig:003).

![Настройка параметров](image/3.png){#fig:003 width=70%}

Окончание загрузки(рис. @fig:004).

![Конец загрузки](image/4.png){#fig:004 width=70%}

Проверка заданных характеристик(рис. @fig:005).

![Заданные характеристики](image/5.png){#fig:005 width=70%}

Настройка соединения по ssh(рис. @fig:006).

![Настройка ssh](image/6.png){#fig:006 width=70%}

Клонирование репозитория(рис. @fig:008) (рис. @fig:009).

![Клонирование репозитория](image/8.png){#fig:008 width=70%} (image/9.png) {#fig:009 width=70%}

# Выводы

Мне удалось настроить пространство для лабораторных работ

# Список литературы{.unnumbered}

::: {#refs}
:::
