# Контрольные задачи (1-5) по предмету "Структури даних і алгоритми"
Вернигор Виталий ТК-3

# src.BinaryHeap
Задача:
4. Бінарна куча.  Для заданого масиву ключів (більше 15 значень, задати випадково – цілі числа з множини [0, 100]) побудувати бінарну кучу, реалізувати операції додавання елемента, видалення мінімального елемента. Вивести побудовані дерева.
Описание:
Реализуется структура данных с абстрактным типом данных.  Для хранения вершин используется ArrayList. Для каждой вершины под номером i её левый сын хранится в 2*i+1 вершине, а правый — в 2*i+2 вершине.

Класс содержит следующие методы:

Heap() — конструктор.

shiftUp() — восходящее восстановление свойства кучи. Сложность: О(Log(n))

shiftDown() — нисходящее восстановление свойства кучи. Сложность: О(Log(n))

insert() — добавление элемента в кучу.

delete() — удаление первой вершины. Сложность: О(Log(n))

size() — размер кучи.

isEmpty() — проверка на пустоту.

toString() — преобразование в строку.

max() — максимальный элемент. Сложность: О(1)

print() — вывод кучи на экран.

# src.BlackAndRedTree
Задача:
3. Червоно-чорне дерево. Для заданого масиву ключів (більше 15 значень, задати випадково – цілі числа з множини [0, 100]) побудувати червоно-чорне дерево, реалізувати операції додавання елемента, видалення елемента. Вивести побудовані дерева.

# src.Huffman
Задача:
1. Кодування Хаффмана. Взяти  фрагмент тексту (не менше 100 символів). Реалізувати алгоритм кодування Хаффмана. Отриману систему кодування представити у вигляді дерева.
Описание:
Текст помещённый в input.txt преобразовывается в двоичный с помощью алгоритма кодировки Хаффмана
Если отсутствует файл - пользователю предлогается ввести текст вручную.
Есть возможность декодировать полученный код, дабы убедиться в его корректности.
Управление:

[-1] Завершение 

[1] Вод нового текста

[2] Кодирование текста

[3] Декодирование текста

