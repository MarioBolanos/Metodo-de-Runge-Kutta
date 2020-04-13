# Método de Runge-Kutta

En otros cuadernos hemos estudiado el método de Euler para resolver ecuaciones diferenciales ordinarias (EDO). El método de Euler es quizás el más simple de entender e implementar y, por lo tanto, es muy popular como material de enseñanza. Sin embargo, para fines científicos, el método de Euler es inexacto en comparación con los métodos más complejos que usan el mismo tamaño de paso, y también son condicionalmente inestables.

Aquí, consideraremos el Método Runge-Kutta, que es uno de los métodos numéricos más aplicados para resolver EDO. Se considera razonablemente eficiente teniendo en cuenta el tiempo de cálculo y su aproximación de cuarto orden ofrece una precisión decente, es decir, lo suficientemente bueno para la mayoría de los problemas que no requieren soluciones de muy alta precisión. Tenga en cuenta que presentamos el método en su forma más simple: puede encontrar su implementación algo diferente en otros lugares. En general, las implementaciones más nuevas (e inteligentes) del método pueden proporcionar aumentos significativos a su eficiencia.

<section class = "post-meta">
Por Magnus H-S Dahle, Henning G. Hugdal, Håkon W. Ånes y Peter Berg
</section>
