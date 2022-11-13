![](https://icon2.cleanpng.com/20180221/kzq/kisspng-service-robot-microsoft-powerpoint-chatbot-robot-5a8df110542cc3.3413058015192517283448.jpg)


# Инструкция для работы с Git и удалёнными репозиториями


## Что такое Git?             
---
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
---
Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

---

## Создание коммитов
### Git add

Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add &lt;имя файла&gt;*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "&lt;сообщение к коммиту&gt;*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
---
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout &lt;номер коммита&gt;*

## Журнал изменений
---
Для того, чтобы посмотреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git
---
### Создание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch &lt;название новой ветки&gt;*

## Слияние веток
---
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*

## Удаление веток
---
Для удаления ветки ввести команду "git branch -d 'name branch'"


для работы с текстом использовал данный [ресурс](https://texterra.ru/blog/ischerpyvayushchaya-shpargalka-po-sintaksisu-razmetki-markdown-na-zametku-avtoram-veb-razrabotchikam.html "подсказки по Git")


![картинка](https://learn.microsoft.com/ru-ru/contribute/media/markdown-reference/document.png)

>привет! как дела?
>>хорошо
>>>давай не болей)