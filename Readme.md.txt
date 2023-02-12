-Luego cree un archivo que se llame README.md el cual incluya la descripción de la solución de su tarea de la Unidad 2.

El ejercicio de las estaciones es un poco complicado cuando eres principiante en el tema de programacion, la soluciones que encontre fue invertigas un poquito a fondo todo los temas
que tenian relacion.

Primero Ingrese el var = prompt ("Ingrese numero del mes") esto me sirvio para que me saliero el enunciado donde pude ingresar algun numero para que me saliera la estacion que
correspondia al mes, pero para que eso sucediera tuve que ingresar comando los cuales hicieran esa funcion.

Comenzamos con el enunciado al poner el enunciado poner else aler (valor invalido) para que cuando pongamos un numero que no sea 1 al 12 salga valor invalido.

Ponemos if este se utiliza para ingresar un mensaje especifico el cual quiero que salga en el enunciado, luego de eso coloco lo que son signos de mayor y menor,
eso da a entender que quiero que el numero 1 sea mayor,el otro menor que 12, luego comenzamos a poner los comandos que son numerodemes y ponemos los numeros,
12,1 y 2, a esos numeros le ponemos una alert con la palabra invierno, para cuando uno coloque el numero 12,1 o 2 entre esos numeros debemos poner espacions
para que no salgan juntos en este caso utilizamos los signos (= ||) para que den espacios, por ultimo ponemos un alert para que  salga la palabra invierno, y asi sucesivamente.

Luego ponemos el siguiente parrafo siempre comenzando con el if colocando numero de mes, aqui ya colocamos los numeros 3,4 y 5 con el alert primavera, 
para cuando coloque los numeros correspondientes saliera la palabra primavera,
 cada que pongamos if al finalizar colocamos el corchete { eso nos ayuda aque agarre el alert y se pueda ejecutar la palabra que tenemos.

Despues seguimos con el ultimo parrafo colocando numero de mes y los numeros que correspondan a ese mes en este caso 9,10 y 11, igual ponemos el alert (otoño) para que cuando coloquemos esos numeros
salga la palabra otoño.

No se olviden de colocarle las comillas en las palabras dentro del alert, ya que si no las colocan tira error, ya que las palabras siempre van encerradas en comillas para que se puedan ejercutar.
Ya por ultimo nos pide colocar el nombre y el numero de carnet, para eso podemos la palabra let esto sirve para colocar nombres a los resultados que querramos, en este caso nombre y numero de carner.
Eso lo encerramos en un alert (nombre y numero de carnet) si se dan cuenta hay comillas y el signo de mas, esto sirve para que de espacios en el enunciado, quedaria asi.

var numerodemes = prompt('Ingrese numero de un mes')
if (numerodemes >= 1 && numerodemes <= 12){
    if(numerodemes == 12 || numerodemes == 1 || numerodemes ==2){
        alert('invierno')
    }

    if(numerodemes == 3 || numerodemes == 4 || numerodemes == 5){
        alert('Primavera')
    }

    if(numerodemes == 6 || numerodemes == 7 || numerodemes == 8){
        alert('verano')
    }

    if(numerodemes == 9 || numerodemes == 10 || numerodemes == 11){
        alert('otoño')
    }
}else{
    alert('valor invalido')
    
}
        
let nombre = 'Brandon Aldahir Dardon Ramos'
let numerodecarnet = 'carnet 23003586'

alert(nombre +' '+ numerodecarnet


Y asi quedaria ya finalizado.


