# Tuplas
Manejo de Tuplas

#Crear Tupla 
thistuple = ("J", "K", "L")
print(thistuple)


#Tupla con miembros duplicados 
thistuple = ("J", "K", "L", "M", "N")
print(thistuple)


#Contanto miembros de la tupla
thistuple = ("J", "K", "L")
print(len(thistuple))


#Notese la diferencia de cuando SI es Tupla y cuando NO lo es, revisa lo que muestra este pequeño código 
thistuple = ("J",)
print(type(thistuple))


#NOT a tuple
thistuple = ("J")
print(type(thistuple))


#Asignando tuplas a variables 
#tuple1 = ("J", "K", "L")tuple2 = (1, 5, 7, 9, 3)
tuple3 = (True, False, False)


#Combinando tipos de datos en mis tuplas
tuple1 = ("abc", 34, True, 40, "male")
print(tuple1)



#Tipo de datos de una tupla
mytuple = ("ONE", "TWO", "THREE")
print(type(mytuple))


#Utilizando el método tuple para hacer una 
thistuple = tuple(("ONE", "TWO", "THREE"))
print(thistuple)
