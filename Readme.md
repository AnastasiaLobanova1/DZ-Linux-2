# Файлы и каталоги в Linux
## ДЗ Лобанова Анастасия
### Задания
![Задание 1-5](https://thumb.cloud.mail.ru/weblink/thumb/xw1/5Zox/X8cieQYRw)

![Задание 6-12](https://thumb.cloud.mail.ru/weblink/thumb/xw1/MSXa/78uyKE4bd)

![Задание 13](https://thumb.cloud.mail.ru/weblink/thumb/xw1/9T4g/mWmGwLWWX)

### Контрольные вопросы
1. ls -d – вывод сведений о директории без вывода ее содержимого
 
   ls -i – отобразить inode, в котором находится файл

   ls -t - отображает файлы в порядке последней модификации, начиная с самого недавнего

   ls -r - отображает файлы в обратном порядке
![ls -d,-i,-t,-r](https://thumb.cloud.mail.ru/weblink/thumb/xw1/y6RE/7V5s96xcM)

2. ls -v – сортировка по номеру версии файла

    ls -w – для задания ширины колонки

    ls -l – вывести длинный список с подробной информацией
    
    ls -S – вывод отсортированных файлов в зависимости от их размера. Объекты будут располагаться по списку от большего по размеру к меньшему

![ls -v, -w, -l, -S](https://thumb.cloud.mail.ru/weblink/thumb/xw1/UxXk/Bd561LEkg)

3. ls -R – отобразить список из подкаталогов путем рекурсивного вывода
   
   ls -F – включить видимость типа объекта. Узнать тип объекта можно по присвоенному символу, который отображается в конце названия файла

   ls -A – отображение всех файлов, кроме скрытых

   ls -v – сортировка по номеру версии файла

![ls -R, -F, -A, -v](https://thumb.cloud.mail.ru/weblink/thumb/xw1/S1uX/D8cEZadCv)

4. ls -x	Вывод в несколько колонок с сортировкой по строкам
   
   ls -С – вывод файлов колонками

   ls --full-time – вывод информации в полном объеме, включая время в формате ISO

   ls -h – для преобразования значений размера файлов в нужный формат. Автоматически размер файлов отображается в байтах без указания единицы измерения

   ![ls -x, -C, --full-time, -h](https://thumb.cloud.mail.ru/weblink/thumb/xw1/6YAc/mkRcfykvA)

5. Для чего предназначена команда pwd?
   
Это весьма простая утилита, благодаря которой можно выводить в терминал путь к текущей папке. С запуском каждая программа получает текущую папку, в которой будут происходить все операции с файлами этой программы, если не указан другой путь.

6. Для чего предназначена команда cd? Как её использовать? Что делает команда cd ~
   
Команда cd (change directory) используется для изменения текущей директории в командной строке или терминале операционной системы. При выполнении команды cd с указанием пути к желаемой, текущая рабочая директория изменяется на указанную

cd [путь_к_папке]

Переход в домашнюю директорию
Домашняя директория текущего пользователя обозначается значком тильда ~. Для перехода в домашнюю директорию используется команда:

cd ~

7. Продемонстрируйте и прокомментируйте использование опций команды rm
   
Команда rm удаляет файлы или каталоги

-f - не запрашивать подтверждения операции, не выдавать диагностических сообщений, не возвращать код ошибочного завершения, если ошибки были вызваны несуществующими файлами;

-i - выводить запрос на подтверждение операции удаления (если заданы одновременно опции -f и -i, то срабатывает последняя указанная);

-r или -R - рекурсивное удаление дерева каталогов.

![rm](https://thumb.cloud.mail.ru/weblink/thumb/xw1/eeHm/qGHGDpTtZ)

8. Продемонстрируйте и прокомментируйте использование опций команды rmdir

Команда rmdir удаляет пустые каталоги. Если какой-либо из аргументов каталог не указывает на существующий пустой
каталог, то будет выдано сообщение об ошибке.

-p - если каталог включает более чем один компонент пути, то удаляется каталог, затем убирается последний компонент пути и удаляется получившийся каталог и т. д. до тех пор, пока все компоненты не будут удалены. Таким образом, команда rmdir -p a/b/c эквивалентна последовательности команд rmdir a/b/c; rmdir a/b; rmdir a.

![rmdir](https://thumb.cloud.mail.ru/weblink/thumb/xw1/BK3D/s85rV5XpU)

9. Продемонстрируйте и прокомментируйте использование опций команды mv

Команда mv (от англ. move) —используется для перемещения или переименования файлов.

Опции команды mv:

–f - не запрашивать подтверждения операций;

–i - выводить запрос на подтверждение операции, когда существует файл, в который происходит переименование или перемещение.

![mv](https://thumb.cloud.mail.ru/weblink/thumb/xw1/K4A1/1xRtsCYDd)

10. Продемонстрируйте и прокомментируйте использование опций команды cp

Команда cp (от англ. copy) копирует файлы или каталоги.

Если последний аргумент является существующим каталогом, то команда cp копирует каждый из заданных в качестве параметров команды файлов в этот каталог. Если задано только два имени файла, то команда копирует первый файл
во второй. Подробности применения команды можно получить, используя команду man cp.

![cp](https://thumb.cloud.mail.ru/weblink/thumb/xw1/dH15/xdB6un4cV)

11. Продемонстрируйте и прокомментируйте использование опций команды cat

Команда cat (от англ. concatenate) — последовательно выводит указанные файлы, таким образом, объединяя их в единый поток. Если вместо имени файла указывается «-», то
читается стандартный ввод.

![cat](https://thumb.cloud.mail.ru/weblink/thumb/xw1/jfcf/kkEdCsiJM)

12. Соответствует ли строка «sapr» шаблону [!a]? Почему?

Не соответствует.

Термин "строка" обычно используется для указания любой последовательности символов; типичные примеры строк - вводимые пользователем символы или отдельный аргумент команды. Пользователи вводят запросы в ответ на приглашение командной строки, генерируются имена файлов, команды что-то выводят. Часто при этом бывает нужно определить, соответствует ли заданная строка заданному шаблону; этот процесс называется сопоставлением с шаблоном. Командная оболочка предоставляет довольно развитые средства сопоставления.

Если вы не знаете, чего хотите, но точно знаете, чего НЕ хотите, вы можете инвертировать класс символов, используя восклицательный знак (!) как его первый символ. Класс символов [!а] будет соответствовать любому символу, кроме а. Когда класс символов инвертирован, он соответствует абсолютно любому символу, не входящему в диапазон, а не только очевидным или "обычным".
