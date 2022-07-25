#  Introducción a la programación y Javascript

Objetivo de la semana🏁

Aprende los conceptos básicos de programación y empieza a conocer Javascript

## Subtemas de la semana

+ ¿Cómo es la programación?

+ ¿Qué es realmente la programación?

+ ¿Qué es un programa?

+ ¿Cómo una computadora ejecuta un programa?

+ Operaciones algorítmicas

1. Secuencial

2. Condicional

3. Iterativo

+ Elementos básicos de la programación.

a. Conjunto de instrucciones

b. Variables

c. Producción

+ ¿Qué es javascript?

+ ¿Qué es un lenguaje interpretado?

+ Conceptos básicos de HTML

+ javascript hola mundo

+ Variables en Javascript

+ Estructura HTML básica  
## Desafíos de la semana (martes)💻
![image](https://user-images.githubusercontent.com/103481905/180600854-c143f7e9-0bf5-4b53-8623-9579ca1f8560.png)  
**1.Interpreted And Compiled Programming Languages**   
Compilers and interpreters perform different functions, although some compilers perform both functions. The compilers are responsible for executing the code in a more private way and it is much faster, unlike its counterpart that is more flexible to work with because it does not necessarily need to have access to the form of the code but only executes it.  
**2.¿Java está compilado o interpretado, o ambos?**    
Java can be both compiled and interpreted. Because the last step just where the virtual machine (JVM) comes into play at that moment becomes an interpreted language and in this way it is concluded that it is functional in both parts.  
**3.Ejercicio de conversión de moneda de pseudocódigo**    
**Conversor de divisas de dolares a bitcoin**
```

algorithm  
we define the variables  
dollarValue as integer  
valueBitcoin as real  
x(will contain the result) as real  

read data valueDolar, valueBitcoin  

x=dollarvalue*Bitcoinvalue;  

we write the result x 

```
**4.lenguajes de alto nivel**  
## Miercoles  
**1. ¿Tu fecha de nacimiento en la matriz?**
```

Algoritmo fechanacimiento
entero fechanacimiento
cadena caracter
real resultado
fechanacimiento=trunc(fechanacimiento)
Mientras fechanacimiento>0
resultado=fechanacimiento % 2=0
si resultado entonces
binario="0" + binario
Sino
binario="1"+binario
Finsi
fechanacimiento=trunc(fechanacimiento/2)
Fin mientras

imprimir binario  
```
**2. Ejercicio MIPS**  
- Create a program that adds any two given numbers provided by the user  
``` 
.data
     num1: .asciiz "\nIngrese el primer valor: "
     num2: .asciiz "\nIngrese el segundo valor: "

.text 
    main:  
     li $v0, 4
              la $a0, num1
              syscall

     li $v0, 5
     syscall

              move $t0, $v0
     li $v0, 4
              la $a0, num2
              syscall

     li $v0, 5
     syscall
     move $t1, $v0

     li $v0, 1
     move $a0, $t0
     syscall
 
```



- Create a program that displays your name
```   
.data 
   Nombre: .asciiz "\nIngrese su nombre: "
   
   .text 
        main:
             li $v0, 4
             la  $a0, Nombre
             syscall 
             li $v0, 5
     syscall
     move $t0, $v0
     
```


 

