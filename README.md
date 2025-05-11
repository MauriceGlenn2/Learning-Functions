# Reeborg's World 

The challenge is to walk to the goal, avoiding the walls.

<img width="320" alt="image" src="https://github.com/user-attachments/assets/96bd01c7-6cea-466a-afa0-861fcab60cc7" />

```python
def turn_right():
    turn_left()
    turn_left()
    turn_left()
    
def jump():
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_left()

    
while not at_goal():
    if wall_in_front():
        jump()
    else:
        move()
