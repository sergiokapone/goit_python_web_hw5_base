# Домашнє завдання #5 (Основна обов'язкова частина)

Консольна утиліта, яка повертає курси валют ПриватБанку протягом останніх кількох днів.

## Опції та використання

```bash

usage: main.py [-h] [-c [CURRENCIES ...]] [-d NUM_OF_DAYS]

options:
  -h, --help            show this help message and exit
  -c [CURRENCIES ...], --currencies [CURRENCIES ...]
                        Currency codes
  -d NUM_OF_DAYS, --num_of_days NUM_OF_DAYS
                        Number of days


```

Якщо ввести

```bash
python main.py


```

програма видасть курси для валют `USD` та `EUR` за сьогоднішній день.

## Приклад використання

Вивести курс для чеської крони (`CZK`) за останні `3` дні.

```bash
python main.py -d 3 -c CZK

```

## Залежності

```
[packages]
aiofile = "*"
aiohttp = "*"
prettytable = "*"
```
