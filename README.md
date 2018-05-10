# Hello-To-the-World-
SDEV 140
#import
#main function
from tkinter import *
def main():

# the main conversion
def call_convert(rlabel1, rlabe12, inputn):
    tem = inputn.get()
    if tempVal == 'Celsius':
        f = float((float(tem) * 9 / 5) + 32)
        rlabel1.config(text="%f Fahrenheit" % f)
    if tempVal == 'Fahrenheit':
        c = float((float(tem) - 32) * 5 / 9)
        rlabel1.config(text="%f Celsius" % c)
    return

    root=Tk()
    root.title("GUI")
    root.geometry("400x700")
    
#enter Celsius
    L1=Label(root,text="Enter a Celsius temperature.")
    E1=Entry(root,textvariable=numberinput)
    button=Button(root, text="Total", command=convert(string))

    button.pack()
    E1.pack()
    L1.pack()
    root.mainloop()#main loop


#convert Celcius to Fahrenheit
def convert(string):
    if string !="":
    cel=int(string)
    far=(9/5*(cel))+32
    print(far)
