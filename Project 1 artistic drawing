

import turtle

screen = turtle.Screen()
screen.setup(800, 600)
screen.title("A Peaceful Landscape")
screen.bgcolor("skyblue")

t = turtle.Turtle()
t.speed(0)



def rectangle(x, y, width, height, colour):
    t.penup()
    t.goto(x, y)
    t.color(colour)
    t.pendown()
    t.begin_fill()

    for i in range(2):
        t.forward(width)
        t.left(90)
        t.forward(height)
        t.left(90)

    t.end_fill()
    t.penup()



def circle(x, y, size, colour):
    t.penup()
    t.goto(x, y - size)
    t.color(colour)
    t.pendown()
    t.begin_fill()
    t.circle(size)
    t.end_fill()
    t.penup()



def triangle(x1, y1, x2, y2, x3, y3, colour):
    t.penup()
    t.goto(x1, y1)
    t.color(colour)
    t.pendown()
    t.begin_fill()
    t.goto(x2, y2)
    t.goto(x3, y3)
    t.goto(x1, y1)
    t.end_fill()
    t.penup()



def tree(x, y):
    rectangle(x, y, 18, 55, "brown")
    circle(x + 9, y + 70, 28, "green")
    circle(x - 10, y + 60, 20, "green")
    circle(x + 28, y + 60, 20, "green")


circle(260, 190, 45, "yellow")


triangle(-400, -80, -220, 170, -40, -80, "gray")
triangle(-150, -80, 50, 130, 250, -80, "dimgray")
triangle(100, -80, 280, 160, 460, -80, "gray")


rectangle(-400, -250, 800, 170, "lightgreen")


triangle(-100, -250, 30, -250, 150, -80, "deepskyblue")


tree(-300, -125)
tree(280, -125)



for x in [-180, -130, 190, 230]:
    circle(x, -190, 6, "red")
    rectangle(x, -215, 3, 20, "green")


t.goto(0, -285)
t.color("black")
t.write("A Peaceful Landscape",
        align="center",
        font=("Arial", 18, "bold"))

t.hideturtle()

turtle.done()
