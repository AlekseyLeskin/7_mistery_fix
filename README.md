# Решатель квадратных уравнений

Это простой пример использования тестирования в Python на примере функции, которая вычисляет корни квадратного уравнения:

1.  "quadratic_equation.py" - это скрипт, который вычисляет корни квадратного уравнения. Если у Вас есть уравнение вида "ax2 + bx + c = 0", то данный скрипт поможет его решить. Просто введите значения a, b и c в качестве аргументов функции.
2.  "tests.py" - это скрипт тестирования для "quadratic_equation.py". Подробнее о юнит-тестировании в Python можно почитать по ссылке - https://github.com/cgoldberg/python-unittest-tutorial#unittest---automated-testing-framework

# Как использовать

* склонировать этот репозиторий
* запустить tests.py для юнит-тестирования "quadratic_equation.py
* импортировать функцию в свой скрипт и запустить её с необходимыми значениями. Пример:

```bash
from quadratic_equation import get_roots

print(get_roots(3,-12,0))
```
В результате работы данного кода будет выведено: 
```
(0.0, 4.0)
```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
