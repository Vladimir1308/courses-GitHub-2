# Инструкция для работы с Git и удаленными репозиториями

## Что такое Git?
<u>Git</u> - *Предназначенная для быстрой и эффективной работы с любыми проектами, от небольших до очень крупных.*
## Подготовка крепозитория
Для создание репозитория необхадимо выполнять команду *git init* в папке с репозиторием и у Вас создается репозиторий (появится скрытая папка .git).
>Пример
![Как должно выглядить](pictures\gitinit.png)

## Создание коммитов 
### Git add
Для добавления изменеий в коммит команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*. 
> добовляем две первых буквы имени файла жмем кнопку *Tab*.

>Пример 
![Как должно выглядить](pictures\gitadd.png)

## Просмотр состояния репозитория
### git status
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, Вы увидете были ли изменения в файлах, или их небыло. 
> Без изменения файла 
![Как должно выглядить](pictures\gitstatus.png)

> С изменением файла
 ![Как должно выглядить](pictures\gitstatus2.png)

## Создания комитов 
### git commit
Для того, чтобы создать комит(сохранение) необходимо выполненить команду *git commit*. Выполняется она так: *git commit -m "коментарий"*.

> Пример
![Как должно выглядить](pictures\gitcommit.png)

## Просмотр истории коммитов с изменениями
### git log
Просматривать изменения, внесённые в репозиторий, можно с помощью параметра *git log* он отображает список последних коммитов, внесённые в каждый файл.
> Пример
![Как должно выглядить](pictures\gitlog.png)

##  Переход коммитам
### git checkout и git checkout master
Переход от одного комита к другому можно с помощью параметра *git checkout <указывется имя сохраненого раздела>*.
> Пример
![Как должно выглядить](pictures\gitcheckaut.png)

Для возврата актуального ссостояние и продолжить работу, нужно использоват команду *git checkout master*.
 >Пример
![Как должно выглядить](pictures\gitcheckoutmaster.png)

## Просмотр изменений до коммита
### git diff
Можно просматривать список изменений, внесённых в репозиторий, используя команду *git diff*.
>Пример
![Как должно выглядить](pictures\gitdiff.png)

## Менеджер веток
### git branch
Команда умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их. Используя команду *git branch* перечисляет ветки,0
 1. *git branch (имя ветки)* создание ветки, 
 1. *git branch -d (имя ветки)* удаления ветки.

>Пример
![Как должно выглядить](pictures\gitbranch.png)

## Просмотр истории виде дерева
### git log --graph
Команда показывает сколько веток на истории коммитов,  используя команду *git log --graph*.Команда показывает сколько веток на истории коммитов,  используя команду *git log --graph*.

>Пример
![Как должно выглядить](pictures\gitlog--graph.png)

## Cлияния одной или нескольких веток
### git merge
Команда используется для слияния одной или нескольких веток в текущую. Затем она устанавливает указатель текущей ветки на результирующий коммит.

>Пример
![Как должно выглядить](pictures\gitmerge.png)


Ссылка:

[Git - Основные команды][1]

[Язык разметки Markdown][2]

[1]: https://git.github.io/git-scm.com/book/ru/v2/Приложение-C:-Команды-Git-Основные-команды
[2]:https://skillbox.ru/media/code/yazyk-razmetki-markdown-shpargalka-po-sintaksisu-s-primerami/#stk-19

Перенос ДЗ на Git Hub

