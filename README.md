# DOSW_ParcialT1_JuanLopez

**Nombre:** Juan Manuel Lopez Barrera
**Grupo:** 1


## 1. Reaalice el diagrama de contexto con las generalidades de su sistema. (Añadirlo al README.md)

**Diagrama de Contexto:**
![Diagrama-de-contexto.png](docs%2FUML%2FDiagrama-de-contexto.png)

## 2. Identifique 2 patrones de diseño que puedan aplicarse al caso de estudio, especificando por cada uno:
**a.** Nombre del Patrón

**1** Composite

**2** Iterator
   
**b.**Tipo de patrón (creacional, estructural o de comportamiento).

**1** Estructural

**2** De comportamiento
   
**c**. Justificación de la decisión.

**1**  Ya que nos pider registrar una jerarquia de Bootcamp -> Grupos -> Estudiantes ->Evaluaciones 
que es al final del dia algo parecido a un arbol composite seria adecuado

**2**  El sistema no puede asumir la profundidad en la estructura, un patron adecuado para poderlo iterar independientemente
de la profundiad es el patron Iterator
