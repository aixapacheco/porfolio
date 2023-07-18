# Sintaxis básica de Markdown

Ya tenemos claro que Markdown es un lenguaje de marcado ligero y fácil de usar que te permite formatear el texto de forma sencilla.

A continuación, quiero mostrarte cómo utilizar la sintaxis básica de Markdown, que incluye encabezados, listas y enlaces, para que comiences a trabajar con este de forma rapida y fácil.

## Encabezados

Los encabezados se utilizan para resaltar títulos y subtítulos en tu documento. Puedes crear encabezados de diferentes niveles, desde h1 hasta h6, utilizando uno o varios símbolos de numeral (#) seguidos de un espacio y el texto del encabezado.

```markdown
# Esto es un encabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6
```

## Listas

Las listas te permiten organizar elementos en forma de lista numerada o lista de viñetas.

### Listas ordenadas

Para crear una lista ordenada, utiliza números seguidos de un punto y un espacio para cada elemento de la lista.

```markdown
1. Elemento 1
2. Elemento 2
3. Elemento 3
```

### Listas desordenadas

Para crear una lista desordenada, utiliza guiones, asteriscos o signos de más seguidos de un espacio para cada elemento de la lista.

```markdown
- Elemento 1
- Elemento 2
- Elemento 3
```

```markdown
* Elemento 1
* Elemento 2
* Elemento 3
```

```markdown
+ Elemento 1
+ Elemento 2
+ Elemento 3
```

### Listas anidadas

Puedes anidar listas dentro de otras listas para crear una estructura jerárquica.

```markdown
- Elemento 1
  - Subelemento 1.1
  - Subelemento 1.2
- Elemento 2
  - Subelemento 2.1
    - Subsubelemento 2.1.1
    - Subsubelemento 2.1.2
  - Subelemento 2.2
```

## Enlaces

Puedes crear enlaces a páginas web o a secciones dentro del mismo documento.

### Enlaces de texto

Para crear un enlace de texto, utiliza corchetes [] para el texto del enlace y paréntesis () para la URL o la ubicación a la que deseas que el enlace lleve.

```markdown
[Visita nuestra página web](http://www.ejemplo.com)
```

### Enlaces de imágenes

Si deseas insertar una imagen en tu documento Markdown, utiliza la misma sintaxis que para los enlaces de texto, pero con un signo de exclamación (!) antes de los corchetes.

```markdown
![Texto alternativo de la imagen](http://www.ejemplo.com/imagen.jpg)
```

### Enlaces a secciones dentro de un archivo

Si deseas crear un enlace que lleve a una sección específica dentro del mismo documento, primero debes crear un identificador para esa sección utilizando el símbolo de numeral (#) y el nombre de la sección.

```markdown
[Salta al encabezado](#encabezado)
```

En este caso, el enlace llevará al encabezado con el identificador "encabezado".

### Creación de tablas con Markdown

En distintos casos vamos a necesitar tomar apuntes en base a tablas por lo que lo se usan ( || ) y ( - ) para crearlas.

```markdown
| Columna 1 | Columna 2 |
|-----------|-----------|
| Fila 1    |           |
| Fila 2    |           |
```

### Escribiendo codigo dentro de markdown

Como ya vez en los puntos anteriores podemos mostrar como es que se escribe el codigo sin crear confución al procesador de markdown en el camino por ejemplo si necesitamos crear un enlace [ENLACE](enlace) en la explicación el mismo se vuelve parte del texto.

En cambio si lo hacemos usando (``) podemos evitar que se mezcle con el resto del texto en markdown

```markdown
[ENLACE](enlace)
```

Esto se puede lograr usando tres veces la tilde diagonal para marcar la entrada y tres tildes diagonales para marcar la salida.

```markdown

\```php (AQUI SE PUEDEN USAR LOS TRES TILDES)

<?php>

<?>
\``` (FINALIZANDO EL CODIGO)

```

Esta es solo una introducción a la sintaxis básica de Markdown. Puedes explorar más sobre Markdown y sus diversas características para dar formato a tu contenido de manera efectiva.

¡Diviértete experimentando con Markdown y aprovecha su simplicidad para crear documentos bien estructurados en GitHub!
