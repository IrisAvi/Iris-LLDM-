#***YAML***

##**INTRODUCCIÓN**
YAML (YAML Ain't Markup Language, en castellano, ‘YAML no es un lenguaje de marcado’) es un formato serialización de datos inspirado en lenguajes como XML, C, Python, Perl. Fue creado en 2001 por Clark Evans, Ingy döt Net y Oren Ben-Kiki.

A comienzos de su desarrollo, YAML significaba Yet Another Markup Language (otro lenguaje de marcado más) para distinguir su propósito centrado en los datos en lugar del marcado de documentos. Sin embargo, dado que se usa frecuentemente XML para serializar datos y XML es un auténtico lenguaje de marcado de documentos, es razonable considerar YAML como un lenguaje de marcado ligero.

##**SINTAXIS**

La sintaxis de YAML es sencilla. Fue diseñada teniendo en cuenta que fuera legible, pero que a la vez fuese fácilmente mapeable a los tipos de datos más comunes en la mayoría de los lenguajes de alto nivel. 
YAML utiliza una notación basada en la sangría y/o un conjunto de caracteres Sigil distintos de los que se usan en XML, haciendo que sea fácil componer ambos lenguajes.

##**CARACTERÍSTICAS**

Algunas de las principales características de YAML son: 

* Los contenidos en YAML se describen utilizando el conjunto de caracteres imprimibles de Unicode, bien en UTF-8 o UTF-16.

* La estructura del documento se denota indentando con espacios en blanco; sin embargo no se permite el uso de caracteres de tabulación para sangrar.

* Los miembros de las listas se denotan encabezados por un guion ( - ) con un miembro por cada línea, o bien entre corchetes ( [   ] ) y separados por coma espacio ( , ).

* Los vectores asociativos se representan usando los dos puntos seguidos por un espacio. en la forma "clave: valor", bien uno por línea o entre llaves ( {   } ) y separados por coma seguida de espacio ( , ).

* Un valor de un vector asociativo viene precedido por un signo de interrogación ( ? ), lo que permite que se construyan claves complejas sin ambigüedad.

* Los valores sencillos (o escalares) por lo general aparecen sin entrecomillar, pero pueden incluirse entre comillas dobles ( " ), o comillas simples ( ' ).

* En las comillas dobles, los caracteres especiales se pueden representar con secuencias de escape similares a las del lenguaje de programación C, que comienzan con una barra invertida ( \ ).

* Se pueden incluir múltiples documentos dentro de un único flujo, separándolos por tres guiones (---); los tres puntos ( ...) indican el fin de un documento dentro de un flujo.
Los nodos repetidos se pueden denotar con un ampersand ( & ) y ser referidos posteriormente usando el asterisco ( * ).

* Los comentarios vienen encabezados por la almohadilla ( # ) y continúan hasta el final de la línea.

[!NOTE]
Para más información consultar: [YAML] (https://es.wikipedia.org/wiki/YAML)





