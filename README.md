# python-turtle-animation-code
from turtle import* import colorsys tracer(10) bgcolor("black") pensize(3) h=0.4 up() goto(0,10) down() for i in range (260):     c=colorsys.hsv_to_rgb(h,1,1)     color(c)     h+=0.002     up()     forward(i*2)     down()     circle(i,-20)     circle(i,-100)     color(c)     pensize(7)     fd(7)     rt(1)     lt(19) done()
