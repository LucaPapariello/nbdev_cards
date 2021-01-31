# Deck of cards
> A minimal example of using nbdev to create a python library.


## Install

After cloning this repository:

`pip install -e .`

## How to use

Playing cards in python!

```python
from nbdev_cards.card import Card

c = Card(suit=1, rank=3)
print(f'You picked the card: {c}')
```

    You picked the card: 3 of Diamonds


```python
from nbdev_cards.deck import Deck

d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
```

    Number of playing cards in the deck: 52

