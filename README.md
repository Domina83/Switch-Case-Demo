# Food Menu Selector (Switch Case)
This C program allows the user to select an item from a food menu using a number (1–5), and it displays the selected dish with its price using a `switch-case` structure.

## Language
C

## Description
- Displays a food menu to the user
- Takes the user's choice as input
- Uses a `switch` statement to show the corresponding item and its price
- Handles invalid input with a default message

### Menu
KFC with Mayonnaise and Sauce – Rs. 350

Nuggets and Mojito – Rs. 150

Pasta with Sauce – Rs. 299

Sandwich with Mayonnaise – Rs. 199

Triple Deck Cheese Pizza – Rs. 450

3
You ordered Pasta with sauce. It costs RS: 299

## How to Run
```bash
gcc food_menu.c -o menu
./menu

What I Learned

How to create a menu using printf

Taking user input with scanf

Using switch-case to handle multiple choices

Adding break statements to avoid fall-through
