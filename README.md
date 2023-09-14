from tkinter import *
from tkinter import mesagerbox
import radom

def no():
    messagebox.showinfo(' ', 'Thanks bro')
    quit()

def motionMouse(event):
    btnYes.place(x=random.radint(0, 500), y=radom.randint(0, 500))
root = Tk()
root.geometry('600x600')
root.title('survey')
root.resizable(width=false, height=false
root['bg'] = 'white

label = Label(root, text='Are you gay?', font='Arial 20 bold', bg='white').pack()
btnYes = Button(root, text='No', font='Arial 20 bold')
btnYes.place(x=170, y=100)
btnYes.bind('<Enter>', motionMouse)
btnNO = Button(root, text='Yes', font='Arial 20 bold', comand=no).place(x=350, y=100)

root.mainloop()
