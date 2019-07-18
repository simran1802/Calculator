from tkinter import *
def click(event):
    global scvalue
    text = event.widget.cget("text")
    print(text)

    if text == 'C':
        scvalue.set("")
        screen.update()
    elif text == '=':
        if scvalue.get().isdigit():
            value = int(scvalue.get())

        else:
            value = eval(screen.get())

        scvalue.set(value)
        screen.update()

    else:
        scvalue.set(scvalue.get() + text)
        screen.update()
    # print("Working!!")
    # pass
root = Tk()
root.geometry("400x600")
root.maxsize(400,600)
root.title("Calculator by simran")
scvalue = StringVar()
scvalue.set("")

screen = Entry(root,textvar=scvalue,font="lucida 30 bold")
screen.pack(fill=X,padx=10,pady=10)

f = Frame(root,bg='grey')

b = Button(f,text='9',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=1)
b.bind('<Button-1>',click)

b = Button(f,text='8',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=1)
b.bind('<Button-1>',click)

b = Button(f,text='7',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=1)
b.bind('<Button-1>',click)
f.pack()
f = Frame(root,bg='grey')
b = Button(f,text='6',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='5',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='4',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)
f.pack()

f = Frame(root,bg='grey')
b = Button(f,text='3',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='2',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='1',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)
f.pack()

f = Frame(root,bg='grey')
b = Button(f,text='0',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='C',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='=',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)
f.pack()

f = Frame(root,bg='grey')
b = Button(f,text='+',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='-',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='*',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)
f.pack()

# b = Button(f,text='/',font="lucida 28 bold")
# b.pack(side=LEFT,padx=3,pady=4)
# b.bind('<Button-1>',click)
# f.pack()

f = Frame(root,bg='grey')
b = Button(f,text='/',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

b = Button(f,text='.',font="lucida 28 bold")
b.pack(side=LEFT,padx=3,pady=4)
b.bind('<Button-1>',click)

# b = Button(f,text='%',font="lucida 28 bold")
# b.pack(side=LEFT,padx=3,pady=4)
# b.bind('<Button-1>',click)
f.pack()
# b = Button(f,text='OFF',font="lucida 28 bold")
# b.pack(side=LEFT,padx=3,pady=4)
# b.bind('<Button-1>',click)
# f.pack()




root.mainloop()
