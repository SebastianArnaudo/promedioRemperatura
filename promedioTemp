import tkinter as tk
from tkinter import Frame
from tkinter import messagebox


def main():

    ventana = tk.Tk()
    ventana.title("Calculo de temperatura")
    ventana.geometry("450x400")



    def calcularPromedio():
        
        maxima = entradaMax.get()
        minima = entradaMin.get()

        maxima = float(maxima)
        minima = float(minima)

        mid = (maxima + minima) / 2

        MensjPro["text"] = "La temperatura media del dia es:"
        muestraPromedio["text"] = mid


    framePrincipal=Frame(ventana,bg="blue")
    framePrincipal.pack(expand=True,fill="both")
    
    etiquetaMax = tk.Label(framePrincipal,text = "Ingrese la temperatura maxima del dia", font="arial", fg="white",bg="blue")
    etiquetaMax.place(x=100, y=50)

    entradaMax = tk.Entry(framePrincipal)
    entradaMax.place(x=160,y=100)
    
    etiquetaMin = tk.Label(framePrincipal,text = "Ingrese la temperatura minima del dia", font="arial", fg="white",bg="blue")
    etiquetaMin.place(x=100, y=150)
    
    entradaMin = tk.Entry(framePrincipal)
    entradaMin.place(x=160, y=200)

    botonCalcular = tk.Button(framePrincipal,text = "Calcular promedio", command = calcularPromedio, fg="white",bg="green")
    botonCalcular.place(x=165, y=250)

    MensjPro = tk.Label(framePrincipal,text = "",font="arial", fg="white",bg="blue")
    MensjPro.place(x=110, y=300)

    muestraPromedio = tk.Label(framePrincipal,text = "", font="arial", fg="white",bg="blue")
    muestraPromedio.place(x=200, y=350)

    tk.mainloop()



if __name__ == "__main__":
    main()
 