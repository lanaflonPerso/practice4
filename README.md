# practice4
jtr-practice4

Практическое занятие №4

Задание 1
=============================================================

Входную информацию загружать из файла part1.txt

Создать класс, который выводит содержимое текстового файла в консоль, 
заменяя в каждом слове длиннее трех символов все строчные символы 
(нижний регистр) прописными (верхний регистр).
При решении задачи использовать регулярные выражения.
Файл брать размером не более 1 Кб (достаточно несколько строк).
_______________________

Задание 2
=============================================================

Входную информацию загружать из файла part2.txt
Выходную информацию загружать в файл part2_sorted.txt

Создать класс, который создает и заполняет файл (part2.txt) случайными целыми числами от 0 до 50 (всего 10 чисел), 
затем читает файл и выводит его содержимое в другой файл (part2_sorted.txt), отсортировав числа по возрастанию.
Содержимое обоих файлов (числа разделенные пробелом) вывести в консоль.

Для сортировки написать собственный метод, который осуществляет сортировку некоторым алгоритмом (например "пузырьком"). 
Выходной файл должен быть текстовым (читабельным).
Вывести содержимое входного и выходного файла в консоль.

Пример консольного вывода:
input  ==> 30 23 16 16 9 23 3 18 21 29
output ==> 3 9 16 16 18 21 23 23 29 30

_______________________

Задание 3
=============================================================
Входную информацию загружать из файла part3.txt

Файл содержит символы, слова, целые числа и числа с плавающей точкой. Написать класс, который имеет следующую функциональность: 
в цикле пользователь вводит тип данных (один из: char, String, int, double), 
в ответ приложение печатает в консоль все значения соответствующих типов, которые существуют в файле. 
Если пользователь вводит слово stop, то происходит выход из цикла.
Задачу решить с использованием регулярных выражений.

Замечание: под строкой понимать последовательность символов два и более. 
Символы - латинские или кириллические буквы в верхнем или нижнем регистре 
(обязательно предусмотреть наличие кириллицы во входном файле).

Пример исходного файла:
a bcd 43.43 432 и л фвыа 89 .98

_______________________

Задание 4
=============================================================

Входную информацию загружать из файла part4.txt

Создать класс, который реализует интерфейс java.lang.Iterable. 
Класс должен разбирать текстовый файл и возвращать предложения из файла. 
Метод iterator данного класса должен возвращать объект итератор - экземпляр внутреннего класса.

Не допускается использовать существующие реализации итераторов из контейнерных классов! 
Используйте регулярные выражения.

Замечание. Напишите регулярное выражение, которое "вырезает" предложения из текста, 
далее используйте объект Matcher при реализации методов интерфейса Iterator.

_______________________

Задание 5
=============================================================

Входной пакет ресурсов, локаль ru: resources_ru.properties
Входной пакет ресурсов, локаль en: resources_en.properties
Пакеты ресурсов расположить непосредственно в каталоге src

Создать пакеты ресурсов (properties файлы) для двух локалей: ru и en. Пакеты содержат как минимум две записи, например:

Пример содержимого resources_en.properties
table = table
apple = apple


Пример содержимого resources_ru.properties
table = стол
apple = apple

Написать класс, который в цикле читает с консоли ключ (key) и имя локализации через пробел, 
в ответ печатает соответствующее значение в консоль. Признаком окончания ввода служит слово stop.

Чтение из консоли и запись в консоль являются обязательными!
