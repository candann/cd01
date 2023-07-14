1 import turtle as t

2

3 t.penup()

4 t.seth(-90)

5 t.fd(160)

6 t.pendown()

7 t.pensize(20)

8 t.colormode(255)

9 for j in range(10):

10 t.speed(1000)

11 t.pencolor(25*j,5*j,15*j)

12 t.seth(130)

13 t.fd(220)

14 for i in range(23):

15 t.circle(-80,10)

16 t.seth(100)

17 for i in range(23):

18 t.circle(-80,10)

19 t.fd(220)

20 t.done()
