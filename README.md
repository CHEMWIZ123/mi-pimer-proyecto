#1
print("hola mundo")



#2
my_name = "hola mundo"
print (my_name)



#3
my_name = input ("Cual es mi nombre")
print ("usando input", my_name)



#4
print (3+2/2*5)*2



#5
horas = input ("¿Cuanto horas trabajas?")
print ("usando input", horas)

Salario = input ("¿Cuanto valen las horas?")
print ("usando input", Salario)

my_paga = "$30.000"
print (my_paga )



#6
h = input("escribe un número entero")
n = input("escrribe otro número entero")
a = int(h) /int(n)
print("el resultado del cociente es",a)
i = int(h)-int(n)
print("el resultado de la resta es",i)


#7
Peso = float(input ("¿Cuanto pesas kg?")) 
Estatura = float (input ("¿Cuanto mides m?"))

mc= Peso/Estatura
print (" tu masa corporal es", mc)




#8
peso_engranes = 112
peso_cilindros = 75

numero_engrades = float(input("cuantos engranes se vendieron?"))
numero_cilindros = float(input("cuantos cilindros se vendieron?"))

pesototal = (numero_engrades*peso_engranes)+(numero_cilindros*peso_cilindros)
print("el peso total del paquete es, (pesototal) gramos")



#9
panes = 3.49
pdiaanterior = panes- 0.6
barras_vendidas = float(input ("cuántas barras vendiste que no son del día?"))

print ("el precio habitual de una barra de pan es", panes)
print ("el descuento por no ser fresca es del 60%")
print ("el precio final de una barra de pan del dia anterior es", pdiaanterior)
print ("el precio final de todas las barras de pan del dia anterior vendidas es", pdiaanterior * barras_vendidas)



#10
edad = int(input("Cual es tu edad?"))

 if edad>= 18:
    print("eres mayor de edad")

else {
    print("No eres mayor de edad")
    
}



#11
contraseña_guardada = "ContraseñaSegura"
contraseña_introducida = input("escriba la contraseña: ")

coincide (ignorando mayúsculas y minúsculas)
if contraseña_guardada.lower() == contraseña_introducida.lower():
    print("La contraseña es correcta.")
else:
    print("La contraseña es incorrecta.")



#12
numerador =int(input("introduzca el numerador"))
divisor= int(input("introduzca el numerador"))

if divisor == 0:
    print("error: no se puede dividir por 0")

else:
resultado = numerador/divisor
print("el resultado de la division es:(resultado)")



#13
numero = int(input("escribe un numero entero:"))

if numero/2 ==0:
    print("el numeor (numero)es par")

else:
    print ("el numeor (numero)es impar")



#14
palabra = input("escriba una palabra")

for _ in range(10):
    print(palabra)



#15
numero = int(input("escriba un numero entero positivo"))

if numero <= 0:
    print("el numero ingresado no es validO. Debe ser positivo")
else:
impares =[]

for i in range (1,numero + 1,2):
    impares.append(str(i))

print (",".join(impares))
