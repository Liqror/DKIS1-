Практическая 1

Вариант 13: Помещение, учебная аудитория, кабинет, спортзал.

Для того, чтоб все заработало:
1. Перейдите в папку src
2. Выполните в консили: javac -encoding UTF-8 project/Main.java 
3. Запустите в консоли: java project.Main

Подробное описание задания:

Для каждого варианта имеется набор из четырех сущностей. Необходимо выстроить иерархию наследования. В каждом классе (базовом и производных) должно быть минимум одно числовое и одно текстовое поле. При вводе числовых параметров обязательна проверка на число и на диапазон (даже если число может быть любое, проверку необходимо реализовать).

Для всех классов должны быть реализованы конструкторы (по умолчанию, с параметрами), методы equals(), hashCode(), toString().

Необходимо реализовать консольное Java-приложение, которое имеет простейшее пользовательское меню, состоящее как минимум из следующих пунктов:

1. Добавить новый элемент (Элементы должны добавляться в коллекцию элементов типа базового класса. Необходимо предусмотреть возможность добавления любого объекта производного класса в данную коллекцию).
2. Удалить элемент по индексу
3. Вывод всех элементов в консоль
4. Сравнение двух элементов на равенство (по индексам)
5. Завершение работы приложения.