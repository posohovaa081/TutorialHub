# Инструкция для работы с Git и удаленными репозиториями ![Это Git](git.jpeg.jpeg)
 
## Что такое Git?
Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.
 
## Подготовка репозитория
Для создания репозитория необходимо выполнить команду "git init" в папке с репозиторием и у Вас создаться репозиторий (появится скрытая ппка .git)

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов
Для того, чтобы создать коммит (сохранение) необходимо выполнить команду "git commit". Выполняется она так: *git commit -m"<сообщение к коммиту>*. Все файлы для коммита должны быть ***добавлены*** и сообщение к коммиту писать ***обязательно***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она впапке с репозиторием следующим образом: *git checkout <номер коммита>*
 
### Git add
Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

## Журнал изменений
Для того, чтобы посмотреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Cоздание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием *git branch <название новой ветки>*. После данной операции ветка уже была создана, но вы по-прежнему находитесь в прежней ветке.

## Слияние веток
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*.Чтобы вмерджить ветку в мастер, нужно сначала перейти в master.

## Просмотр списка веток
Можно просматривать полный список веток, используя параметр *git branch*. Команда отобразит все ветки, отметит текущую звёздочкой (*) и выделит её цветом.

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"


## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"
