---
## Front matter
lang: ru-RU
title: Лабораторная работа № 4
subtitle: Операционные системы
author:
  - Голованова Мария Константиновна
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 4 марта 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

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

  * Голованова Мария Константиновна
  * НММбд-01-22, 1132226478
  * Факультет физико-математических и естественных наук
  * Российский университет дружбы народов
  
:::
::: {.column width="30%"}


:::
::::::::::::::

# Вводная часть

## Цели и задачи

- Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

## Теоретическое введение

В операционной системе GNU Linux взаимодействие пользователя с системой обычно осуществляется с помощью командной строки посредством построчного ввода команд. 
Основными командами являются:
Команда cd. Команда cd используется для перемещения по файловой системе операционной системы типа Linux.
Команда pwd. Для определения абсолютного пути к текущему каталогу используетсякоманда pwd (print working directory).
Команда ls. Команда ls используется для просмотра содержимого каталога.
Команда mkdir. Команда mkdir используется для создания каталогов.
Команда rm. Команда rm используется для удаления файлов и/или каталогов.
Команда history. Для вывода на экран списка ранее выполненных команд используется команда history. Выводимые на экран команды в списке нумеруются. К любой команде из выведенного на экран списка можно обратиться по её номеру в списке, воспользовавшись конструкцией !<номер_команды>.

# Выполнение лабораторной работы

## Выполнение лабораторной работы

- Я определила полное имя моего домашнего каталога.(рис. 1).

![Вывод полного имени моего домашнего каталога](image/Снимок экрана от 2023-03-01 13-53-00.png){.column width=70%}

- Я перешла в каталог /tmp. (рис. 2).

![Переход в каталог /tmp](image/Снимок экрана от 2023-03-01 14-09-30.png){.column width=70%}

## Выполнение лабораторной работы

Я вывела на экран содержимое каталога /tmp, используя для этого  команду ls с различными опциями (рис. 3, рис. 4, рис. 5, рис. 6, рис. 7). Разница в выводимой на экран информации объясняется тем, что различные опции позволяют увидеть дополнительные данные, которые не отображаются без дополнительных указаний к команде ls.

![Вывод на экран содержимого каталога /tmp с помощью команды ls](image/Снимок экрана от 2023-03-01 14-05-03.png){.column width=70%}

## Выполнение лабораторной работы

![Вывод на экран содержимого каталога /tmp с помощью команды ls с опцией -a](image/Снимок экрана от 2023-03-01 14-05-49.png){.column width=70%}

## Выполнение лабораторной работы

![Вывод на экран содержимого каталога /tmp с помощью команды ls с опцией -F](image/Снимок экрана от 2023-03-01 14-06-32.png){.column width=70%}

## Выполнение лабораторной работы

![Вывод на экран содержимого каталога /tmp с помощью команды ls с опцией -l](image/Снимок экрана от 2023-03-01 14-07-17.png){.column width=70%}

## Выполнение лабораторной работы

![Вывод на экран содержимого каталога /tmp с помощью команды ls с опцией -alF](image/Снимок экрана от 2023-03-01 14-07-44.png){.column width=70%}

## Выполнение лабораторной работы

- Я перешла в каталог /var/spool и вывела на экран его содержимое, проверяя, есть ли там подкаталог с именем cron (рис. 8). В каталоге /var/spool нет подкаталога с именем cron. 

![Проверка содержимого каталог /var/spool на наличие подкаталога с именем cron](image/Снимок экрана от 2023-03-04 21-34-22.png){.column width=70%}

## Выполнение лабораторной работы

- Я перешла в домашний каталог, вывела на экран его содержимое и определила, кто является владельцем файлов и подкаталогов (mkgolovanova).(рис. 9).

![Вывод на экран содержимого домашнего каталога и определение имени владельца файлов](image/Снимок экрана от 2023-03-01 14-16-18.png){.column width=70%}

## Выполнение лабораторной работы

- Я создала в домашнем каталоге новый каталог с именем newdir (рис. 10).

![Создание каталога newdir](image/Снимок экрана от 2023-03-01 14-22-12.png){.column width=70%}

## Выполнение лабораторной работы

- В каталоге ~/newdir создайте новый каталог с именем morefun (рис. 11).

![Создание каталога morefun в каталоге ~/newdir](image/Снимок экрана от 2023-03-01 14-24-06.png){.column width=70%}

## Выполнение лабораторной работы

Я создала в домашнем каталоге одной командой три новых каталога с именами letters, memos, misk, а затем удалила эти каталоги одной командой (рис. 12, рис. 13).

![Создание каталогов с именами letters, memos, miskе](image/Снимок экрана от 2023-03-01 14-26-57.png){.column width=60%}

![Удаление каталогов letters, memos, misk](image/Снимок экрана от 2023-03-01 14-30-36.png){.column width=60%}

## Выполнение лабораторной работы

Я попробовала удалить ранее созданный каталог ~/newdir командой rm. Каталог не был удалён, так как для удаления каталогов необходимо использовать опцию рекурсивного удаления -r (рис. 14).

![Попытка удаления каталога ~/newdir командой rm](image/Снимок экрана от 2023-03-01 14-31-24.png){.column width=70%}

## Выполнение лабораторной работы

Я удалила каталог ~/newdir/morefun из домашнего каталога, и проверила, был ли он удалён (рис. 15).

![Удаление каталога ~/newdir/morefun из домашнего каталога и проверка действия](image/Снимок экрана от 2023-03-01 14-33-03.png){.column width=70%}

## Выполнение лабораторной работы

С помощью команды man я определила набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов (рис. 16, рис. 17, рис. 18, рис. 19, рис. 20). Это опции -t, -lt, -ltr

![Вывод опций команды ls с помощью команды man (1)](image/Снимок экрана от 2023-03-01 14-34-27.png){.column width=35%}

## Выполнение лабораторной работы

![Вывод опций команды ls с помощью команды man (2)](image/Снимок экрана от 2023-03-01 14-34-38.png){.column width=40%}

## Выполнение лабораторной работы

![Вывод опций команды ls с помощью команды man (3)](image/Снимок экрана от 2023-03-01 14-35-04.png){.column width=40%}

## Выполнение лабораторной работы

![Вывод опций команды ls с помощью команды man (4)](image/Снимок экрана от 2023-03-01 14-35-27.png){.column width=40%}

## Выполнение лабораторной работы

![Вывод опций команды ls с помощью команды man (5)](image/Снимок экрана от 2023-03-01 14-35-42.png){.column width=40%}

## Выполнение лабораторной работы

Я использовала команду man для просмотра описания команд cd, pwd, mkdir, rmdir, rm (рис. 21, рис. 22, рис. 23, рис. 24, рис. 25, рис. 26, рис. 27).

![Вывод опций команды cd с помощью команды man](image/Снимок экрана от 2023-03-01 14-41-09.png){.column width=35%}

## Выполнение лабораторной работы

![Вывод опций команды pwd с помощью команды man (1)](image/Снимок экрана от 2023-03-01 14-42-35.png){.column width=35%}

## Выполнение лабораторной работы

![Вывод опций команды pwd с помощью команды man (2)](image/Снимок экрана от 2023-03-01 14-43-01.png){.column width=35%}

## Выполнение лабораторной работы

![Вывод опций команды mkdir с помощью команды man ](image/Снимок экрана от 2023-03-01 14-44-32.png){.column width=35%}

## Выполнение лабораторной работы

![Вывод опций команды rmdir с помощью команды man ](image/Снимок экрана от 2023-03-01 14-45-42.png){.column width=35%}

## Выполнение лабораторной работы

![Вывод опций команды rm с помощью команды man (1)](image/Снимок экрана от 2023-03-01 14-46-55.png){.column width=35%}

## Выполнение лабораторной работы

![Вывод опций команды rm с помощью команды man (2)](image/Снимок экрана от 2023-03-01 14-47-05.png){.column width=35%}

## Выполнение лабораторной работы

Используя информацию, полученную при помощи команды history (рис. 28), я выполнила модификацию и исполнение нескольких команд из буфера команд.(рис. 29, рис. 30, рис. 31).

![Выведение на экран списка ранее выполненных команд с помощью команды history](image/Снимок экрана от 2023-03-01 14-50-24.png){.column width=35%}

## Выполнение лабораторной работы

![Модификация и исполнение команды 993 из буфера команд](image/Снимок экрана от 2023-03-01 14-53-29.png){.column width=40%}

![Модификация и исполнение команды 977 из буфера команд](image/Снимок экрана от 2023-03-01 14-55-09.png){.column width=40%}

## Выполнение лабораторной работы

![Модификация и исполнение команды 1001 из буфера команд](image/Снимок экрана от 2023-03-01 14-59-28.png){.column width=50%}

# Выводы

- Я приобретела практические навыки работы с операционной системой на уровне командной строки (организация файловой системы, навигация по файловой системе, создание и удаление файлов и директорий).

