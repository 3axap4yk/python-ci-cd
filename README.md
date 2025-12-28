# Простой калькулятор на Python

Минимальная библиотека калькулятора с базовыми операциями и тестами

## Возможности

- Сложение (`add`)
- Вычитание (`subtract`)
- Умножение (`multiply`)
- Деление (`divide`) — с обработкой ошибки деления на ноль

## Требования

- Python 3.6+

## Использование

```python
from calculator import add, divide

print(add(10, 5))      # 15
print(divide(20, 4))   # 5.0
```

## Запуск тестов
Чтобы запустить модульные тесты, выполните в терминале:
```bash
python -m unittest test_calculator.py -v
```

Или
```bash
python test_calculator.py
```