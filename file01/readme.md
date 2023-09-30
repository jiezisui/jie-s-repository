# 个人信息

##个人信息

-姓名：武彤
-学校：北京印刷学院
-学院：新媒体学院
-班级：数字媒体技术1班
-联系方式：15301336156



##希望能够在414学习到的
-将专业学学习中学到的知识，落实到实践中
-
#-*-coding:UTF-8 -*-
import turtle as t




t.colormode(255)
t.speed(0)
t.screensize(850,760,"white")
t.setup(width=850,height=760,startx=260,starty=0)
t.title("草莓熊"）
t.resizemode('noresize')
t.tracer(1)



scolor=["#E6005C,"#00BFFF","#538a30","#F28500"]
qcolor=["#FF007F","#87CEFA","#7fbc2b","#FFA500"]
blsize=80
bs=2**0.5/2*blsize

zjb=blsize/2
zjsjxxb=2**0.5 *zjb
length=1.7*blsize
width=2/15*blsize

def fongche():
    t.penup()
    t.goto(-205,-42)
    t.begiin_fill()
    t.pensize(4)
    t.pencolor("#321320")
    t.fillcolor("#D2B48C")
    t.circle(15)
    t.end_fill()
    t.penup()
    t.goto(-220,80)
    t.pendown()
    t.setheading(-90)
    t.pensize(width)
    t.pencolor("#5f4a1d")
    t.forward(length)
    t.pensize(2)
    t.backward(length)
    t.setheading(90)

    for i in range(4)

        t.color(scolor[i])
        t.begin_fill()
        t.forward(zjb)
        t.left(90)
        t.forward(zjb)
        t.left(135)
        t.forward(zjsjxxb)
        t.end_fill()




        t.color(qcolor[i])
        t.begin_fill()
        t.backward(zjsjxxb)
        t.right(90)
        t.forward(bs)
        t.left(135)
        t.forward(blsize)
        t.end_fill()




        t.right(180)
        t.penup()

mling_
    
