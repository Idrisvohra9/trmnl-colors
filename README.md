
# trmnl_colors v-4.0.7
## Add colors to the static WOrLd!


colors module is made to colorize the output of terminal when the code runs on command line, With that there are functions for adding basic text colors (Total 10 including invsisble) and or text formats such as Bold, Italics, Underline, Light or Strikethrough to your code.

But wait there is more! use background colors, filled Variants which can be accessed by calling thier specific name and 'bg' postfix as in background. Here is an example describing with  use case:

## Latest Updates:

### Introducing constants to make your life more easier:

>### Use case for constants

```python
from trmnl_colors.constants import *

print(RedB + "Hello" + GreenB + " World!", end="")

print(RESET,end="")

```
>### Use case for functions

```python
from trmnl_colors.functions import *
bluebg()
print("Hello")
reset()
```

* Each color can be accessed by calling thier particular name and the first letter of the format at the postfix.
```python
from trmnl_colors.functions import *
yellowB()
print("Hello") # After every color call remember to call the reset function.
# Outputs Hello in yellow color in Bold text
reset()
```
* For example:Call clr.redB() for red color with text format Bold, S for strikethrough D for Default U for Underline I for Italics L is for special lighter color substitute for each color.


* There are also filled color variants in which the font color and the background color match each other making them viable for specific type of color operations. 

* There is a special function called reset() which is basically the default white so that the color function gets reset it is recommended to use this function after every usage of a color to mantain the color of the terminal.
* 
* PS if you want to create blocks of colors for decoration purposes use filled variants e.g. clr.whitefilled() 

## Terminal Application Screenshots with trmnl_colors:
### Create Terminal programs such as the below examples. Only your imagination and python skills are a limit!

![Screenshots](https://github.com/Idrisvohra9/trmnl-colors/blob/main/static/Screenshot%202023-08-24%20171908.png?raw=true)
![Screenshots](https://github.com/Idrisvohra9/trmnl-colors/blob/main/static/Screenshot%202023-08-24%20172610.png?raw=true)
> Explore & stay Creative
>## by: Idris-Vohra
