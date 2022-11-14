## nametuple
a class without method 
```python
Card = collections.namedtuple('Card', ['rank', 'suit']) 
>>> beer_card = Card('7', 'diamonds')
>>> beer_card
Card(rank='7', suit='diamonds')
```
## list comprehension with 2 seprated for loop
```python
_cards = [Card(rank, suit) for suit in self.suits for rank in self.ranks]
```
## can i use random on obj of class?
``` python
>>> deck = FrenchDeck()
>>> >>> from random import choice
>>> choice(deck)
Card(rank='3', suit='hearts')
```
#### C include a struct2 called PyVarObject, which has an ob_size field holding
the number of items in the collection.
``` python
```
