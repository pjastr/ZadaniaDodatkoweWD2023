Zadania dodatkowe - Wizualizacja danych - Tydzień 3
================

## WEEK3 TASK1

Popraw poniższy kod tak, aby zwracał poprawnie sumę cyfr:

``` python
def get_sum_of_digits(num):
    sum = None
    digits = list(num)
    for x in digits:
        sum + x
    return sum
    
```

Uwzględnij następujące przypadki:

    123  => 6
    223  => 7
    1337 => 14

Źródło:
<https://www.codewars.com/kata/563d59dd8e47a5ed220000ba/train/python>