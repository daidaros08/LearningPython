#Escribe un programa que use INPUT para pedirle al usuario su nombre y luego darle labienvenida

nombre= input('ingrese su nombre: ')
print (f'Bienvenido {nombre}!!!')


#Escribe un prorama para pedirle alusuario el numero de horas y la tarifa por horas para calcular el salario bruto

tarifaHora= int(input('Ingrese su tarifa por hora: '))
horaTrabajo= int(input('Ingrese las horas a trabajar: '))
salario = tarifaHora * horaTrabajo
print(f'Su salario bruto por {horaTrabajo} horas es {salario} pesos')

#Escribe un programa que le pida al usuario una temperatura en grados Celcius, la convierta a grados Fahrenheit e imprima por pantalla la temperatura convertida

cel= float(input('Ingese los grados Celsius: '))
fahr= 1.8 * cel + 32
print (cel, "grados Celsius equivalen a ", fahr, "grados Fahrenheit")


#Reescribe el programa del calculo del salario para darle al empleado 1.5 veces la tarifa horaria para todas las  horas trabajadas que excedan de 40.

horaTrabajo2 = int(input('Ingrese las horas a trabajar: '))
tarifaHora2 = int(input('Ingrese  su tarifa por hora: '))
tarifaExtra = tarifaHora2 * 1.5
if horaTrabajo2 >40:
	horaComun= 40*tarifaHora2
	horaExtra = (horaTrabajo2 - 40) * tarifaExtra
	sueldoFinal= horaComun + horaExtra
	print (f'Su salario con horas extras es de {sueldoFinal} pesos')
else:
	salarioFinal= horaTrabajo2*tarifaHora2
	print ('Su salario sin horas extras es de', salarioFinal, 'pesos')

#Reescribe el  programa del salario usando TRY y EXCEPT,  de modod que el programa sea capaz de gestionar entradas no numericas con elegancia, mostrando un mensaje y saliendo del programa.

try:
	horaTrabajo3 = int(input('Ingrese las horas a trabajar: '))
	tarifaHora3 = int(input('Ingrese  su tarifa por hora: '))
	tarifaExtra2 = tarifaHora3 * 1.5

	horaTrabajo3 = int(input('Ingrese las horas a trabajar: '))
	tarifaHora3 = int(input('Ingrese  su tarifa por hora: '))
	tarifaExtra2 = tarifaHora3 * 1.5
	if horaTrabajo3 >40:
		horaComun2= 40*tarifaHora3
		horaExtra2 = (horaTrabajo3 - 40) * tarifaExtra2
		sueldoFinal2= horaComun2 + horaExtra2
		print (f'Su salario con horas extras es de {sueldoFinal2} pesos')
	else:
		salarioFinal2= horaTrabajo3*tarifaHora3
		print ('Su salario sin horas extras es de', salarioFinal2, 'pesos')
except:
	print ('Introduzca un valor numerico por favor')

	
	#Escribe un programa que solicite una puntuacion entre 0.0 y 1.0. Si la puntuacion esta fuera de ese rango, muestra un mensaje de error. Si la puntuacion esta entre 0.0 y 1.0, muestra la calificacion siguiente => si es <0.6 
try:
	nota= float(input('Introduzca puntuacion entre 0.0 y 1.0: '))
	if nota >=1.0 or nota <= 0.0:
		print ('Ingese un valor valido' )
	elif nota < 0.6:
		print('Insuficiente')
	elif nota >=0.6:
		print ('Suficiente')
	elif nota >= 0.7:
		print ('Bien')
	elif nota >=0.8:
		print('Notable')
	elif nota >=0.9:
		print ('Sobresaliente'  )

except:
	print ('Error, por favor ingrese valores validos')

#Reescribe el programa del calculo del salario, con tarifa para horas extras, y crea una funcion llamada CALCULO_SALARIO que reciba dos parametros: horas y tarifa

hs = int(input('Ingrese las horas a trabajar: '))
tarifas = int(input('Ingrese  su tarifa por hora: '))
def calculo_salario (horas, tarifa):
	tarifaExtra = tarifa * 1.5
	try:
			if horas >40:
				horaComun2= 40*tarifa
				horaExtra2 = (horas - 40) * tarifaExtra
				sueldo_final= horaComun2 + horaExtra2
				print (f'Su salario con horas extras es de {sueldo_final} pesos')
			else:
				salario_final= horas*tarifa
				print ('Su salario sin horas extras es de', salario_final, 'pesos')
	except:
		print ('Introduzca un valor numerico por favor')
		calculo_salario(hs, tarifa)
		
calculo_salario(hs, tarifas)

#Reescribe el programa de calificaciones usando una funcion llamada CALCULA_CALIFICACION que reciba una puntuacion como parametro  y devuelva una calificacion como cadena

def calcula_calificacion (nota):
	try:
		if nota >=1.0 or nota <= 0.0:
			print ('Ingese un valor valido' )
		elif nota < 0.6:
			print('Insuficiente')
		elif nota >=0.6:
			print ('Suficiente')
		elif nota >= 0.7:
			print ('Bien')
		elif nota >=0.8:
			print('Notable')
		elif nota >=0.9:
			print ('Sobresaliente'  )

	except:
		print ('Error, por favor ingrese valores validos')
		calcula_calificacion (nota)

	

		nota= float(input('Introduzca puntuacion entre 0.0 y 1.0: '))
		calcula_calificacion ()
		
		
		
		
#Escribe un programa que lea repetidamente numeros hasta que el usuario introduzca 'fin'. Una vez introducido 'fin' muestra por pantalla el total, la cantidad de numeros y el promedio de esos numeros. Si el usuario introduce cualquier otra cosa que no sea un numero, detecta su fallo con try y except, muestra un mensaje de error y pasa al numero siguiente
intr = 0
suma= 0
cantidad =0
promedio = 0
while intr <=10:	
	try:
		numUser=  input('Ingrese un numero: ')
		cantidad+=1
		suma+= int(numUser)
		print (int(numUser))
		if numUser =='fin' or numUser == 'Fin':
			print (f'El total de numeros ingresados es: {cantidad}')
			print (f'La suma de todos los numeros da: {suma}')
			print (f'El promedio de los numeros ingresados es: {promedio}')
			break
	except:
		print('Dato erroneo')
print ('finalizado') 	
	


#Escribe otro programa que pida una lista de numeros como la anterior y al final muestre por pantalla el maximo y el minimo de los numeros

bucl= True
numeros = []

while bucl ==True:	
	try:
		numUser2=  input('Ingrese un numero: ')
		if numUser2 =='fin' or numUser2 == 'Fin' or numUser2=='FIN':
			print (f'Los numeros ingresados son: {numeros}')
			print (f'El mayor valor ingresado es: {max(numeros)}')
			print (f'El menor valor ingresado es: {min(numeros)}')
			break
		elif numUser2 != 'fin' or numUser2 != 'Fin' or numUser2 != 'FIN':
			numeros.append (int(numUser2))
			print (numUser2)		
	except:
		print('Dato erroneo')
print ('finalizado')



#Toma el siguiente codigo en Py que almacena una cadena:
	#str= 'X-DSPAM-Confidence:0.8475'
#Utiliza FIND y una parte de la cadena para extraer la porcion de la cadena despues del dos puntos (:) y luego utiliza la funcion FLOAT para convertir la cadena extraida en un numero de punto flotante


#Las variables fueron llamadas como personajes de Community
str= 'X-DSPAM-Confidence:0.8475'  
abed= str.find('0.8475') #Devuelve la posicion inicial del fragmento
annie= str[abed: ] #selecciono desde el inicio del fragmento al final
troy=float(annie) #lo transformo en un float
print(troy)

