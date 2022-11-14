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
