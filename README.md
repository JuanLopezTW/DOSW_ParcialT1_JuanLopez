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

# 3. Identifique 5 requerimientos del sistema y clasifíquelos en funcionales (3) y no funcionales (2). Garantice que al menos un requerimiento funcional seleccionado utilice uno o los dos patrones identificados. (Añadirlo al README.md)

# Requesisitos

# Funcionales 

**1** La aplicacion debe calcular los promedios ponderados de manera automatica: por grupo, estudiante, por modulo y general del bootcamp


**2** La aplicacion debe generar una lista con los estudiantes en riesgo (aquellos que su nota ponderada sea menor a 3)


**3** La aplicacion debera generar un reporte con los promedios ponderados

# No Funcionales

**4** Que sea responsive

**5** Tipografia Poppins

## 4 Del listado anterior, seleccione los 2 requerimientos funcionales más importantes del sistema y desarrolle un diagrama de casos de uso con surespectiva historia de usuario. Garantiza que al menos un requerimiento funcional seleccionado utilice un patrón identificado. (Añadirlo al README.md)

## Diagrama de caso de uso/historia 

![Diagrama-Casos-de-Uso.png](docs%2FUML%2FDiagrama-Casos-de-Uso.png)

**Historia 1**

**Como* Administrador

**Quiero** Consultar la lista de promedios

**Para Poder** Medir el desempeño del curso general

**Historia 2**

Como Administrador

Quiero Consultar la lista de estudiantes en riesgo 

Para Poder Contactarme con ellos para saber la situacion en la que se encuentran
