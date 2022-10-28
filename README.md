# Mini-project
Snake Game
Image.open(urlopen((https://assets.petco.com/petco/image/upload/f_auto,q_auto/21-443495_BallPython_WhiteBG_1080x720)))
# General function of the game¶
Snake is a game where a snake moves through a plane in 2D and eats food to grow. Once it consumes a unit of food it grows a unit. When the snake collides with itself the game is over and restarts.

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
random 
pygame

