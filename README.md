# PhpStorm/WebStorm Горячие клавиши.

Список самых часто-используемых горячих клавиш для IDE [PhpStorm](https://www.jetbrains.com/phpstorm/)/[WebStorm](https://www.jetbrains.com/webstorm/). Можно забирайте себе(Fork) или добавляйте в избранное(Star).
Эта страница написана специально в дополнение к моему курсу по обзору данных редакторов на сайте сообщества сообщества [Loftblog](http://loftblog.ru/material/1-ustanovka-pervye-shagi/) и на [YouTube](https://www.youtube.com/playlist?list=PLY4rE9dstrJzAnXFt9m48Q0V5_2kVK1Qt) канале.
Сочетания клавиш указаны установленные по умолчанию. Посмотреть назначенные и изменить их можно в меню Preferences > Keymap.
Сочетания клавишь для Windows взяты с просторов интернета. Сам я работаю на Mac и проверить могу только на этой системе. Если Вы найдете ошибки, пожалуйста отправляйте запрос на исправление через GitHub(Pull request) или пишите в комментариях к видео. 


## Общие

| Команда | Mac OS X | Windows/Linux | Description |
| ------- | -------- | ------- | ----------- |
| Preferences/Settings  | `CMD + ,`     | `Ctrl + Alt + S`  | Открыть настройки программы |
| Switch tabs           | `Ctrl + Tab` | `Ctrl + Tab`  | Переключение между открытыми вкладками |
| New                   | `CMD + N`     | `Ctrl + N`  | Создать новый файл/Директорию |
| Save                  | `CMD + S`     | `Ctrl + S`  | Сохранить изменения в текущем файле |
| Save As               | `CMD + Shift + S` | `Ctrl + Shift + S`  | Сохранить изменения в файле с новым именем |
| Close Tab             | `CMD + W`     |  `Ctrl + F4` | Закрыть текущую вкладку |
| Search                | `Double Shift` | `Double Shift`  | Открыть окно поиска по проекту  |
| Find in Path          | `CMD + Shift + F` |  `Ctrl + Shift + F` | Поиск по всему проекту |
| Find Action           | ` `           |  `Ctrl + Shift + A` | Поиск опции меню или команды |



## Редактирование

| Команда | Mac OS X | Windows/Linux | Description |
| ------- | -------- | ------- | ----------- |
| Find            | `CMD + F` | `Ctrl + F`                           | Поиск по файлу  |
| Replace         | `CMD + R` | `Ctrl + R`                           | Замена найденных символов  |
| Duplicate Lines | `CMD + D` | `Ctrl + D`                           | Создать дубликат текущей строки |
| Safe Delete     | `CMD + Backspace` | `Ctrl + Y`                   | Удаление всей текущей строки |
| Joins two lines | ` `       | `Ctrl + Shift + J`                   | Объединяет две строки и убирает лишние пробелы  |
| Select block    | `ALT + up` | `Ctrl + W    Ctrl + Sift + W`       | Выделить блок кода (расширить выделение слово->предложение->конструкция->...) или наоборото |
| Multi select    | `ALT + Click` | `ALT + J`     `Alt + Shift + J`  | Множественный курсор (нажать и немного подержать - выделит все вхождения) |
| Move Line Up    | `CMD + Shift + up` | `Ctrl + Shift + up`         | Переместить текущую строку на одну строку вверх |
| Move Line Down  | `CMD + Shift + down` | `Ctrl + Shift + down`     | Переместить текущую строку на одну строку вниз |
| Line comment    | `CMD + /` | `Ctrl + /`                           | Добавить строчный комментарий |
| Block comment   | `CMD + Shift + /` | `Ctrl + Shift + /`           | Добавить блочный комментарий |
| Surround with   | `CMD + ALT + T` |  `Ctrl + ALT + T`              | Оборачивание выделенного кода, в выбраное выражение* |
| Reformat code   | `CMD + ALT + L` | `Ctrl + ALT + L`               | Восстанавливает форматирование кода согласно настройкам |
| Last Edition Location | `CMD + Shift + Backspace` | `Ctrl + Shift + Backspace`  | Вернуться к предыдущему месту редактирования |
| Rename          | `CMD + F6` |  `Shift +  F6`                      | Умное переименовывание переменной/атрибута с заменой по проекту |
| Basic Completion| ` ` |  `Ctrl + Space`                            | Автодополнение команд/атрибутов/параметров и пр. |
| Аutocompletion | ` ` | `Ctrl + Shift + Enter`                      | Автозавершение текущего оператора (или вызов метода) в синтаксически корректную конструкцию |
| First var in CC | ` ` | `Ctrl + .`                                  | Автоподстановка первого значения из код кэмплишн |



## Навигация

| Команда | Mac OS X | Windows/Linux | Description |
| ------- | -------- | ------- | ----------- |
| Quick Documentation | ` ` | `Ctrl + Q`  | Вызов всплывашки быстрой документации к выбраному классу/методу |
| Valid parametrs     | ` ` | `Ctrl + P`  | Нажатие в скобках метода/функции покажет параметры вызова |
| Find Declaration    | ` ` | `Ctrl + B`  | Поиск места определения класса/метода/переменной |
| Context Info        | ` ` | `Alt + Q`   |? Показать объявление метода без прокрутки к нему  |
| Navigation Bar      | ` ` | `Alt + Home`| Переход по структуре проекта |



## Инфо

| Команда | Mac OS X | Windows/Linux | Description |
| ------- | -------- | ------- | ----------- |
| Find Usages       | ` ` | `Alt + F7`              | Поиск по проекту использований класса, метода, переменной |
| Show Usages       | ` ` | `Ctrl + Alt + F7`       | Показать вызов/использование метода/класса/переменной во всём проекте |
| Highlight Usages  | ` ` | `Ctrl + Shift + F7`     | Подсветит переменную во всём файле (F3 и Shift+F3 - перемещение по найденному) |
| Quick Definition  | ` ` | `Ctrl + Shift + I`      | Быстрый просмотр подключаемого файла, метода и многое |
| Available Actions | ` ` | `Alt + Enter`           | Вызов списка доступных действий |
| Syntax errors     | ` ` | `F2`        `Shift + F2`| Переход по подсвеченным ошибкам синтаксиса |
| Recent changes    | ` ` | `Alt + Shift + C`       | Просмотр последних действий в проекте |

