# Learning-Functions
```python
def turn_right():
    turn_left()
    turn_left()
    turn_left()
    
def jump():
    move()
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_left()

    
while front_is_clear() or wall_in_front():
    if front_is_clear():
        move()
    else:
        # Navigate around the wall
        turn_left()
        move()
        turn_right()
        move()
        turn_right()
        move()
