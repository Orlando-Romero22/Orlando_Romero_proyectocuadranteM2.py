# Orlando_Romero_proyectocuadranteM2.py
Cuadrante

import os

x = int (input ('Ingresa el valor de x: '))
y = int (input ('Ingresa el valor de y: '))
if x==0 and y==0:
    print ('Origen')
if x==0:
    print ('Eje Y')
if y==0:
    print ('Eje X')
if x>0 and y>0:
    print ('Cuadrante I')
if x<0 and y>0:
    print ('Cuadrante II')
if x<0 and y<0:
    print ('Cuadrante III')
if x>0 and y<0:
    print ('Cuadrante VI')
print ()
os.system ('pause')
