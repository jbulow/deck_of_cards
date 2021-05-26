# Deck of Cards
> Small nbdev experiment.


This file will become your README and also the index of your documentation.

## Install

`pip install your_project_name`

## How to use

`Card` is a class the represents a single card in a deck of cards. For examle:

```python
Card(suit=2, rank=11)
```




    Jack of Hearts



```python
c = Card(suit=1, rank=3)
```

```python
assert str(c) == "3 of Diamonds"
```

```python
c2 = Card(suit=2, rank=11)
```

```python
assert str(c2) == "Jack of Hearts"
```

```python
assert c2 > c
```
