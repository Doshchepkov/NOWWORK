---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Дисциплина: Архитектура компьютера"
author: "Ощепков Дмитрий Владимирович"

## Generic otions
lang: ru-RU
## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl
## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Настройка каталога для виртуальных машин
# Настройка хост-клавиши
# Создание виртуальной машины

Все эти этапы были сделаны в прошлом семестре, результат этих пунктов был показан на видео

# После установки
# Обновления и повышение комфорта работы

![Получил права супер-пользователя и обновил пакеты](Images1/1.png){ #fig:001 width=80% }

# Автоматическое обновление

![Установил программное обеспечение для автоматических обновлений](Images1/2.png){ #fig:002 width=80%}

# Запуск таймера

![Запустил таймер](Images1/3.png){ #fig:003 width=80% }

# Отключение SELinux

![Заменил значение в config](Images1/11.png){ #fig:004 width=80% }

# Установка драйверов для VirtualBox

![Установка пакета DKMS](Images1/5.png){ #fig:005 width=80%}

![Установка драйверов](Images1/6.png){ #fig:006 width=80%}

# Настройка раскладки клавиатуры

![Отредактирвал конфигурационный файл](Images1/7.png){ #fig:007 width=80%}

# Установка имени пользователя и названия хоста

Все было установлено сразу правильно

# Установка программного обеспечения для создания документации

![Установил pandoc:](Images1/8.png){ #fig:008 width=80% }

![Установил texlive:](Images1/10.png){ #fig:010 width=80% }

# Выводы

Приобрел практические навыкм установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

Ответы на контрольные вопросы:

::: {#refs}
:::
