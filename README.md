# SNAKE GAME
To play the game just download the file Snake Game.ipynb and run it :)

![images](https://user-images.githubusercontent.com/115581351/198727414-05fdd8c1-3366-4796-8000-88cdad3330cd.jpg)

# Trello schedule

![image](https://user-images.githubusercontent.com/115581351/198736021-811a6dfc-6c62-4801-97b0-4b6ecef3f8c0.png)


# For Music
To hear the provided music download the file .ogg and erase '#' on lines 10,11,12.

# General function of the game
Snake is a game where a snake moves through a plane in 2D and eats food to grow. Once it consumes a unit of food it grows a unit. 
When the snake collides with itself the game is over and restarts.

# Function declaration
initial(): Defines initial values

snake_direction(): Defines snake movement and generation.

eat_food(): Snake eats food, based on small distance returned by distance food + small offset.

random_food_pos(): get food position as a point inside the board. Value between half of
the board width and height-food size.

distance_food(pos1, pos2): Function to determine distance between food and snake head, needs 2 arguments.

up(), right(), down(), left(): Functions for input movement 

# Libraries used
turtle graphics https://docs.python.org/3/library/turtle.html 

random https://www.w3schools.com/python/module_random.asp 

pygame https://www.pygame.org/docs/

# Further implementation
Add assets to snake, board and food.
Add scoreboard.
Add decreasing delay to make the snake go faster.


