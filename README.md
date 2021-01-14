# simple-console-menu
A simple, reusable menu for CLI python3 scripts.

Displays a numbered menu to console and returns a corresponding function or object based on user number selection using a passed *expanded list/tuple.  
Import it and pass it an *expanded list of tuples/lists. It will return list[1] for your selection.

```py
# import the function
from menuloop import display_menu

# tuple of tuples ('Display', function)
options = (('option 1', function1), ('option 2', function2))

# display the menu and get the return
function_to_call = display_menu(*options)

# call the returned function
function_to_call()
```
