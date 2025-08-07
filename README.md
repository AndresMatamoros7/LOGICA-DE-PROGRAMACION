# LOGICA-DE-PROGRAMACION
import random
opciones=['piedra','papel','tijera']
magia=random.randint(0,2)
computadora=opciones[magia]
print("eleccion de la computador", computadora)
juagdor=input("opcion: ")
print("tu selecion fue: ", jugador)

if (jugador == computadora):
    print("empate")
    
if (jugador == 'tijeras'):
    if (computadora == 'papel'):
       print("ganaste")
    if (computadora == 'piedra'):
       print("perdiste")
            
if (jugador == 'papel'):
    if (computadora == 'piedra'):
       print("ganaste")
    if (computadora == 'tijera'):
       print("perdiste")  
            
if (jugador == 'piedra'):
    if (computadora == 'tijera'):
       print("ganaste")
    if (computadora == 'papel'):
       print("perdiste")   
