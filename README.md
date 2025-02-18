# Iris-LLDM-
Repositori Llenguatge de Marques Iris

# ***JSON***

## **INTRODUCCIÓN**
JSON (JavaScript Object Notation, 'notación de objeto de JavaScript') es un formato de texto utilizado para el intercambio de datos. Está compuesto por la notación literal de objetos de JavaScript, aunque se considera un formato independiente del lenguaje por ser una alternativa a XML.

## **VENTAJAS DEL JSON**
En relación con XML, una de las principales ventajas que preenta JSON es que resulta mucho más sencillo escribir un analizador sintáctico (parser) para él.​ Hay que tener en cuenta que en JavaScript, un texto JSON se puede analizar fácilmente usando la función eval(), algo que ha sido fundamental para que haya sido aceptado por parte de la comunidad de desarrolladores AJAX.2

## **SINTAXIS**
La sintaxis de JSON se compone de diferentes tipos de datos. Entre ellos:

* Números: Se permiten números negativos y los númeors pueden contener decimales separados por puntos.

* Cadenas: Representan secuencias de cero o más caracteres. Se deben poner entre doble comilla.

* Booleanos: Representan valores booleanos y pueden tener dos valores: true y false

* Null: Representan el valor nulo.

* Array: Representa una lista ordenada de cero o más valores los cuales pueden ser de cualquier tipo. Los valores se deben separan por comas y el vector se mete entre corchetes.

* Objetos: Son colecciones no ordenadas de pares de la forma <nombre>:<valor> separados por comas y puestas entre llaves. El nombre tiene que ser una cadena entre comillas dobles. El valor puede ser de cualquier tipo. 

**Ejemplo**:

```
{"dueños":[
	{
        "nombre": "Victoria",
	    "edad": "36",
	    "mascotas": [
		    {"nombreMascota": "Kena"},
		    {"nombreMascota": "Freya"}
	    ]
    },
	{"nombre": "Leo",
	 "edad": "22",
	 "mascotas": [
		{"nombreMascota": "Goku"}
	    ]
    },
    ]
}
```


## **MODELOS DE PROCESAMIENTO**
Debido al amplio uso de JSON, se han desarrollado APIs para diversos lenguajes de programación.Entre ellos podemos encontrar APIs creadas para: C, C++, C#, Delphi, Java, JavaScript, Python, etc.

## **COMPARACIÓN CON XML**
Hay muchos analizadores JSON en el lado del servidor, existiendo al menos un analizador para la mayoría de los entornos. En algunos lenguajes, como Java o PHP, hay diferentes implementaciones donde escoger. En JavaScript, el análisis es posible de manera nativa con la función JSON.parse(). Ambos formatos carecen de un mecanismo para representar grandes objetos binarios.

Con independencia de la comparación con XML, JSON puede ser muy compacto y eficiente si se usa de manera efectiva. Por ejemplo, la aplicación DHTML de búsqueda en «BarracudaDrive» (en inglés). Archivado desde el original el 21 de mayo de 2006. recibe los listados de directorio como JSON desde el servidor. Esta aplicación de búsqueda está permanentemente consultando al servidor por nuevos directorios, y es notablemente rápida, incluso sobre una conexión lenta.

Los entornos en el servidor normalmente requieren que se incorpore una función u objeto analizador de JSON. Algunos programadores, especialmente los familiarizados con el lenguaje C, encuentran JSON más natural que XML, pero otros desarrolladores encuentran su escueta notación algo confusa, especialmente cuando se trata de datos fuertemente jerarquizados o anidados muy profundamente.

### *JSON Y YAML*
YAML es un superconjunto de JSON que trata de superar algunas de las limitaciones de este. Aunque es más complejo, todavía puede considerarse como ligero. El lenguaje de programación Ruby utiliza YAML como el formato de serialización por defecto. 

> [!NOTE]
> Para más información consultar: [JSON] (https://es.wikipedia.org/wiki/JSON)

# ***YAML***

## **INTRODUCCIÓN**
YAML (YAML Ain't Markup Language, en castellano, ‘YAML no es un lenguaje de marcado’) es un formato serialización de datos inspirado en lenguajes como XML, C, Python, Perl. Fue creado en 2001 por Clark Evans, Ingy döt Net y Oren Ben-Kiki.

A comienzos de su desarrollo, YAML significaba Yet Another Markup Language (otro lenguaje de marcado más) para distinguir su propósito centrado en los datos en lugar del marcado de documentos. Sin embargo, dado que se usa frecuentemente XML para serializar datos y XML es un auténtico lenguaje de marcado de documentos, es razonable considerar YAML como un lenguaje de marcado ligero.

## **SINTAXIS**

La sintaxis de YAML es sencilla. Fue diseñada teniendo en cuenta que fuera legible, pero que a la vez fuese fácilmente mapeable a los tipos de datos más comunes en la mayoría de los lenguajes de alto nivel. YAML utiliza una notación basada en la sangría y/o un conjunto de caracteres Sigil distintos de los que se usan en XML, haciendo que sea fácil componer ambos lenguajes.

## **CARACTERÍSTICAS**

Algunas de las principales características de YAML son:

Los contenidos en YAML se describen utilizando el conjunto de caracteres imprimibles de Unicode, bien en UTF-8 o UTF-16.

La estructura del documento se denota indentando con espacios en blanco; sin embargo no se permite el uso de caracteres de tabulación para sangrar.

Los miembros de las listas se denotan encabezados por un guion ( - ) con un miembro por cada línea, o bien entre corchetes ( [ ] ) y separados por coma espacio ( , ).

Los vectores asociativos se representan usando los dos puntos seguidos por un espacio. en la forma "clave: valor", bien uno por línea o entre llaves ( { } ) y separados por coma seguida de espacio ( , ).

Un valor de un vector asociativo viene precedido por un signo de interrogación ( ? ), lo que permite que se construyan claves complejas sin ambigüedad.

Los valores sencillos (o escalares) por lo general aparecen sin entrecomillar, pero pueden incluirse entre comillas dobles ( " ), o comillas simples ( ' ).

En las comillas dobles, los caracteres especiales se pueden representar con secuencias de escape similares a las del lenguaje de programación C, que comienzan con una barra invertida ( \ ).

Se pueden incluir múltiples documentos dentro de un único flujo, separándolos por tres guiones (---); los tres puntos ( ...) indican el fin de un documento dentro de un flujo. Los nodos repetidos se pueden denotar con un ampersand ( & ) y ser referidos posteriormente usando el asterisco ( * ).

Los comentarios vienen encabezados por la almohadilla ( # ) y continúan hasta el final de la línea.

> [!NOTE]
> Para más información consultar: [YAML] (https://es.wikipedia.org/wiki/YAML)
