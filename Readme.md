# Инструкция по работе с Git

## Что такое Git?

Git - одна из реализаций распределенных систем контроля версий, позволяющая организовать версионность, как локально, так и на удаленном сервере. Самая популярная платформа, реализующая *Git*, - [GitHub](https://github.com)

## Подготовка репозитория

Для создания в папке репозитория необходимо открыть эту папку в терминале и написать команду git init, после чего в этой папке создастся скрытая папка *. git*, таким образом папка станет репозиторием. 

## Создание коммитов

### Создание фиксации

Для создания фиксаций используется команда *git commit*. Для этого в терминале с папкой-репозиторием необходимо написать команду git commit -m "Сообщение к коммиту". Сообщение к комминту писать **Обязательно**.

### Добавление файла к сохранению

Для того, чтобы добавить файл к сохранению, необходимо использовать команду *git add*. В терминале с открытой папкой-репозиторием необходимо написать *git add <название файла>*, и этот файла добавится к сохранению.

### Просмотр состояния репозитория

Для просмотра состояния репозитория используется команда git status. В терминале с открытой папкой-репозиторием необходимо написать команду git status. В  результате можно увидеть следующие выводы:
1. On branch *** nothing to commit - это означает нет активных изменений
2. Untrecked file - это означает, что имеются файлы, не отслеживаемые системой контроля версий
3. ...

## Журнал изменений

Для просмотра историй изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log*, и вы увидите список всех коммитов в этой ветке с описанием: имени, электронной почты, сообщением к коммиту и номер коммита.

## Перемещение между коммитами

Для перемещения между коммитами используется команда git checkout. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout <номер коммита>*. Номер коммита берется из журнала изменений ветки.

## Ветки в git

## Слияние веток ирешение конфликтов

## Удаление веток