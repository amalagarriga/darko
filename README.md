# darko
import turtle
rainbow = ["red", "orange", "yellow", "green", "blue"]

toni = turtle.Turtle()
toni.speed(0)
toni.penup()
toni.forward(50)
toni.pendown()
for side in [1, 2, 3, 4, 5, 6, 7, 8, 9, 0]:
    
    for side in rainbow:
        toni.color(side)
        toni.forward(100)
        toni.right(144)
    toni.left(36)
toni.hideturtle()
