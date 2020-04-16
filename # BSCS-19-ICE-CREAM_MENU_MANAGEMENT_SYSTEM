from tkinter import*
import tkinter as tk

root=Tk()
root.geometry("600x570+50+50")
root.title("lanie")
root.configure(background = 'snow3')
root.resizable(False,False)

quantity = [0,1,2,3,4,5,6,7,8,9,10]
styles = ["popsicle\t", "cup\t", "cone\t", "1Liter\t", "1Gallon\t"]

#checkbox
var1=IntVar()
var2=IntVar()
var3=IntVar()
var4=IntVar()
var5=IntVar()

#style_optionmenu
var6=StringVar()
var7=StringVar()
var8=StringVar()
var9=StringVar()
var10=StringVar()

#quantity_optionmenu
var11=IntVar()
var12=IntVar()
var13=IntVar()
var14=IntVar()
var15=IntVar()

def TotalCost():
    total_cost = 0
    if var1.get() == 1:
        if var6.get() == styles[0]:
            total_cost += 20 * var11.get()
        elif var6.get() == styles[1]:
            total_cost += 30 * var11.get()
        elif var6.get() == styles[2]:
            total_cost += 35 * var11.get()
        elif var6.get() == styles[3]:
            total_cost += 199 * var11.get()
        elif var6.get() == styles[4]:
            total_cost += 399 * var11.get()

    if var2.get() == 1:
        if var7.get() == styles[0]:
            total_cost += 15 * var12.get()
        elif var7.get() == styles[1]:
            total_cost += 20 * var12.get()
        elif var7.get() == styles[2]:
            total_cost += 25 * var12.get()
        elif var7.get() == styles[3]:
            total_cost += 150 * var12.get()
        elif var7.get() == styles[4]:
            total_cost += 250 * var12.get()

    if var3.get() == 1:
        if var8.get() == styles[0]:
            total_cost += 15 * var13.get()
        elif var8.get() == styles[1]:
            total_cost += 20 * var13.get()
        elif var8.get() == styles[2]:
            total_cost += 25 * var13.get()
        elif var8.get() == styles[3]:
            total_cost += 150 * var13.get()
        elif var8.get() == styles[4]:
            total_cost += 250 * var13.get()

    if var4.get() == 1:
        if var9.get() == styles[0]:
            total_cost += 20 * var14.get()
        elif var9.get() == styles[1]:
            total_cost += 30 * var14.get()
        elif var9.get() == styles[2]:
            total_cost += 35 * var14.get()
        elif var9.get() == styles[3]:
            total_cost += 199 * var14.get()
        elif var9.get() == styles[4]:
            total_cost += 399 * var14.get()

    if var5.get() == 1:
        if var10.get() == styles[0]:
            total_cost += 10 * var15.get()
        elif var10.get() == styles[1]:
            total_cost += 15 * var15.get()
        elif var10.get() == styles[2]:
            total_cost += 20 * var15.get()
        elif var10.get() == styles[3]:
            total_cost += 100 * var15.get()
        elif var10.get() == styles[4]:
            total_cost += 200 * var15.get()

    entryTotal.config(state = NORMAL)
    entryTotal.delete(0, END)
    entryTotal.insert(0, "₱ {0}".format(total_cost))
    entryTotal.config(state = DISABLED)

allframe = Frame(root, bg= 'thistle1', bd=15, pady=5, relief=RIDGE)
allframe.pack(side=TOP, fill =X)

Tops = Frame(allframe, bg= 'thistle1', bd=0, pady=5, relief=RIDGE)
Tops.pack(side=TOP, fill =X)

lblTitle = Label (Tops, font=('Times New Roman', 60, 'bold'),text = "Ice Cream", bd=10, bg= 'thistle1', fg='black', justify=CENTER)
lblTitle.pack (side = TOP)

contentFrame = Frame(allframe, bg = 'thistle2', bd = 3, pady = 5, relief = RIDGE)
contentFrame.pack(side = TOP, fill = BOTH, expand = TRUE)

flavorsFrame = Frame(contentFrame, bg = 'thistle2', bd = 0,pady =5)
flavorsFrame.pack(side = LEFT, fill = BOTH, expand = TRUE)

flavorsLabel = Label(flavorsFrame, text = "Flavors", bg = 'thistle2', fg = 'cyan4',
                     font=('Times New Roman', 20, 'bold'))
flavorsLabel.pack(side= TOP, fill = X)

stylesFrame = Frame(contentFrame, bg = 'thistle2', bd = 0,pady =5)
stylesFrame.pack(side = LEFT, fill = BOTH, expand = TRUE)

stylesLabel = Label(stylesFrame, text = "Styles", bg = 'thistle2', fg = 'cyan4',
                     font=('Times New Roman', 20, 'bold'))
stylesLabel.pack(side= TOP, fill = X)

quantityFrame = Frame(contentFrame, bg = 'thistle2', bd = 0,pady =5)
quantityFrame.pack(side = LEFT, fill = BOTH, expand = TRUE)

quantityLabel = Label(quantityFrame, text = "Quantity", bg = 'thistle2', fg = 'cyan4',
                     font=('Times New Roman', 20, 'bold'))
quantityLabel.pack(side= TOP, fill = X)

#flavor checkboxes gui
Choice1 = Checkbutton(flavorsFrame, text= "Cookies and cream",variable=var1, onvalue = 1, offvalue=0,  font=('Times New Roman', 17, 'bold', 'italic'), fg='black', bg='thistle2',anchor = W, width = 15)
Choice1.pack(side=TOP)

Choice2 = Checkbutton(flavorsFrame, text= "Chocolate",variable=var2, onvalue = 1, offvalue=0,  font=('Times New Roman', 17, 'bold', 'italic'), fg='black', bg='thistle2',anchor = W, width = 15)
Choice2.pack(side=TOP)

Choice3 = Checkbutton(flavorsFrame, text= "Vanilla",variable=var3, onvalue = 1, offvalue=0,  font=('Times New Roman', 17, 'bold', 'italic'), fg='black', bg='thistle2',anchor = W, width = 15)
Choice3.pack(side=TOP)

Choice4 = Checkbutton(flavorsFrame, text= "Cashew nuts",variable=var4, onvalue = 1, offvalue=0,  font=('Times New Roman', 17, 'bold', 'italic'), fg='black', bg='thistle2',anchor = W, width = 15)
Choice4.pack(side=TOP)

Choice5 = Checkbutton(flavorsFrame, text= "Cheese",variable=var5, onvalue = 1, offvalue=0,  font=('Times New Roman', 17, 'bold', 'italic'), fg='black', bg='thistle2',anchor = W, width = 15)
Choice5.pack(side=TOP)

#style optiomenu gui
Choice1_1 = OptionMenu(stylesFrame, var6, *styles)
var6.set(styles[0])
Choice1_1.config(font = ('times new roman',15))
Choice1_1.pack(side = TOP)

Choice2_1 = OptionMenu(stylesFrame, var7, *styles)
var7.set(styles[0])
Choice2_1.config(font = ('times new roman',15))
Choice2_1.pack(side = TOP)

Choice3_1 = OptionMenu(stylesFrame, var8, *styles)
var8.set(styles[0])
Choice3_1.config(font = ('times new roman',15))
Choice3_1.pack(side = TOP)

Choice4_1 = OptionMenu(stylesFrame, var9, *styles)
var9.set(styles[0])
Choice4_1.config(font = ('times new roman',15))
Choice4_1.pack(side = TOP)

Choice5_1 = OptionMenu(stylesFrame, var10, *styles)
var10.set(styles[0])
Choice5_1.config(font = ('times new roman',15))
Choice5_1.pack(side = TOP)

#quantity optionmenu gui
Choice1_2 = OptionMenu(quantityFrame, var11, *quantity)
var11.set(quantity[0])
Choice1_2.config(font = ('times new roman',15))
Choice1_2.pack(side = TOP)

Choice2_2 = OptionMenu(quantityFrame, var12, *quantity)
var12.set(quantity[0])
Choice2_2.config(font = ('times new roman',15))
Choice2_2.pack(side = TOP)

Choice3_2 = OptionMenu(quantityFrame, var13, *quantity)
var13.set(quantity[0])
Choice3_2.config(font = ('times new roman',15))
Choice3_2.pack(side = TOP)

Choice4_2 = OptionMenu(quantityFrame, var14, *quantity)
var14.set(quantity[0])
Choice4_2.config(font = ('times new roman',15))
Choice4_2.pack(side = TOP)

Choice5_2 = OptionMenu(quantityFrame, var15, *quantity)
var15.set(quantity[0])
Choice5_2.config(font = ('times new roman',15))
Choice5_2.pack(side = TOP)

#bottom GUI
bttm = Frame(root, bg='Snow3', bd=0, pady=5, relief=RIDGE)
bttm.pack(side=TOP, fill =BOTH)

total = Frame(bttm, bg='Snow3', bd=5, pady=5, relief=RIDGE)
total.pack(side=TOP, fill =BOTH)

Totalcost = Label(total, text = "Total Cost:", font = ('times new roman', 18), bg="snow3")
Totalcost.pack(side=TOP, fill=BOTH)

entryTotal = Entry(total, width = 30, font = ('times new roman',23,'bold'),state = DISABLED)
entryTotal.pack(side=BOTTOM, fill=BOTH)

button = Frame(bttm, bg='Snow3', bd=0, pady=5, relief=RIDGE)
button.pack(side=BOTTOM, fill =BOTH)

btnTotal = Button (button, padx=120,pady=5, bd=2, fg="black", font=('times new roman',20,"bold"), width=5, text="Total", bg='green2', command = TotalCost)
btnTotal.pack(side=LEFT, fill=BOTH)

btnExit = Button (button, padx=120,pady=5, bd=2, fg="black", font=('times new roman',20,"bold"), width=5, text="Exit", bg='indianred2', command=root.destroy)
btnExit.pack(side=RIGHT,fill=BOTH)
