---
## Front matter
title: "Четвертый этап индивидуального проекта"
author: "Беличева Д.М.; НКНбд-01-21"

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
lot: false # List of tables
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

Продолжить редактирование своего сайта. Добавить ссылки на научные ресурсы.

# Задание

1. Разместить ссылки на научные ресурсы (гитхаб, ютуб) на сайте.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:

- Оформление отчёта

- Создание презентаций

- Работа с библиографией

# Теоретическое введение

Сайт – это совокупность веб-страниц, объединённых под общим доменом и связанных ссылками, тематикой и дизайнерским оформлением [@Site:bash] . Мы создали статический сайт с помощью Hugo.
Hugo — генератор статических страниц для интернета.

В этом этапе я напишу пост про оформление отчета. Отчет — это структурированное сообщение о результатах вашей работы, которое вы делаете в устной или письменной форме.

# Выполнение лабораторной работы

1. Разместим ссылки на научные ресурсы (гитхаб, ютуб) на сайте.  (рис. [-@fig:001;-@fig:002])

![Добавление ссылок на научные ресурсы](image/1.png){ #fig:001 width=70% }

![Результат на сайте](image/2.png){ #fig:002 width=70% }

2. Сделаем пост по прошедшей неделе. (рис. [-@fig:003;-@fig:004])

![Текст поста по прошедшей неделе](image/3.png){ #fig:003 width=70% }

![Результат на сайте](image/4.png){ #fig:004 width=70% }

3. Добавим пост на тему оформление отчета. (рис. [-@fig:005;-@fig:006])

![Текст поста про оформление отчета](image/5.png){ #fig:005 width=70% }

![Результат на сайте](image/6.png){ #fig:006 width=70% }

# Выводы

В процессе выполнения этого этапа проекта я добавила на сайт ссылки на свои научные аккаунты, а также написала два поста.

# Список литературы{.unnumbered}

::: {#refs}
:::
