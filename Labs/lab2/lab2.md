---
## Front matter
title: "Отчёт по лабораторной работе №2"
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

Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.

# Базовая настройка git

![Задал имя и email владельца репозитория и настроил utf-8 в выводе сообщений git, задал имя начальной ветки](Images2/2.1.png){ #fig:001 width=80% }

# Параметр autocrlf

![Параметр autocrlf](Images2/2.2.png){ #fig:002 width=80%}

# Создаю ключ ssh

![Создал ключ](Images2/2.3.png){ #fig:003 width=80% }

![Добавил на гит](Images2/2.4.png){ #fig:004 width=80% }

# Создаю ключ pgp

![Созддал ключ](Images2/2.5.png){ #fig:005 width=80%}

![Получание ключа в чистом виде](Images2/2.6.png){ #fig:006 width=80%}

![Подключил к гиту](Images2/2.7.png){ #fig:007 width=80%}

# Настройка gh

![Авторизовался](Images2/2.8.png){ #fig:008 width=80% }

# Сознание репозитория курса на основе шаблона

![Клонировал репозиторий](Images2/2.9.png){ #fig:009 width=80% }

# Выводы

Изучил идеологию и применение средств контроля версий.
Освоил умения по работе с git.

::: {#refs}
:::
