# turtle-graphics
from turtle import*
import colorsys
speed(0)
bgcolor('black')
hue=0.0


for i in range(200):
    c=colorsys.hsv_to_rgb(hue,1,1)
    color(c)
    hue=+0.0049
    circle(-i+2,80)
    goto(0,0)
    rt(134)
    lt(50)
    fd(60)


done()
