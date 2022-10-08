---
## Front matter
lang: ru-RU
title: Дискреционное разграничение прав в Linux. Исследование влияния дополнительных атрибутов
author: Абузярова Лейла Джамилевна	НБИбд-01-19
institute: Российский Университет Дружбы Народов
date: 8 октября, 2022, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---

# Цели и задачи

## Цель лабораторной работы

Изучение механизмов изменения идентификаторов, применения SetUID и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрение работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

# Выполнение лабораторной работы

## Подготовка к работе

![Установка компилятора gcc](image/01.png){ #fig:001 width=70% height=70%}

## Подготовка к работе

![Подготовка к работе](image/02.png){ #fig:002 width=70% height=70%}

## Подготовка к работе

![Проверка установки компилятора](image/03.png){ #fig:003 width=70% height=70%}

## Работа с файлом simpleid

![Создание и редактирование файла simpleid.c](image/04.png){ #fig:004 width=70% height=70%}

## Работа с файлом simpleid

![Написание программы](image/05.png){ #fig:005 width=70% height=70%}

## Работа с файлом simpleid

![Результат программы simpleid](image/06.png){ #fig:006 width=70% height=70%}

## Работа с файлом simpleid2

![Создание и редактирование файла simpleid2.c](image/07.png){ #fig:007 width=70% height=70%}

## Работа с файлом simpleid2

![Написание программы](image/08.png){ #fig:008 width=70% height=70%}

## Работа с файлом simpleid2

![Результат программы simpleid2 от guest](image/09.png){ #fig:009 width=70% height=70%}

## Работа с файлом simpleid2

![Результат программы simpleid2 от root](image/10.png){ #fig:010 width=70% height=70%}

## Работа с файлом readfile

![Создание и редактирование файла readfile.c](image/11.png){ #fig:011 width=70% height=70%}

## Работа с файлом readfile

![Программа readfile](image/12.png){ #fig:012 width=70% height=70%}

## Работа с файлом readfile

![Смена прав на файле readfile](image/13.png){ #fig:013 width=70% height=70%}

## Работа с файлом readfile

![Проверка файла на чтение](image/14.png){ #fig:014 width=70% height=70%}

## Работа с файлом readfile

![Повторная проверка файла на чтение](image/15.png){ #fig:015 width=70% height=70%}

## Исследование Sticky-бита

![Проверка прав на файле file01.txt](image/16.png){ #fig:016 width=70% height=70%}

## Исследование Sticky-бита

![Дозапись и перезапись слов в файл file01.txt](image/17.png){ #fig:017 width=70% height=70%}

## Исследование Sticky-бита

![Снятие атрибута t](image/18.png){ #fig:018 width=70% height=70%}

# Выводы

## Результаты выполнения лабораторной работы

Изучили механизмы изменения идентификаторов, применения SetUID- и Sticky-битов. Получили практические навыки работы в консоли с дополнительными атрибутами. Также мы рассмотрели работу механизма смены идентификатора процессов пользователей и влияние бита Sticky на запись и удаление файлов.