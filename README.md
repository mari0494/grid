# grid
from tkinter import *
def button1Click() :
 Display.config(text="Р­С‚Рѕ СЂР°РґСѓРµС‚!")
def button2Click() :
 Display.config(text="Р­С‚Рѕ РѕРіРѕСЂС‡Р°РµС‚!")
Window = Tk()
Display = Label(Window, text="РџСЂРёРІРµС‚, РєР°Рє РґРµР»Р°?")
Display.grid(row=0, column=1)
Button1 = Button(Window, text="РҐРѕСЂРѕС€Рѕ", command=button1Click)
Button2 = Button(Window, text="Norm", command=button2Click)
Button1.grid(row=2, column=0, padx=10, pady=10)
Button2.grid(row=2, column=2, padx=10, pady=10)
Window.mainloop()
