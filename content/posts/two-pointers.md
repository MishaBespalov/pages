---
id: 1738774856-twopointers
aliases:
  - Two Pointers
tags:
  - Algorithms/two_pointers
---

# Two Pointers

`Задача реверснуть строку.`

|     | ->  |     |     |     |     |
| --- | --- | --- | --- | --- | --- |
| a   | b   | c   | d   | e   | f   |
|     |     |     |     | <-  |     |

- Решение
  Логика простая, ставим указатель в начало и в конец.
  Свапаем местами значения с указателей, потом сдвигаем указатели друг к другу до тех пор пока они не встретятся.

`Чекнуть палиндром`

|     | ->  |     |     |     |     |
| --- | --- | --- | --- | --- | --- |
| a   | b,  | c   | c   | b   | a.  |
|     |     |     |     | <-  |     |

- Решение
  Логика простая, ставим указатель в начало и в конец.
  Сверяем значение в указателях, если равны, то сдвигаем указатели друг к другу.
  Если не равны то не палиндром.
  При этом делаем чем, что символ находтися в a-z границах, иначе скипаем такой символ

