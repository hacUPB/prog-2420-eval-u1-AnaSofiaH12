# **Algoritmos**
## Problema 1: Determinar el promedio de calificaciones de un estudiante y si ha aprobado o no

Ana quiere saber si ha aprobado sus exámenes finales. Tiene una lista de sus calificaciones y necesita calcular el promedio. Para aprobar, debe tener un promedio de al menos 3.0.

```
Inicio
    Deefinir M=0
    Definir K=30

    leer N 
    Definir S=N 

        Mientras S> 0
            leer C
            M = M+C
            S = S-1
        Fin mientras
    P = M/N

    si P ≥ 3.0
        Imprimir "Aprobo"

    sino 
        Imprimir "Reprobo"
Fin
```
Numero de calificaciones: N

Calificaciones: C

Sumatoria de calificaciones : M

Promedio : P



## Problema 4: Determinar la distancia total recorrida por un vehículo con registros de velocidad y tiempo

María tiene un registro de las velocidades a las que ha conducido su vehículo y el tiempo que ha mantenido cada velocidad. Quiere calcular la distancia total recorrida.
```
Inicio
    Definir ls_Vel
    Definir ls_tiem

    Leer ls_vel
    Leer ls_tiem

    Definir distancia_total = 0

    Para 1 desde 0 hasta longitud(ls_vel) - 1
        hacer vel_actual = ls_vel
        tiem_actual = ls_tiem
        
        Multiplicar vel_actiual por tiem_actual para obtener distancia
        
        sumar distancia_total a distancia e igualar a distancia_total

    Imprimir distancia_total
Fin
```

##  Problema 6: Calcular la edad de una persona a partir de su fecha de nacimiento y la fecha actual

**Descripción del Problema:**
Se desea saber cuántos años, meses y días tiene actualmente una persona, basándose en su fecha de nacimiento. Además, le gustaría saber si ya ha cumplido años este año o aún no, y si hoy es su cumpleaños para celebrarlo. Cada una de las fechas está conformada por 3 variables: día, mes y año.
```
Inicio
leer dia_naci, mes_naci, año_naci, mes_actual, año_actual, dia_actual

// Primero se calculan los años:
  años = año_actual - año_naci
// ahora se mira si ya se han cumplido esos años, es decir, si el mes_naci y día_naci ya han pasado:
     Si (mes_actual <mes_naci) o
        (mes_actual == mes_naci Y dia_actu < dia_naci) Entonces
        años == años - 1
        imprimir "No has cumplido años."

lUego se calculan los meses:
Si (mes_actual >= mes_naci) entoces
    meses = mes_actual - mes_naci
Fin Si

//Calcular días
si (dia_actual > dia_naci) entonces
  dias = dia_actual - dia_naci
Finsi

si (dia_actu = dia_naci) Y (mes_actu = mes_naci) Y (año_actu = año_actual) entonces
  imprimir "Feliz cumple"
sino
 imprimir "hoy no cumples"
Fin si

  
Fin
```

.