# Python-hacks
Documentación ColabTurtlePlus
https://larryriddle.agnesscott.org/ColabTurtlePlus/documentation2.html

#from ColabTurtlePlus.Turtle import *
clearscreen()
setup(300,300)
showborder()
color("red", "yellow")
shape("turtle")
pensize(2)
speed(7)
begin_fill()

for _ in range(4):
  forward(100)
  left(90)

circle(-50)

end_fill()
color("black","green")
saveSVG(turtle=True)
