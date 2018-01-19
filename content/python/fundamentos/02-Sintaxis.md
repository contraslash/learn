+++
date = "2018-01-17T21:53:08-05:00"
title = "02 sintaxis"
type = "post"
+++

# Sintaxis

Como dije anteriormente, la principal característica de Python es la legibilidad de su código, caracteres de terminación o segmentación de bloques usuales en otros lenguajes son inexistentes en python.

Notamos la diferencia comparando con Java y Python


<table>
    <thead>
    <tr>
        <th>
            Programa
        </th>
        <th>
            Java
        </th>
        <th>
            Python
        </th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>
            Hola mundo
        </td>

        <td>
<pre>
public class HelloWorld
{
   public static void main(String[] args)
   {
      System.out.println("Hola Mundo!");
   }
}
</pre>
        </td>

        <td>
<pre>
print("Hola Mundo!")
</pre>
        </td>
    </tr>
    <tr>
        <td>
            Condicionales
        </td>

        <td>
<pre>
if (true) {
    System.out.print("Verdadero");
} else {
    System.out.print("False");
}
</pre>
        </td>
        <td>
<pre>
if True:
    print("Verdadero")
else:
    print("False")
</pre>
        </td>
    </tr>
    <tr>
        <td>
            Ciclos for
        </td>

        <td>
<pre>
for (int i = 0; i < 5; i++) {
   for (int j = 0; j <= i; j++) {
      System.out.print("*");
   }
   System.out.println();
}
</pre>
        </td>
        <td>
<pre>
for i in xrange(5):
    for j in xrange(i+1):
        ptiny("*")
    print()
</pre>
        </td>
    </tr>
    </tbody>
</table>

En el siguiente capítulo recordaremos las estructuras básicas de programación, pero lo que quiero que comprendas en este punto es que aunque la indentación es recomendada en otros lenguajes de programación, en Python es obligatoria, además de servir para la separación semántica de bloques de programación, mantenie el código legible.

El espacio recomendado entre cada bloque de indentación es de 4 espacios, esta es la recomendación por [PEP 8](https://www.python.org/dev/peps/pep-0008/).

> PEP (Python Enhancement Proposals) son un conjunto de guías que la comunidad de Python define para la mejora del lenguaje. Todos los cambios han ocurrido en el lenguaje están consignados en estas propuestas. Son el equivalente Python de las [RFC](https://en.wikipedia.org/wiki/Request_for_Comments) por parte de la [IETF](https://en.wikipedia.org/wiki/Internet_Engineering_Task_Force).