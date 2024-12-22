
# Лабораторная работа: Команда grep

Лабораторная работа посвящена изучению возможностей команды `grep` для поиска и фильтрации данных в текстовых файлах с использованием регулярных выражений.

## Пример 
Создадим текстовый файл `test.txt` с некоторым содержимым. Например:

```
Happy New Year! 
Happy New Year!
May we all have a vision now and then
Of a world where every neighbour is a friend.

Happy New Year! 
Happy New Year!
May we all have our hopes, our will to try
If we don`t, we might as well lay down and die
You and I...
```  

Теперь попроубем найти строки этого файла, в которых содержится слово `new` (любого регистра). Для этого используем команду `grep`:

```bash
grep -i "new" test.txt
```
Должен получиться следующий вывод:

```
Happy New Year!
Happy New Year!
Happy New Year!
Happy New Year!
```

## Задание  
Вам дан файл `people.txt`, в каждой строке которого содержатся данные о людях: фамилия, имя, отчество и возраст. Они записаны в формате:

```
Иванов Иван Иванович, 25
```

Выведите все строки, в которых содержится информация о людях, в возрасте которых только одна цифра 2.

## Источники

[Google](https://google.com)

[GNU Grep](https://www.gnu.org/software/grep/manual/grep.html#Regular-Expressions)
