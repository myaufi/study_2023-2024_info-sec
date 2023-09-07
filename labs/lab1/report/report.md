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

![Создание виртуальной машины](image/placeimg_800_600_tech.jpg){#fig:001 width=70%}

Добавление носителя образ Rocky (рис. @fig:002).

![Добавление образа](image/placeimg_800_600_tech.jpg){#fig:002 width=70%}

Настройка основных параметров: язык, дата и время, администратор, хост сети (рис. @fig:003).

![Настройка параметров](image/placeimg_800_600_tech.jpg){#fig:003 width=70%}

Окончание загрузки(рис. @fig:004).

![Конец загрузки](image/placeimg_800_600_tech.jpg){#fig:004 width=70%}

Проверка заданных характеристик(рис. @fig:005).

![Заданные характеристики](image/placeimg_800_600_tech.jpg){#fig:005 width=70%}

Настройка соединения по ssh(рис. @fig:006).

![Настройка ssh](image/placeimg_800_600_tech.jpg){#fig:006 width=70%}

Клонирование репозитория(рис. @fig:008) (рис. @fig:009).

![Клонирование репозитория](image/placeimg_800_600_tech.jpg){#fig:008 width=70%} {#fig:009 width=70%}

# Выводы

Мне удалось настроить пространство для лабораторных работ

# Список литературы{.unnumbered}

::: {#refs}
:::
