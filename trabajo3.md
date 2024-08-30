# Problemas de Algoritmos (trabajo #3)
## Joan David García Sánchez
### Problema #4

```
 Inicio
    Definir lista_velocidades
    Definir lista_tiempos

    Leer lista_velocidades
    Leer lista_tiempos

    Definir distancia_total como 0

    Para 1 desde 0 hasta longitud(lista_velocidades) - 1 hacer
        velocidad_actual = lista_velocidades
        tiempo_actual = lista_tiempos
        
        Multiplicar velocidad_actiual por tiempo_actual para obtener distancia
        
        sumar distancia_total a distancia e igualar a distancia_total

    Imprimir distancia_total
 Fin
```
### Problema #1

``` 
Inicio
    Definir n1=0
    Definir K=30

 Leer n
  Definir n=5

  Mientras 5>0
    Leer C
    m=m+c
 Fin mientras

  p=m/n

 Si p mayor o igual a 3
  Imprimir "fue aprobado"

 Si p no es mayor o igual a 3
  Imprimir "reprobado"

Fin
```

### problema #6

```
Inicio
leer dia_naci, mes_naci, año_naci, mes_actu, año_actu, dia_actu

// Primero se calculan los años:
  años = año_actu - año_naci
// ahora se mira si ya se han cumplido esos años, es decir, si el mes_naci y día_naci ya han pasado:
     Si (mes_actu<mes_naci) o
        (mes_actu == mes_naci Y dia_actu < dia_naci) Entonces
        años == años - 1
        imprimir "No has cumplido años."
//luego se calculan los meses:
Si (mes_actu >= mes_naci) entoces
    meses = mes_actu - mes_naci
FinSi

//Calcular días
si (dia_actu > dia_naci) entonces
  dias = dia_actual - dia_naci
Finsi

si (dia_actu = dia_naci) Y (mes_actu = mes_naci) Y (año_actu = año_actual) entonces
  imprimir "Feliz cumple"
sino
 imprimir "hoy no cumples"
Fin si



     
Fin
```
