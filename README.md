# Shopping List Manager

This assignment practices Python lists, loops, conditionals, `.append()`, `.remove()`, membership checks, and list comparisons.

## Files

- `list_warmup.py` — Practices creating, adding to, removing from, and counting items in a list.
- `shopping_list.py` — A menu-based shopping list manager that allows users to add, remove, show, and finish.
- `list_report.py` — Prints a numbered shopping list, counts items with more than four letters, and finds the longest item.
- `screenshots/` — Contains screenshots showing each Python program running.

## Why check `in` before using `.remove()`?

It is safer to check whether an item is in the list before calling `.remove()` because `.remove()` causes an error if the item does not exist. Using `in` first prevents the program from crashing and allows us to show a helpful message to the user instead.
