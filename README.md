# Interpolación tipo Lagrange 2D

La función [GenInterpLagrange2D] genera una corrección imaginaria con un polinomio
complejo de grado 2 e interpola los datos utilizando el algoritmo propuesto de Lagrange
2D en forma baricéntrica.

Las funciones [EstInteg], [CorrIm] y [EstOscil] son auxiliares y se utilizan en la
generación de la corrección imaginaria. La clase [BarLagrange2D] realiza la
interpolación en forma baricéntrica.

También se incluye la clase [LagrangeCos2D] que corresponde a la propuesta inicial de
interpolación tipo Lagrange 2D usando la parte real de una interpolación compleja. La
función interpoladora que genera es en la práctica la misma que la de [BarLagrange2D],
sin embargo, la ejecución del método [interp] de esta última es más rápida.