## Day 1 — Task 1: Create and display a shopping list

### What you will learn

You will practise storing several items in a **list**, displaying them, and asking Python to count them.

A list keeps related values together under one name. For example, instead of creating a separate variable for every shopping item, you can keep all your items in one list called `shopping_list`.

### Your task

Write a small Python program that stores these three shopping items: **rice, milk, and apples**.

When you run your program, it should display:

```text
My shopping list:
['rice', 'milk', 'apples']
Number of items: 3
```

**Python must calculate the number of items. Do not simply write a print statement containing the number `3`.**

You do not need a menu, user input, or separate functions for this task.

### Directions

**Step 1 — Create your Python file.**

Use the Python editor you already use. Create a new file and save it as:

```text
shopping_list.py
```

Write your code in this file.

**Step 2 — Put your shopping items into a list.**

Create a variable named `shopping_list` and store rice, milk, and apples inside it.

To write a list, use square brackets: `[ ]`. Separate the items with commas. Because these items are text, put quotation marks around each item.

Here is an example using different information:

```python
colours = ["red", "blue"]
```

Use that pattern to create your shopping list. **Keep the three shopping items together in one list**, rather than using three separate variables.

**Step 3 — Display a heading and your list.**

Use `print()` to display the heading:

```text
My shopping list:
```

On the next line of your code, use another `print()` to display the contents of your `shopping_list` variable.

Remember the difference:

```python
print("colours")  # Displays the word colours.
print(colours)    # Displays the values stored in the variable.
```

Run your program now. Check that you can see the heading and all three shopping items before continuing.

**Step 4 — Count the items.**

Use `len()` to find out how many items are in your list.

For example:

```python
len(colours)
```

This gives the number of items in the `colours` list. Apply the same idea to your shopping list.

Display the result with the label `Number of items:`. You can print a label and a calculated value together using this pattern:

```python
print("Your label:", your_calculated_value)
```

The words `your_calculated_value` above are a placeholder—replace them with the calculation your program needs.

**Step 5 — Run the complete program.**

Compare your output with the example at the beginning. Check that the heading, shopping items, and item count all appear.

### Test that your program really works

Do these checks **by editing the original list in your code** and running the program again.

| Check                               | What you should see                                       |
| ----------------------------------- | --------------------------------------------------------- |
| Start with rice, milk, and apples.  | All three items appear, and the count is `3`.             |
| Add bread as a fourth item.         | Bread appears, and the count automatically becomes `4`.   |
| Remove milk from that updated list. | Milk disappears, and the count automatically becomes `3`. |

**Do not change the counting line during these checks.** It should work regardless of how many items are in the list.

After testing, restore the original three items and save your file.

### When you get stuck

Check that your quotation marks, square brackets, and parentheses are paired correctly. Also check that you have spelled `shopping_list` the same way wherever you use it.

When asking for help, show your code and any error message. Explain what you expected to happen and what happened instead. Ask for a hint before asking for the complete solution.

### What to show at the review

Show your saved `shopping_list.py` file and run it. Then explain, in your own words:

1. What information does `shopping_list` hold?
2. What does `len()` do in your program?
3. Why does the count change when you add bread, even though you did not edit the counting line?

**The task is complete when the program passes the checks and you can explain what each line does. Looking up syntax is allowed—you do not need to memorise everything.**
