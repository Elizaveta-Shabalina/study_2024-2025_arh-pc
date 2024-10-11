---
## Front matter
title: "ЛАБОРАТОРНАЯ РАБОТА № 2"
subtitle: "Дисциплина: Архитектура компьютера"
author: "Шабалина Елизавета Андреевна"

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

Целью работы является изучить идеологию и применение средств
контроля версий. Приобрести практические навыки по работе с системой
git.


# Задание

    1. Настройка github
	2. Базовая настройка git
	3. Создание SSH ключа
	4. Сознание рабочего пространства и репозитория курса на основе
шаблона
	5. Сознание репозитория курса на основе шаблона
	6. Настройка каталога курса
	

# Выполнение лабораторной работы

1) Сначала сделаем предварительную конфигурацию git. Откроем
терминал и введем команды, указав имя и email.
Настроим utf-8 в выводе сообщений git.
Зададим имя начальной ветки (будем называть её master). Создадим
параметр autocrlf и safecrlf. (рис. [-@fig:001])

![Базовая настройка git](image/1.jpg){#fig:001 width=70%}


2) Для последующей идентификации пользователя на сервере
репозиториев необходимо сгенерировать пару ключей.
Ключи сохраняться в каталоге ~/.ssh/. Далее необходимо загрузить
сгенеренный открытый ключ. Скопировав из локальной консоли ключ в
буфер обмена вставляем ключ в появившееся на сайте поле и указываем
для ключа имя (Title). (рис. [-@fig:002])

![Создание ключа](image/2.jpg){#fig:002 width=70%}


3)загрузка открытого ключа в git (рис. [-@fig:003])

![Создание ключа](image/3.jpg){#fig:003 width=70%}



3) Сначала сделаем предварительную конфигурацию git. Откроем
терминал и введем команды, указав имя и email.
Настроим utf-8 в выводе сообщений git.
Зададим имя начальной ветки (будем называть её master). Создадим
параметр autocrlf и safecrlf. (рис. [-@fig:003])

![загрузка открытого ключа в git](image/3.jpg){#fig:003 width=70%}


4) Откроем терминал и создадим каталог для предмета «Архитектура
компьютера»  (рис. [-@fig:004])

![.](image/4.jpg){#fig:004 width=70%}


5) Перейдем на страницу репозитория с шаблоном курса. Далее выберите
Use this template. В открывшемся окне задаем имя репозитория и создаем
репозиторий.
Откроем терминал и перейдем в каталог курса и клонируем созданный
репозиторий. (рис. [-@fig:005])

![клонирование репозитория](image/5.jpg){#fig:005 width=70%}


6) Перейдем в каталог курса и удалим лишние файлы. Создаем
необходимые каталоги и отправляем файлы на сервер. Затем проверяем
правильность создания иерархии рабочего пространства в локальном
репозитории и на странице github. (рис. [-@fig:006])

![.](image/6.jpg){#fig:006 width=70%}


# Выполнение самостоятельной работы

1) Создаём отчет по выполнению второй лабораторной работы и загружаем на github (рис. [-@fig:007])

![лаб 1](image/7.jpg){#fig:007 width=70%}


2) то же самое делаем с первой лабораторной (рис. [-@fig:008])

![.лаб 2](image/8.jpg){#fig:008 width=70%}


# Выводы

Я изучила идеологию и применение средств
контроля версий. Приобрела практические навыки по работе с системой
git.


# Список литературы{.unnumbered}

