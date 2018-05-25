# Решатель квадратных уравнений
решение уравнений вида Ax^2+Bx+C=0. В случае дискриминанта меньше 0, решение не предоставляется в виде комплексных числах.

# Как использовать
Функции:  **get_roots** принимает три коэффициента A,B,C.

Для применения функции в Вашем скрипте необходимо ее импортировать

**from quadratic_equation import get_roots** или **import get_roots**

## Пример использования функции
**root1, root2 = get_roots(A, B, C)**

где:

_root1_ - первый корень квадратичного уравнения

_root2_ - второй корень квадратичного уравнения

_A, B, C_ - коэффициенты квадратичного уравнения для которого мы ищем корни

## Пример кода с применением данной функции
```
def test_first_root_less_than_second(self):
    root1, root2 = get_roots(1, 2, -3)
    self.assertEqual(root1, -3)
    self.assertEqual(root2, 1)
```
 
# Как запустить
Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

## Запуск на Linux:
```
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```
## Запуск на Windows:

Происходит аналогично запуску на Linux

## Вывод в консоль
```
....
----------------------------------------------------------------------
Ran 4 tests in 0.002s

OK
```
# Цели проекта
Код создан в учебных целях. В рамках учебного курса по веб-разработке ― DEVMAN.org
