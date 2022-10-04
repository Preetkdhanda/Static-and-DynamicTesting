### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1: # this should be == 
      return True
    else   #missing ":"
      return False
   

# Indentation error, this would not account for aces being the higest value card
  dif highest_card(self, card1 card2): #dif instead of def** missing "," between the varibles
  if card1.value > card2.value:
    return card # missing the full reference for the card that it wants to return
  else:  #2 equal cards would return that card 2 is higher than card 1
    return card2
  

#Indentation error
def cards_total(self, cards):
  total  #variable was declared but it didnt have a total set
  for card in cards:
    total += card.value
    return "You have a total of" + total #this should be indented
  
```
