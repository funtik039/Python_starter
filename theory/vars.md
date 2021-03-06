# Переменные в Python

Переменная хранит определенные данные. Название переменной в Python должно начинаться с алфавитного символа или со знака подчеркивания и может содержать алфавитно-цифровые символы и знак подчеркивания. И кроме того, название переменной не должно совпадать с названием ключевых слов языка Python. 

Ключевых слов не так много, их легко запомнить: 

`and`, `as`, `assert`, `break`, `class`, `continue`, `def`, `del`, `elif`, `else`, `except`, `False`, `finally`, `for`, `from`, `global`, `if`, `import`, `in`, `is`, `lambda`, `None`, `nonlocal`, `not`, `or`, `pass`, `raise`, `return`, `True`, `try`, `while`, `with`, `yield`

## Типы данных в переменных

| Тип| Описание|Пример|Комментарий|
|----|---------|------|-----------|
| `boolean`|логическое значение|True или False |-|
| `int` |целое число|1, 4, 8, 50 |-|
| `float` |число с плавающей точкой|1.2 или 34.76 |-|
| `complex` |комплексные числа|x = complex(1, 2)|-|
| `str` |строка|"hello", 'world' |-|
| `bytes` |байт|132 |последовательность чисел в диапазоне 0-255|
| `byte array` |массив байтов|43, 67, 9|аналогичен bytes, но может изменяться|
| `list` |список|[1, 4, 4,"hello",'world']|-|
| `tuple` |кортеж|(1,1,4,"hello",'world')|нельзя изменить|
| `set` |неупорядоченная коллекция уникальных объектов|{1, 4, a, m}|-|
| `frozen set` |set, только не может изменяться (immutable)|{1, 4, 8, x}|-|
| `dict` |словарь, где каждый элемент имеет ключ и значение|{"Ivan":"+7932", "Igor":"+7937"}|-|
| `None` |Ничего|person = None|-|
