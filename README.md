# CLI Menu

A simple, reusable menu for CLI python3 scripts.

Displays a numbered menu to console and returns a corresponding function or list item/object based on user number selection using a passed *expanded list/tuple.  

Import it and pass it an *expanded list of tuples/lists. It will return list index[1] for your selection by default.  

If you need a different list item, pass the optional *listreturn=* argument with an integer representing the list index needed.

## Basic use Example

```py
import menu

options = (('Option 1', 'Return 1'), ('Option 2', 'Return 2'))

sel = menu.display(*options)
```

```py
# Example with list index 2
sel = menu.display(*options, listreturn=2)
```
