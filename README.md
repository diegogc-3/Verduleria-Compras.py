# Pedirle al usuario los kg de las papas y cebollas
papas=int(input("ingrese los kg de papas: "))
cebollas=int(input("ingrese los kg de cebollas: "))

#Calculamos el subtotal de las papas
if papas>20:
    subtotal_papas=papas*1500
elif papas>10:
    subtotal_papas=papas*1800
else :
    subtotal_papas=papas*2000
#Calculamos el subtotal de las cebollas
if cebollas>20:
    subtotal_cebollas=cebollas*750
elif cebollas>10:
    subtotal_cebollas=cebollas*800
else:
    subtotal_cebollas=cebollas*1000

#Calculamos el importe total
total=subtotal_cebollas+subtotal_papas

#Mostramos el resultado
print("subtotal de papas: ", subtotal_papas)
print("subtotal de cebollas: ", subtotal_cebollas)
print("total de las compras", total)
