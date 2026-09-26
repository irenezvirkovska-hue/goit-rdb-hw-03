# Homework 3 — UCI Adult / Census Income

## Dataset

Для домашнього завдання використано датасет **UCI Adult / Census Income**.

Офіційне джерело:
https://archive.ics.uci.edu/dataset/2/adult

## Data preparation

Датасет завантажено з UCI Machine Learning Repository за допомогою бібліотеки `ucimlrepo`:

```python
from ucimlrepo import fetch_ucirepo

adult = fetch_ucirepo(id=2)
