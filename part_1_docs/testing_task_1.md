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
    if card.value = 1:    # = assigns a value. To compare the value we should be using ==
      return True
    else              #colon is missing
      return False
   

  dif highest_card(self, card1 card2): #dif should be def and there is a comma missing between card1 and card2
  if card1.value > card2.value:     #This line and the 3 below it should all be indented
    return card #card should be card1. card has not been defined.
  else:
    return card2
  


def cards_total(self, cards):   # This entire method is sitting outside the class. It needs to be indented.
  total                 #total needs to be assigned a value, total = 0 for instance
  for card in cards:
    total += card.value
    return "You have a total of" + total    #return should be outside the for loop. This would only add
                                            #the first card before returning the  value. Also total needs
                                            #to be converted to a string.
  
```
