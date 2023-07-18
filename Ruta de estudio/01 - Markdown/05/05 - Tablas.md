# Tablas

### Crear y dar formato a tablas

En Markdown, puedes crear tablas utilizando barras verticales `|` para separar las columnas y guiones `-` para delimitar las filas y encabezados. El primer renglón de la tabla define los encabezados y se separa de los datos con una línea horizontal.

Por ejemplo, la siguiente sintaxis crea una tabla sencilla de dos columnas y dos filas:

```markdown
| Encabezado 1 | Encabezado 2 |
| ------------ | ------------ |
| Dato 1       | Dato 2       |
| Dato 3       | Dato 4       |
```

Resultado:

| Encabezado 1 | Encabezado 2 |
| ------------ | ------------ |
| Dato 1       | Dato 2       |
| Dato 3       | Dato 4       |

### Alinear contenido en tablas

Puedes alinear el contenido dentro de las celdas de una tabla utilizando dos puntos `:` para indicar la alineación. Puedes colocar los dos puntos a la izquierda, a la derecha o en ambos lados del guion.

Por ejemplo, la siguiente sintaxis crea una tabla con alineación personalizada:

```markdown
| Nombre      | Apellido    | Edad |
| :---------- | :---------: | ---: |
| Juan        | Pérez       | 25   |
| María       | González    | 30   |
```

Resultado:

| Nombre | Apellido | Edad |
|:------ |:--------:| ----:|
| Juan   | Pérez    | 25   |
| María  | González | 30   |

### Combinar celdas en tablas

Puedes combinar celdas en una tabla utilizando el símbolo de guion vertical `|`. Puedes combinar celdas verticalmente para crear celdas más grandes o combinar celdas horizontalmente para combinar filas o columnas.

Para combinar celdas verticalmente, simplemente coloca el guion vertical en la línea horizontal que separa las filas:

```markdown
| Frutas          | Cantidad |
| --------------- | -------- |
| Manzanas        | 3        |
| Plátanos        | 2        |
| Naranjas        | 4        |
| :---------------:| -------- |
| Total           | 9        |
```

Resultado:

| Frutas            | Cantidad |
| ----------------- | -------- |
| Manzanas          | 3        |
| Plátanos          | 2        |
| Naranjas          | 4        |
| :---------------: | -------- |
| Total             | 9        |

Para combinar celdas horizontalmente, utiliza el guion vertical en el encabezado correspondiente:

```markdown
| Animales   |         |        |
| :--------- | :-----: | -----: |
| Perro      | Gato    | Pájaro |
| Tigre      | León    | Oso    |
| Mono       | Elefante|        |
```

Resultado:

| Animales |          |        |
|:-------- |:--------:| ------:|
| Perro    | Gato     | Pájaro |
| Tigre    | León     | Oso    |
| Mono     | Elefante |        |

### Personalización de tablas

Markdown no ofrece una sintaxis nativa para personalizar el estilo de las tablas, como colores o bordes. Sin embargo, puedes utilizar extensiones o convertir tu documento Markdown a HTML para aplicar estilos personalizados.

Si deseas agregar colores o bordes a tus tablas, puedes utilizar HTML en línea dentro de tus celdas. Por ejemplo:

```markdown
| Encabezado 1 | Encabezado 2 |
| ------------ | ------------ |
| <span style="color:red">Dato 1</span> | <span style="color:blue">Dato 2</span> |
```

Resultado:

| Encabezado 1                          | Encabezado 2                           |
| ------------------------------------- | -------------------------------------- |
| <span style="color:red">Dato 1</span> | <span style="color:blue">Dato 2</span> |

Recuerda que la personalización de las tablas en Markdown puede variar según la plataforma o el editor donde se visualicen, pero la documentación anteriormente presentada es para la plataforma de Github.
