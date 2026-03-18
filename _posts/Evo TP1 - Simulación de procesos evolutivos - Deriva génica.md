# Objetivos
- Simular la evolución por deriva génica a lo largo del tiempo en diferentes poblaciones
- Analizar si los patrones de evolución por deriva génica dependen de factores tales como el tamaño poblacional, el tiempo, la frecuencia alélica inicial y la identidad del locus analizado.

# Resultados
---
3a. Debería darles a AA, Aa y aa el mismo fitness.

---
5a. Para cada réplica cambia lo ocurrido. En algunos casos, es el alelo $A_1$ el que sobrevive, mientras que en otros casos es seleccionado el alelo $A_2$. En cada situación, el tiempo que se tarda en llegar a un único alelo subsistente es diferente.
![[Pasted image 20250908221537.png]]

---
6a. La cantidad de casos en los que se alcanza un estado monoalélico pareciera disminuir al aumentar el tamaño poblacional.
![[Pasted image 20250908222007.png]]

---
7a. Al aumentar la cantidad de generaciones, vemos que el polimorfismo aún desaparece dado el suficiente tiempo.
![[Pasted image 20250908222509.png]]

---
7b. Creo que especificar la semilla permite la replicabilidad de las corridas.

---
8a. Se ve que al disminuir el tamaño poblacional, disminuye el tiempo necesario para perder el polimorfismo.
![[Pasted image 20250908222924.png]]

---
9a. En todos los resultados puede verse que tener una frecuencia alélica inicial para $A_1$ tan baja disminuye las chances de que sea el alelo elegido. Sin embargo, aumentar el tamaño poblacional lo hace posible.
![[Pasted image 20250908223838.png]] (población de 10 individuos)
![[Pasted image 20250908223902.png]] (población de 50 individuos)
![[Pasted image 20250908223921.png]] (población de 200 individuos)

# Preguntas integradoras
1. A medida que aumentó el tamaño poblacional, aumentó la cantidad de generaciones que podía subsistir el polimorfismo original. Bajar mucho la frecuencia de uno de los alelos hizo que sea más frecuente su temprana pérdida.
2. La variabilidad dentro de las poblaciones disminuyó al disminuir su cantidad de individuos, pues se volvió más probable que se vuelvan monoalélicas. A similar frecuencia inicial de los alelos, la variabilidad entre poblaciones aumentó al disminuir la cantidad de individuos, pues más rápidamente adquirieron estados monoalélicos frecuentemente divergentes.
3. Se fijará un alelo proporcionalmente a su frecuencia inicial.
4. No son adaptativos pues no se dan por un proceso de selección. Sí hubo evolución, pues se modificaron las frecuencias alélicas de la población.