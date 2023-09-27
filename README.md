# Частное введенных чисел
Выполнила: Бурганова Дарья, ФТ-220008.

Задание: добавить в программу вывод частного введенных чисел с точность до сотых 0,00.

***Проект можно открыть в:***

- Visual Studio 

- Atom

Чтобы увидеть программу, Вам следует открыть файл **whatisit**. Затем нужно ввести два числа типа **float** с клавиатуры:
```python
a = float(input("Введите первое число: "))
b = float(input("Введите второе число: "))
```
Программа вычислит частное этих чисел:
```python
chastn = a / b
```
И выведет результат:

```python
print("Частное чисел {0} и {1} равно {2:.2f}".format(a, b, chastn))
```

Тесты:

![test1](https://sun9-77.userapi.com/impg/VujMnbnLQauYw1s7FeODVzX5cp02pCgNm-f6pA/5bt1hKCB_Ik.jpg?size=412x91&quality=96&sign=eee6a35e01d3bb7fdb5139140d6e0051&type=album)
![test2](https://sun9-71.userapi.com/impg/M8aYiZH974XpTqLBToX9OLxU3HhiDLAfCcZpLw/Fxd5E63TK9M.jpg?size=413x94&quality=96&sign=6fa107b5dc799e0b50f1e5255fb88ec2&type=album)