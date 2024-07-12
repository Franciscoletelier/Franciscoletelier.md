**¿Qué es la teoría central del límite?**
* La teoría central del límite es un teorema que establece que la distribución de la media de una muestra se aproxima a una distribución normal a medida que el tamaño de la muestra aumenta.

Entonce:
* Sea $𝑋1$, ... , $𝑋𝑛$ una ***m.a.s.*** de una ***v.a.*** $𝑋$ cualquiera de esperanza $𝜇𝑋$ y desviación típica $𝜎𝑋$. Cuando n tiene a infinito.

$$\lim_{{n \to \infty}} \frac{1}{\sqrt{2\pi n}} e^{-\frac{x^2}{2n}}$$

1. Las observaciones en la muestra deben ser independientes entre sí.
2. Las observaciones deben provenir de la misma distribución poblacional.
3. La distribución poblacional debe tener una media finita y una varianza finita (o desviación estándar finita).
4. El tamaño de la muestra debe ser lo suficientemente grande. Aunque no hay un número específico, generalmente se considera que un tamaño de muestra mayor o igual a 30 es suficiente para que el teorema central del límite sea aplicable.

## Prueba $Chi$^2^

* Es una de las pruebas más conocidas y utilizadas para analizar variables nominales o cualitativas. Es decir, para determinar la existencia o no de independencia entre 2 variables.
* Al igual que la t Student, se trabaja con grados de libertad. Mientras más grados de libertad, la curva tiene a parecerse a una normal
* En las pruebas de independencia, se utiliza el formato de tabla de contingencia, que clasifica los datos de acuerdo a dos o más categorías, relacionados con cada una de las variables cualitativas, que pueden ser o no estadísticamente independientes

**Modelo Matemático**


$$ {x^n (df)} =  \sum_{i=0}^n \frac{(O_i - E_i)^2}{E_i}$$


* Donde:
* df = grados de libertad
* O = eventos observados
* E = eventos esperados (promedio general de todos los eventos)


- **H0** = ambas variables son independientes, no tiene relación
- **H1** = indica que las variables tienen algun grado de asociación o relación
