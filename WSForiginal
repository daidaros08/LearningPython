#Diseñar un programa en el cual el usuario ingrese tres números, uno a la vez, y se muestre a la salida el promedio de los tres números.
num_1 = int(input("ingrese el primer número"))
num_2 = int(input("ingrese el segundo número"))
num_3 = int(input("ingrese el tercer número"))
_suma = int(num_1+num_2+num_3)
_promedio = int(_suma/3)
print(_promedio)

#Realizar un programa al cual se ingresa el día del año mediante un número de 0 a 364, y que muestra en pantalla a qué día de la semana corresponde mediante un número de 0 a 6 (mostrar el número 0 si corresponde a Lunes y 6 si es Domingo)
# Suponemos que el día 0 del año cae un Lunes:
# Ejemplos:
# Input: 2
# Output => 2 (Ya que el día 2 cae Miércoles, y Miércoles es 2 en la semana)
# Input: 10
# Output => 3 (Ya que el día 10 cae Jueves, y Jueves es 3 en la semana)
# Input: 7
# Output => 0 (Ya que el día 7 cae Lunes, y Lunes es 0 en la semana)
# Input: 25
# Output => 4 (Ya que el día 25 cae Viernes, y Viernes es 4 en la semana)

dia_del_anio = int(input ("día del año: "))
dia= int(dia_del_anio % 7)
print(dia)

#Realizar un programa que revise si una nota está aprobada (es decir si es mayor o igual a 4) utilizando un if/else. La nota será ingresada por el usuario usando input().

 
nota= int(input("ingrese nota: "))
if(nota>=4):
    print("aprobado")
else:
    print("desaprobado")
nota

# Realizar un programa que convierta una nota porcentual del 0 al 100 a una letra entre A y F de acuerdo a la siguiente conversión:
# A: 90–100
# B: 80–89
# C: 70–79
# D: 60–69
# F: 0–59
_nota_a_letra= int(input("ingrese numero: "))
if _nota_a_letra >=90:
  print ("A")
elif _nota_a_letra >=80 :
  print ("B")
elif _nota_a_letra >=70:
  print("C")
elif _nota_a_letra >=60:
  print ("D")
else:
  print("F")

# #Implementar un programa que muestre la siguiente secuencia: 1, 2, 3, 4, 5, 4, 3, 2, 1, 0
# #Para un desafío mayor: Utilizar un solo while, un solo if y un solo else



##Entra en bucle infinito, no logre dar con el problema aun
# x= 1
# y=4
# while x>0 and y<=5:
#     if x <= 5:
#         print(x)
#         x+=1
#     elif y<5 and y>=0:
#         print(y)
#         y=y-1

#Mostrar la siguiente secuencia de datos utilizando la instrucción for y la instrucción if: 0, 1, 4, 9, 16, 25, 6, 7, 8, 9
x = 0
y = 1
for z in range(0,10):
  if z <=5:
    print(x)
    x += y
    y += 2
  else:
    print(z)

#Escribir una función que chequee los siguientes usuarios y contraseñas:
#Usuario: Juan - Contraseña: 12345_
#Usuario: Pablo - Contraseña: xDcFvGbHn
#La función debe recibir como parámetros el usuario y la contraseña, y debe devolver el valor True o False.
def chequear_usuario(usuario, contraseña):
    if usuario == "Juan" and contraseña == "12345_" or usuario == "Pablo" and contraseña == "xDcFvGbHn":
        return print(True)
    else:
        return print(False)
chequear_usuario(input("ingrese usuario: "), input("ingrese contraseña: "))

#Conjetura de Lothar
# Escriba un programa que reciba un numero del usuario y repita el siguiente proceso usando un while: Si el numero es par, se debe dividir por  2 . Si el numero es impar, se debe multiplicar por  3  y sumar  1 .
# Este proceso se repite hasta llegar al numero  1  y luego muestra en pantalla la cantidad de pasos que tardó en llegar.
# Ejemplos:
# Input: 6
# Output: 8 (Los pasos a seguir son: 6, 3, 10, 5, 16, 8, 4, 2, 1)
# Input: 13
# Output: 9 (Los pasos a seguir son: 13, 40, 20, 10, 5, 16, 8, 4, 2, 1)
def conjetura_Lothar(numero):
    pasos = 0
    while numero > 1:
        if numero % 2 == 0:
            numero= numero / 2
            pasos= pasos + 1
        else:
           numero = numero * 3 + 1
           pasos = pasos + 1
    else:
        print (pasos)
conjetura_Lothar(int(input("número: ")))

#Cálcular la nota de un alumno es una tarea cotidiana de un profesor. Esta tarea suele realizarse a mano o en excel muchas veces. En esta ocasión la haremos en python.
#Escribir una función que calcule el promedio de 3 notas y entrege ese valor usando return.

nota_uno = int(input("ingrese primer nota: "))
nota_dos = int(input("ingrese segunda nota: "))
nota_tres = int(input("ingrese tercer nota: "))

def promedio_tres_notas(nota_uno, nota_dos, nota_tres):
    return print((nota_uno + nota_dos + nota_tres) / 3)

#Reescribir la función anterior modificandola para asignar una importancia al primer examen de 20%, al segundo de 50% y al tercero de 30%.
#Llamar a cada función anterior 3 veces con distintas notas y verificar, mediante la instrucción if, si el alumno aprobó en cada caso (suponga que 4 es la nota de aprobación).

def promedio_con_importancia (nota_uno, nota_dos,nota_tres):
    nota_uno = nota_uno * 0.2
    nota_dos = nota_dos * 0.5
    nota_tres = nota_tres * 0.3
    return print ((nota_uno + nota_dos + nota_tres)/(0.2+0.3+0.5))

def aprobado (nota_uno,nota_dos,nota_tres):
  if promedio_con_importancia (nota_uno, nota_dos, nota_tres) >= 4.00:
    print (True)
  else:
    print (False)
aprobado (nota_uno, nota_dos, nota_tres)
