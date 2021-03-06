# RPPZL2017-09-02 / RPPZL2017.

### Начало работы:

<b>Посмотрите видео: <a href="https://youtu.be/mIs-X63CH78" target="_blank">Tutorial:QuickStart</a></b>

1. Инициализация. Нажмите Fork на странице https://github.com/Khmelov/RPPZL2017-09-02/
2. У вас в аккаунте fork появится тут  https://github.com/ваш_логин/RPPZL2017-09-02
3. Выберите в IDEA VCS -> Checkout version control -> GitHub и затем:
 * укажите ссылку на Ваш fork https://github.com/ваш_логин/RPPZL2017-09-02;
 * выберите путь к папке проекта;
 * укажите имя папки проекта (например RPPZL2017-09-02_verXX - такой папки на диске быть не должно).

### Перезапуск проекта (требуется не всегда, только при сбоях):
Многие настройки проекта хранятся в файле RPPZL2017-09-02.iml и папке .idea.
Эти настройки могут быть разными на разных машинах.

Чтобы запустить проект с нуля в Windows Вам нужно распаковать Init.zip

1. Если все нормально вы увидите iml-файл в корне проекта
2. При необходимости настройте SDK и среду (File-Project Structure)

Теперь осталось лишь открыть и закрыть проект. Шаги:

1. File-Close
2. Откроется меню с последними проектами, выберите самый первый в списке.
3. Настройте параметры проекта (SDK, JUnit и т.д.)

Проделав шаги по запуску проекта вы всегда можете СБРОСИТЬ все настройки проекта.
Папки с исходными файлами при этом не пострадают.

### Перед **каждым** сеансом работы:

1. Получите последние изменения основного репозитория VCS -> Git -> Rebase my GitHub fork
2. Отправьте эти изменения в свой репозиторий VCS -> Git -> Push

### Работаем с кодом:

1. Работайте ...
2. Добейтесь чтобы проект собирался и запускался без ошибок (В РЕЖИМЕ JAVA 7 - ЭТО ВАЖНО !!!).
3. Делайте коммиты Ctrl+K.
 * _возврат на пункт 1  n раз ;)_
5. Отправьте накопленные изменения в свой репозиторий VCS -> Git -> Push
6. Если работа завершена, а проект собирается и запускается, то можно сделать VCS -> Git -> Pull Request
<br>_при Pull Request-е видно какие изменяются файлы. В идеале должны быть изменения только в вашей папке_

### ВНИМАНИЕ!

Если проект не запускается из-за ошибок в чужих папках **НЕ ИСПРАВЛЯЙТЕ ИХ!**.
<br>Кто-то их тоже исправит и будет конфликт слияния на github.
<br>А как тогда сделать правильно? Просто отключите проблемную папку:
* выделите её в дереве проекта
* нажмите на ней правой кнопкой мыши
* Выполните команду Mark Directory as -> Excluded
* эта команда затронет только Ваш компьютер

### Если все поломалось!

1. **Скопируйте** свою папку из src/by/it/ в отдельное место на диске.
 * найти свою папку на диске можно выделив ее в дереве папок в IDEA. Далее, правая кнопка -> Show in Explorer.
2. Удалите fork из своего аккаунта github (откройте форк на сайте, выберите Setting-Delete this repository)
3. Выполните всю последовательность из шапки (см. <b>Начало работы</b> и <b>Запуск проекта</b>).
4. Верните свою папку на место в свежем проекте.

_С уважением, Александр Хмелев._

