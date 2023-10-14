## Погружение в Python 
### homework 01

1. Выведите в консоль таблицу умножения от 2х2 до 9х10 как на школьной тетрадке.

2. Треугольник существует только тогда, когда сумма любых двух его сторон больше третьей. Дано a, b, c - стороны предполагаемого треугольника. Требуется сравнить длину каждого отрезка-стороны с суммой двух других. Если хотя бы в одном случае отрезок окажется больше суммы двух других, то треугольника с такими сторонами не существует. Отдельно сообщить является ли треугольник разносторонним, равнобедренным или равносторонним.

3. Напишите код, который запрашивает число и сообщает является ли оно простым или составным. Используйте правило для проверки: “Число является простым, если делится нацело только на единицу и на себя”. Сделайте ограничение на ввод отрицательных чисел и чисел больше 100 тысяч.

4. Программа загадывает число от 0 до 1000. Необходимо угадать число за 10 попыток. Программа
должна подсказывать «больше» или «меньше» после каждой попытки. Для генерации случайного
числа используйте код:

### homework 02

1. Напишите программу, которая получает целое число и возвращает его шестнадцатеричное строковое представление. Функцию hex используйте для проверки своего результата.

2. Напишите программу, которая принимает две строки вида “a/b” - дробь с числителем и знаменателем. Программа должна возвращать сумму и произведение* дробей. Для проверки своего кода используйте модуль fractions.

### homework 03

Решить задачи, которые не успели решить на семинаре.
1. Дан список повторяющихся элементов. Вернуть список
с дублирующимися элементами. В результирующем списке
не должно быть дубликатов.

2. В большой текстовой строке подсчитать количество встречаемых
слов и вернуть 10 самых частых. Не учитывать знаки препинания
и регистр символов. За основу возьмите любую статью
из википедии или из документации к языку.

3. Создайте словарь со списком вещей для похода в качестве
ключа и их массой в качестве значения. Определите какие
вещи влезут в рюкзак передав его максимальную
грузоподъёмность. Достаточно вернуть один допустимый вариант.
*Верните все возможные варианты комплектации рюкзака.

4. Три друга взяли вещи в поход. Сформируйте словарь, где ключ — имя друга, а значение — кортеж вещей. Ответьте на вопросы:
✔ Какие вещи взяли все три друга
✔ Какие вещи уникальны, есть только у одного друга
✔ Какие вещи есть у всех друзей кроме одного и имя того, у кого данная вещь отсутствует
✔ Для решения используйте операциис множествами. Код должен расширяться на любое большее количество друзей.

## homework 04

1. Напишите функцию для транспонирования матрицы.

2. Напишите функцию принимающую на вход только ключевые параметры и возвращающую словарь, где ключ — значение переданного аргумента, а значение — имя аргумента. Если ключ не хешируем, используйте его строковое представление.

## homework 05

1. Напишите функцию, которая принимает на вход строку — абсолютный путь до файла. Функция возвращает кортеж из трёх
элементов: путь, имя файла, расширение файла.
2. Напишите однострочный генератор словаря, который принимает на вход три списка одинаковой длины: 
имена str, ставка int, премия str с указанием процентов вида «10.25%». 
В результате получаем словарь с именем в качестве ключа и суммой премии в качестве значения. 
Сумма рассчитывается как ставка умноженная на процент премии.
3. Создайте функцию генератор чисел Фибоначчи (см. Википедию).
4. Создайте функцию-генератор. Функция генерирует N простых чисел, начиная с числа 2.
Для проверки числа на простоту используйте правило: «число является простым, если делится 
нацело только на единицу и на себя».

## homework 06

1. Создайте модуль и напишите в нём функцию, которая получает на вход дату в формате DD.MM.YYYY Функция возвращает истину, если дата может существовать или ложь, если такая дата невозможна. Для простоты договоримся, что год может быть в диапазоне [1, 9999]. Весь период (1 января 1 года - 31 декабря 9999 года) действует Григорианский календарь. Проверку года на високосность вынести в отдельную защищённую функцию.
2. В модуль с проверкой даты добавьте возможность запуска в терминале с передачей даты на проверку.
3. Добавьте в пакет, созданный на семинаре шахматный модуль. Внутри него напишите код, решающий задачу о 8 ферзях. Известно, что на доске 8×8 можно расставить 8 ферзей так, чтобы они не били друг друга. Вам дана расстановка 8 ферзей на доске, определите, есть ли среди них пара бьющих друг друга. 
Программа получает на вход восемь пар чисел, каждое число от 1 до 8 - координаты 8 ферзей. Если ферзи не бьют друг друга верните истину, а если бьют - ложь.
4. Напишите функцию в шахматный модуль. Используйте генератор случайных чисел для случайной расстановки ферзей в задаче выше. Проверяйте различный случайные варианты и выведите 4 успешных расстановки.

## homework 07

1. Решить задачи, которые не успели решить на семинаре. 
Создайте функцию для сортировки файлов по директориям: видео, изображения, текст и т.п.
Каждая группа включает файлы с несколькими расширениями.
В исходной папке должны остаться только те файлы, которые не подошли для сортировки.

2. Напишите функцию группового переименования файлов. Она должна:
принимать параметр желаемое конечное имя файлов. При переименовании в конце имени добавляется порядковый номер.
принимать параметр количество цифр в порядковом номере.
принимать параметр расширение исходного файла. Переименование должно работать только для этих файлов внутри каталога.
принимать параметр расширение конечного файла.
принимать диапазон сохраняемого оригинального имени. Например для диапазона [3, 6] берутся буквы с 3 по 6 из исходного имени файла. К ним прибавляется желаемое конечное имя, если оно передано. Далее счётчик файлов и расширение. 

3. Соберите из созданных на уроке и в рамках домашнего задания функций пакет для работы с файлами.

## homework 08
1. Решить задания, которые не успели решить на семинаре.
2. Напишите функцию, которая получает на вход директорию и рекурсивно обходит её и все вложенные директории. Результаты обхода сохраните в файлы json, csv и pickle.
 Для дочерних объектов указывайте родительскую директорию.
 Для каждого объекта укажите файл это или директория.
 Для файлов сохраните его размер в байтах, а для директорий размер файлов в ней с учётом всех вложенных файлов и директорий. 
3. Соберите из созданных на уроке и в рамках домашнего задания функций пакет для работы с файлами разных форматов.

## homework 09

1. Решить задания, которые не успели решить на семинаре.
2. Напишите следующие функции:
- Нахождение корней квадратного уравнения
- Генерация csv файла с тремя случайными числами в каждой строке. 100-1000 строк.
- Декоратор, запускающий функцию нахождения корней квадратного уравнения с каждой тройкой чисел из csv файла.
- Декоратор, сохраняющий переданные параметры и результаты работы функции в json файл.
3. Соберите пакет с играми из тех файлов, что уже были созданы в рамках курса

## homework 10

1. Решить задания, которые не успели решить на семинаре.
2. Доработаем задания 5-6. Создайте класс-фабрику.
- Класс принимает тип животного (название одного из созданных классов) и параметры для этого типа.
- Внутри класса создайте экземпляр на основе переданного типа и верните его из класса-фабрики.
3. Возьмите 1-3 любые задания из прошлых семинаров (например сериализация данных), которые вы уже решали. Превратите функции в методы класса, а параметры в свойства. Задания должны решаться через вызов методов экземпляра.

## homework 11

1. Разработайте программное обеспечение для ведения журнала событий. 
Вам необходим класс, который будет представлять строки журнала и включать в себя информацию об авторе и времени создания каждой записи...
2. Разработайте программу для хранения и управления текстовыми и числовыми записями...
3. Разработайте программу для работы с прямоугольниками. Необходимо создать класс Rectangle, который будет представлять прямоугольник с заданными шириной и высотой...
4. Реализуйте класс Matrix, представляющий матрицу и поддерживающий следующие операции...

## homework 12
Создайте класс студента.
○ Используя дескрипторы проверяйте ФИО на первую заглавную букву и наличие только букв.
○ Названия предметов должны загружаться из файла CSV при создании экземпляра. Другие предметы в экземпляре недопустимы.
○ Для каждого предмета можно хранить оценки (от 2 до 5) и результаты тестов (от 0 до 100).
○ Также экземпляр должен сообщать средний балл по тестам для каждого предмета и по оценкам всех предметов вместе взятых.

## homework 13
1. Добавьте в задачу Rectangle, которую писали ранее, исключение NegativeValueError,
которое выбрасывается при некорректных значениях ширины и высоты, как при создании объекта, так и при установке их через сеттеры.
2. Допишите в вашу задачу Archive обработку исключений.
Добавьте исключение в ваш код InvalidTextError, которые будет вызываться, когда текст не является строкой или является пустой строкой.
И InvalidNumberError, которое будет вызываться, если число не является положительным целым числом или числом с плавающей запятой.
3. В организации есть два типа людей: сотрудники и обычные люди. Каждый человек (и сотрудник, и обычный) имеет следующие атрибуты:
Фамилия (строка, не пустая) Имя (строка, не пустая) Отчество (строка, не пустая) Возраст (целое положительное число). 
Сотрудники имеют также уникальный идентификационный номер (ID), который должен быть шестизначным положительным целым числом ...
## homework 14
📌 На семинаре 13 был создан проект по работе с пользователями (имя, id, уровень)
📌 Напишите 3-7 тестов pytest (или unittest на ваш выбор) для данного проекта
📌 ОБЯЗАТЕЛЬНО! Используйте фикстуры
