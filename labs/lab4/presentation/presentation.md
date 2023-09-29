---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: "Дискреционное
разграничение прав в Linux. Расширенные
атрибуты
"
author:
  - Егорова Диана Витальевна
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 16 сентября 2023

## i18n babel
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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}
  * Егорова Диана Витальевна
  * студент кафедры математического модулирования и искусственного интеллекта
  * Российский университет дружбы народов
  * [1032201662@rudn.ru](mailto:1032201662@rudn.ru)
:::
::: {.column width="30%"}



:::
::::::::::::::
# Вводная часть

## Актуальность

- Важно иметь навыки работы в консоли с атрибутами файлов
  
## Цели и задачи

Получение практических навыков работы в консоли с расширенными атрибутами файлов.

## Материалы и методы

- Процессор `pandoc` для входного формата Markdown
- Операционная система `Rocky 8.6`
- Сервис для хостинга IT-проектов `GitHub`

# Результаты выполнения работы

## Создание нового пользователя и его добавление в группу

![](image/1.png){#fig:001 width=70%} 

## Просмотр основных параметров guest и guest2 

![](image/2.png){#fig:002 width=70%}

## Регистрацию пользователя guest2 в группе guest командой newgrp guest, ищменение прав директории

![](image/3.png){#fig:003 width=70%}

## Заполнение таблицы «Установленные права и разрешённые действия»

Сравнивая таблицу с такой же таблицей из предыдущей лабораторной работы, можно скачазать, что они одинаковы. Единственное различие только в том, что в предыдущий раз я присваивала права владельцу, а в этот раз группе.

![](image/4.png){#fig:008 width=70%}

## Заполнение таблицы "Минимальные права для совершения операций" 

![](image/5.png){#fig:010 width=70%}


# Вывод

В ходе выполнения работы, мы смогли приобрести практические навыки работы в консоли с атрибутами файлов для групп пользователей.
