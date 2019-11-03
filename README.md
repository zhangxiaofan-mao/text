# text
from tkinter import *
# def callbackW(*arges):
#     xL.set(xE.get())
#
# def callbackR(*args):
#     print('Warnning:数据正在被读取')
#
# def hit():
#     print('读取数据:', xE.get())
#
# root = Tk()
# root.title('同步显示')
# xE = StringVar()
# entry = Entry(root,textvariable=xE)
# entry.pack(padx=10,pady=5)
# xE.trace('w',callbackW)
# xE.trace('r',callbackR)
# xL = StringVar()
# label = Label(root,textvariable=xL)
# xL.set('同步显示')
# label.pack(padx=5,pady=10)
# btn = Button(root,text='读取',command=hit)
# btn.pack(pady=5)
# btn1.pack(side=LEFT)
# btn2.pack(side=LEFT)
#
# counter = 0
# def run_counter(digit):
#     def counting():
#         global counter
#         counter += 1
#         digit.config(text=str(counter))
#         digit.after(1000,counting)
#     counting()
#
# root1 =Tk()
# root.title('计数器')
# digit = Label(root1,bg='yellow',fg='blue',height=3,width=10,
#                font='Helvetic 20 bold')
#
# command=run_counter(digit)
# run_counter = Button(root1,text='结束计数',command=root1.destroy)
# btn3 = Button(root1,text='开始计数')
# run_counter.pack(side=RIGHT,pady=10)
# digit.pack()
# btn3.pack(side=RIGHT)

# def printInfo():
#     print('Account: %s\nPassword: %s' % (accountE.get(),pwdE.get()))
# root3 = Tk()
# root3.title('登录界面')
# msg = '欢迎使用测试系统'
# ssgFng = PhotoImage(file='C:/Users/Administrator/Desktop/测试用图片/截图.jpg')
# logo =Label(root3,image=ssgFng,text=msg,compound=BOTTOM)
# accoundL = Label(root3,text='Account')
# accoundL.grid(row=1)
# pwdL = Label(root3,text='Password')
# pwdL.grid(row=2)
#
# logo.grid(row=0,column=0,columnspan=2,pady=10,padx=10)
# accountE = Entry(root3)
# accountE.insert(0,'mirror')
# pwdE = Entry(root3,show='*')
# accountE.grid(row=1,column=1)
# pwdE.grid(row=2,column=1,pady=10)
# # 下面建立Login和Quit按钮
# loginbth = Button(root3,text='Login',command=printInfo)
# loginbth.grid(row=3,column=0)
# quitbtn = Button(root3,text='Quit',command=root3.quit)
# quitbtn.grid(row=3,column=1)

# 点击显示或不显示
# def btn_hit():
#     global msg_on
#     if msg_on == False:
#         msg_on =  True
#         x.set('I like tkinter')
#     else:
#         msg_on = False
#         x.set('')
#
# root = Tk()
# root.title('测试语言')
# msg_on = False
# x = StringVar()
# label = Label(root,textvariable=x,fg='blue',bg='lightyellow',
#               font='Verdana 16 bold',width=25,height=2)
# label.pack()
#
# btn = Button(root,text='click me',command=btn_hit)
# btn.pack()
#
root1= Tk()
root1.title('测试')
framupper = Frame(root1,bg='lightyellow')
framupper.pack(fill=X,pady=3)
img1 = PhotoImage(file='C:/Users/Administrator/Desktop/测试用图片/1382_已标注.png')
label1 = Label(framupper,text='img1')
label1.pack()
root1.mainloop()


