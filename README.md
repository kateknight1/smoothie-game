# smoothie-game

I am trying to make a simple game about smoothies, similar to the Papa's franchise but simpler, without specific characters, and without emphasis on correct technique.

In the game, you are given an order - a list of ingredients to include in the smoothie. You add them to the blender. You press the button to blend them. You serve the smoothie. 

That's the aim.

## Roadmap

1. Create game loop - DONE!
2. Add in characters to speak orders (using open-source assets).
3. When you click the "blend" button on the blender:
    The list of clicked ingredients resets to empty
    The current list of ingredients gets attached to a new list that the Cx will use to check against their order
    A timer begins on the blender itself (say, 3 seconds).
    Once the timer is complete, a liquid mixture appears in the blender
    When you click anywhere in the blender jug, a smoothie asset is created and the blender is emptied
4. Add art of ingredients that appear in blender when buttons are pressed
5. Make the assets insidde the blender have a random position or fill the blender further up
6. Find a way to make the colour of the smoothie liquid related to the ingredients
7. Make the smoothies appear in the bar/service area with some way to see which is which
8. Give smoothie to customer, customer rates smoothie & leaves. This affects some kind of score system.
9. Score system? Average customer satisfaction - wait time, accuracy.
10. Money system:
    Ingredients cost money to click into the blender
    Ingredients have price for customers
    Customers pay money when ordering
    Customers can tip
12. Kitchen bin - be able to cancel smoothie/empty blender, and reset ingredients list


## Current state of game
Right now, we can load buttons into the kitchen area, which you can click on. If you click on a button, you add that ingredient to a list of ingredients which will be the contents of the smoothie.

## Credits

Icon image
# <a href="https://www.flaticon.com/free-icons/smoothie" title="smoothie icons">Smoothie icons created by Flat Icons - Flaticon</a>

Fonts
LT Stopwatch - https://fontesk.com/lt-stopwatch-font/

