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
    if card.value = 1:
      return True
    else
      return False

# Line 21 the "=" is incorrect as a single = is to assign a variable, this has to be changed to "==" to compare card.1 to the int 1.
# Line 23 the else statement has no ":" after it.
   

  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  
# Line 30 "dif" is the incorrect word to define a function, this has to be changed to "def" which defines a function.
# Line 30 there is no comma between card1 and card2 in the arguments which will cause an error due to the function requiring 2 arguements, by adding a comma between card1 & card2 it separates the 2 arguements.
# Line 30 the if statement is not indented so will not be used inside the highest_card function.
# Line 32 "card" has to be changed to "card1" as it will not relate card to the arguement of card1.


def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total

# Line 42 Function is not indented so will not be used inside the class, the whole function needs indented.
# Line 43 "total" has to be made into a variable and a value assigned to it by adding " = 0", currently the for loop will not see the word total as a variable.
# Line 46 will currently not print correctly due to the string interpolation being incorrect, this has to be changed to f"You have a total of {total}".
# Line 46 the return is indented incorrectly, move it to the same indentation level as the for loop.


  
```
