# Zhangxianhang
# coding:utf-8
import turtle as t
t.pensize(4) # 设置画笔的大小
t.colormode(255) # 设置GBK颜色范围为0-255
t.color((255,155,192),"pink") # 设置画笔颜色和填充颜色(pink)
t.setup(840,500) # 设置主窗口的大小为840*500
t.speed(10) # 设置画笔速度为10
#鼻子
t.pu() # 提笔
t.goto(-100,100) # 画笔前往坐标(-100,100)
t.pd() # 下笔
t.seth(-30) # 笔的角度为-30°
t.begin_fill() # 外形填充的开始标志
a=0.4
for i in range(120):
  if 0<=i<30 or 60<=i<90:
      a=a+0.08
      t.lt(3) #向左转3度
      t.fd(a) #向前走a的步长
  else:
      a=a-0.08
      t.lt(3)
      t.fd(a)
t.end_fill() # 依据轮廓填充
t.pu() # 提笔
t.seth(90) # 笔的角度为90度
t.fd(25) # 向前移动25
t.seth(0) # 转换画笔的角度为0
t.fd(10)
t.pd()
t.pencolor(255,155,192) # 设置画笔颜色
t.seth(10)
t.begin_fill()
t.circle(5) # 画一个半径为5的圆
t.color(160,82,45) # 设置画笔和填充颜色
t.end_fill()
t.pu()
t.seth(0)
t.fd(20)
t.pd()
t.pencolor(255,155,192)
t.seth(10)
t.begin_fill()
t.circle(5)
t.color(160,82,45)
t.end_fill()
#头
t.color((255,155,192),"pink")
t.pu()
t.seth(90)
t.fd(41)
t.seth(0)
t.fd(0)
t.pd()
t.begin_fill()
t.seth(180)
t.circle(300,-30) # 顺时针画一个半径为300,圆心角为30°的园
t.circle(100,-60)
t.circle(80,-100)
t.circle(150,-20)
t.circle(60,-95)
t.seth(161)
t.circle(-300,15)
t.pu()
t.goto(-100,100)
t.pd()
t.seth(-30)
a=0.4
for i in range(60):
  if 0<=i<30 or 60<=i<90:
      a=a+0.08
      t.lt(3) #向左转3度
      t.fd(a) #向前走a的步长
  else:
      a=a-0.08
      t.lt(3)
      t.fd(a)
t.end_fill()
#耳朵
t.color((255,155,192),"pink")
t.pu()
t.seth(90)
t.fd(-7)
t.seth(0)
t.fd(70)
t.pd()
t.begin_fill()
t.seth(100)
t.circle(-50,50)
t.circle(-10,120)
t.circle(-50,54)
t.end_fill()
t.pu()
t.seth(90)
t.fd(-12)
t.seth(0)
t.fd(30)
t.pd()
t.begin_fill()
t.seth(100)
t.circle(-50,50)
t.circle(-10,120)
t.circle(-50,56)
t.end_fill()
#眼睛
t.color((255,155,192),"white")
t.pu()
t.seth(90)
t.fd(-20)
t.seth(0)
t.fd(-95)
t.pd()
t.begin_fill()
t.circle(15)
t.end_fill()
t.color("black")
t.pu()
t.seth(90)
t.fd(12)
t.seth(0)
t.fd(-3)
t.pd()
t.begin_fill()
t.circle(3)
t.end_fill()
t.color((255,155,192),"white")
t.pu()
t.seth(90)
t.fd(-25)
t.seth(0)
t.fd(40)
t.pd()
t.begin_fill()
t.circle(15)
t.end_fill()
t.color("black")
t.pu()
t.seth(90)
t
