---
## Front matter
title: "Лабораторная работа 3"
subtitle: "Язык разметки Markdown"
author: "Смольняков Д.Е."

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
 1. Цель Работы   
 2. Задание   
 3. Теоретическое введение   
 5. Выполнение работы   
 6. Вывод   
 7. Список Литературы   
 

# Цель работы
Ознакомиться с работой языка разметки Markdown, выполнить задания в соответствии с лабораторной
работы, а также составить отчет о выполненной работе

# Задание

 1. Ознакомиться с базовыми сведениями о Markdown   
 2. Перейти в каталог "arch-pc" выполнить команду git pull   
 3. Выполнить команду make для компиляция шаблона   
 4. Удалите полученный файлы с использованием Makefile   
 5. Откройте файл report.md c помощью любого текстового редактора   
 6. Заполните отчет и скомпилируйте отчет с использованием Makefile.   
 7. Загрузить файлы на Github   
 8. Выполнить задание для самостоятельной работы   

# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

Например, в табл. [-@tbl:std-dir] приведено краткое описание стандартных каталогов Unix.

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Имя каталога | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `/`          | Корневая директория, содержащая всю файловую                                                                               |
| `/bin `      | Основные системные утилиты, необходимые как в однопользовательском режиме, так и при обычной работе всем пользователям     |
| `/etc`       | Общесистемные конфигурационные файлы и файлы конфигурации установленных программ                                           |
| `/home`      | Содержит домашние директории пользователей, которые, в свою очередь, содержат персональные настройки и данные пользователя |
| `/media`     | Точки монтирования для сменных носителей                                                                                   |
| `/root`      | Домашняя директория пользователя  `root`                                                                                   |
| `/tmp`       | Временные файлы                                                                                                            |
| `/usr`       | Вторичная иерархия для данных пользователя                                                                                 |

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы

1. Выполнение git pull (См Рис 1) 

![Название рисунка git pull (См Рис 1)](image/Photo1.jpg){width=100%}    
 git pull ( Рис 1)    

2. Выполнение make (Рис 2) 

![Название рисунка Команда Make (См Рис 2)](image/Photo2.png){width=100%}    
 Make (Рис 2)    
 
3. Удаление файлов (Рис 3) 

![Название рисунка Команда rm (См Рис 3)](image/Photo3.png){width=100%}    
Удаление файлов (Рис 3)

4. Открыть файл report.md (Рис 4) 

![Название рисунка Файл report](image/Photo4.png){width=100%}    
report.md (Рис 4)    

5. Заполнить и скомпилировать отчет (См Рис 5)

![Название рисунка Компиляция отчета](image/Photo5.png){width=100%} 
report.md (Рис 5)    

6. Загрузить файлы на гитхаб (См Рис 6) 

![Название рисунка git_ hub](image/Photo6.png){width=100%}    
Гитхаб (Рис 6)

7. Выполнить самостоятельную работу (См Рис 7)

![Название рисунка Самостоятельная работа](image/Photo7.png){width=100%}    
Самостоятельная работа (Рис 7)
# Выводы
В процессе выполнения работы, я ознакомился с языком разметки Markdown.    

# Список литературы{.unnumbered}

::: {#refs}
:::
