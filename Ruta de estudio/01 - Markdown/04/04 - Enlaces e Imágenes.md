## Enlaces e Imágenes

### Enlaces de texto

Para crear enlaces de texto en Markdown, se utiliza la siguiente sintaxis:

```markdown
[Texto del enlace](URL)
```

- Reemplaza "Texto del enlace" con el texto que deseas mostrar para el enlace.
- Reemplaza "URL" con la dirección web a la que deseas que el enlace redirija.

**Ejemplo:**

```markdown
[Visita el sitio web de GitHub](https://github.com)
```

El resultado será un enlace de texto que se verá así: [Visita el sitio web de GitHub](https://github.com).

---

### Enlaces de imágenes

Para insertar imágenes en Markdown y vincularlas desde una URL, se utiliza la siguiente sintaxis:

```markdown
![Texto alternativo](URL de la imagen)
```

- Reemplaza "Texto alternativo" con una descripción de la imagen que se mostrará si no se puede cargar.
- Reemplaza "URL de la imagen" con la dirección web de la imagen que deseas insertar.

**Ejemplo:**

```markdown
![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

El resultado será la inserción de la imagen con su respectivo texto alternativo:

![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

Para personalizar el tamaño de la imagen, puedes utilizar el atributo `width` o `height` dentro de la etiqueta de imagen. Por ejemplo:

```markdown
![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png){ width=200px }
```

Este ejemplo establece un ancho de 200 píxeles para la imagen.

Además, si deseas centrar la imagen en el texto, puedes utilizar etiquetas HTML dentro de tu documento Markdown. Por ejemplo:

```markdown
<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo de GitHub" width="200px" />
</p>
```

El resultado será una imagen centrada en el texto.

Recuerda ajustar los valores de ancho (`width`), alto (`height`) y la alineación (`align`) según tus necesidades y preferencias.

---

### Enlaces a secciones dentro de un archivo

En Markdown, también es posible crear enlaces que lleven a secciones específicas dentro de un archivo Markdown. Para ello, sigue estos pasos:

1. Asigna un identificador único a la sección objetivo dentro del archivo Markdown. Puedes hacerlo utilizando la sintaxis de encabezados:

```markdown
## Sección A {#seccion-a}
```

2. Crea un enlace utilizando el identificador asignado precedido por el símbolo `#`:

```markdown
[Enlace a Sección A](#seccion-a)
```

**Ejemplo:**

```markdown
[Enlace a Sección A](#seccion-a)
```

El resultado será un enlace que, al hacer clic, llevará al usuario a la sección correspondiente dentro del mismo documento Markdown.

Recuerda reemplazar "Sección A" con el título de la sección que deseas enlazar y "#seccion-a" con el identificador único que le hayas asignado.

¡Ahora puedes crear enlaces a páginas web, imágenes y secciones específicas dentro de tus archivos Markdown en GitHub, personalizando su tamaño, alineación y otros aspectos visuales según tus necesidades!
