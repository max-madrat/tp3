# Техническое задание по ТП №3
## Часть №1 Тестирование
### 1.Реализованы функции чтения из файла, поиска минимального числа, поиска максимального числа, сложения и умножения всех чисел из файла
### 2.Реализованы тесты для проверки корректности функций поиска минимума, максимума, сложения и умножения
### 3.Реализованы тесты для проверки скорости работы программы при увеличении размера входного файла
> Каждая функция тестируется на нескольких масивах. В результате работы выводится вес каждого массива и время необходимое для реализации функции для него. Для этого была использована библиотека datetime
```
    from datetime import datetime
```
>  При тестировании замечены разные результаты по времени, и из-за маленького объема данных случается, что время работы отличается либо на малую величину, либо не отличается вовсе
### 4.Реализована функция подсчета среднего арифметического всех чисел в массиве и проверка к ней.
### 5.  Программа реализована так, чтобы не возникало аварийного завершения работы программы из-за ошибки переполнения
> Блок try-except сработает только если будет встречена ошибка переполнения
```
    except OverflowError:
        return "Слишком большие данные"
```
---
