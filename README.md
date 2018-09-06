# Ejemplos y ejercicios de Bootstrap

## 1. Hola Bootstrap
* Incluir archivo del CDN de Bootstrap y probar el LiveServer.
* Comandos básicos de git:
  * `git init` - inicializar el repositorio
  * `git config user.name` - configurar el nombre de usuario
  * `git config user.email` - configurar el correo del usuario
  * `git status` - verificar el estado del repositorio
  * `git add` - agregar archivos al repositorio
  * `git commit` - confirmar los cambios
  * `git remote` - establecer el repositorio remoto
  * `git push` - subir los cambios al repositorio remoto

## 2. Malla de Bootstrap

### Clases importantes
* `container`
* `row`
* `col`
* `col-*`

## 3. Malla responsiva

### Clases importantes
* `col-{breakpoint}-*`

### Puntos de quiebre (breakpoint)
* Extra small `< 576px`
* `sm` - small `>= 576px`
* `md` - medium `>= 768px`
* `lg` - large `>= 992px`
* `xl` - extra large `>= 1200px`


## 4. Alineamiento en la malla 

### Clases importantes

#### Alineamiento vertical de todos los elementos de una fila
* `align-items-start`
* `align-items-center`
* `align-items-end`

#### Alineamiento vertical de una columna individual
* `align-self-start`
* `align-self-center`
* `align-self-end`

#### Alineamiento horizontal de las columnas de una fila
* `justify-content-start`
* `justify-content-center`
* `justify-content-end`
* `justify-content-around`
* `justify-content-between`

## 5. Márgenes y padding

### Tipografía
* `h1-h6` : títulos
* `display-1-4` : tipografía grande
* `lead` : tipografía delgada
* Alineamiento del texto
  * `text-center`
  * `text-right`
  * `text-left`
  
### Colores
  * Color de texto: `text-*`
  * Color de fondo: `bg-*`
  * Donde `*` corresponde a alguno de los colores: 
    * `secondary`  
    * `success`  
    * `danger`  
    * `warning`  
    * `info`  
    * `light`  
    * `dark`  
    * `white`  

### Márgenes y padding
  
Los márgenes y padding se establecen por medio de la clase con el formato `{propiedad}{lado}-{tam}`.
  
La `{propiedad}` corresponde a:
  * `m` - para el margen
  * `p` -  para el padding
  
El `{lado}` corresponde a:
  * `t` - para arriba
  * `b` - para abajo
  * `l` - para izquierda
  * `r` - para derecha
  * `x` - para izquierda y derecha
  * `y` - para arriba y abajo
  * `ninguno` - para aplicarlo a los 4 lados

El `{tam}` especifica el tamaño por medio de un número:
  * `0` - elimina la propiedad
  * `1` - equivale a `0.25 rem`
  * `2` - equivale a `0.5 rem`
  * `3` - equivale a `1 rem`
  * `4` - equivale a `1.5 rem`
  * `5` - equivale a `3 rem`
  * `auto` - equivale a que el navegador calcule el margen.
  * Un `rem` es una unidad relativa que equivale a `16px`.
  
La propiedad del margen o padding se puede aplicar de manera responsiva `{propiedad}{lado}-{breakpoint}-{tam}`.

## 6. Ejercicio de sitio en construcción

Aplicar los márgenes y padding vistos anteriormente.

Incluir bordes, imágenes responsivas y diferentes estilos de texto.

### Bordes

Los bordes se pueden agregar utilizando la clase con el formato: `border-{lado}`, donde `{lado}` corresponde a:

* `top` - agrega borde arriba
* `right` - agrega borde a la derecha
* `bottom` - agrega borde abajo
* `left` - agrega borde a la izquierda
* `ninguno` - agrega el borde a los cuatro lados

Se pueden eliminar bordes con utilizando la clase con el formato `border-{lado}-0`, aplicando los mismos valores para `{lado}` mencionados anteriormente.

Los bordes se pueden colorear agregando la clase `border-*` donde `*` corresponde a cualquiera de los colores utilizados para el texto o el fondo.

Adicionalmente, las esquinas de los bordes se pueden redondear utilizando la clase `rounded-{lado}` considerando los mismos lados para el borde y además de `circle` para obtener un borde totalmente circular.

### Imágenes
* `img-fluid`
* `img-thumbnail`

### Texto
* `text-justify`
* `text-left`
* `text-center`
* `text-right`
* `text-lowercase`
* `text-uppercase`
* `text-capitalize`

### Propiedad `display`
La propiedad `display` de CSS permite establecer el tipo de disposición de los elementos HTML: en línea, en bloque, en linea-bloque. Bootstrap permite aplicar esta propiedad utilizando la clase `d-{breakpoint}-{valor}`, utilizando los mismos nombres para el breakpoint definidos en la malla responsiva y siendo `{valor}` alguno de los siguientes:

* `none` - para ocultar el elemento
* `inline` - para acomodar el elemento en línea
* `block` - para acomodar el elemento en bloque
* `inline-block` - para acomodar el elemento en línea y bloque


## 7. Ejercicio grid

## 8. Formularios

### Clases importantes
* `form-group`
* `form-control`
* `form-control-file`
* `form-check`
* `form-check-input`
* `form-check-label`
* `btn`
* `btn-*`
* `btn-outline-*`
* `btn-block`
* `btn-lg`
* `btn-sm`

## 9. Formularios en malla

### Clases importantes
* `form-row`
* `col-{breakpoint}-*`

## 10. Ejercicio de formulario

## 11. Formulario horizontal (con validación)

### Clases importantes
* `row`
* `col-{breakpoint}-*`
* `needs-validation`
* `valid-feedback`
* `invalid-feedback`
* `offset-*`
  
### Atributos importantes
* `novalidate`
* `required`
* `pattern`
* `minlength`

### Script de valiación
* `addEventListener`
* `submit`
* `checkValidity()`
* `preventDefault()`
* `stopPropagation()`
* `classList.add('was-validated')`

## 12. Alertas

### Clases importantes

* `div.alert`
* `alert-*`
* `alert-heading`
* `button.close`

### Atributos importante
* `data-dismiss = "alert"`

## 12. Modal

### Clases importantes

* `modal`
* `modal-dialog`
* `modal-content`
* `modal-header`
* `modal-title`
* `modal-body`
* `modal-footer`
* `fade`
* `modal-dialog-centered`
* `modal-sm`
* `modal-lg`

### Atributos importantes
* `data-toggle = "modal"`
* `data-target = "#id"`
* `data-dismiss = "modal"`

## 14. Navbar

### Clases importantes
* `div.navbar`
* `navbar-light`
* `navbar-dark`
* `a.navbar-brand`
* `ul.navbar-nav`
* `li.navbar-item`
* `a.navbar-link`
* `div.collapse`
* `navbar-collapse`
* `navbar-expand-{breakpoint}`
* `button.navbar-toggler`
* `span.navbar-toggler-icon`
  
### Atributos importantes
* `data-target = "#id"`
* `data-toggle = "collapse"`

## 15. Carrusel

### Clases importantes

* `div.carousel.slide`
* `div.carousel-inner`
* `div.carousel-item.active`
* `div.carousel-caption`
* `a.carousel-control-prev`
* `span.carousel-control-prev-icon`
* `a.carousel-control-next`
* `span.carousel-control-next-icon`
* `ol.carousel-indicators`
* `li.active`

### Atributos importantes

* `data-slide = "prev"`
* `data-slide = "next"`
* `data-target = "#id"` 
* `href = "#id"`
* `data-slide-to = "numero-slide"`
* `data-ride = "carousel"`
* `data-interval = "tiempo-pausa"`

### Recursos importantes
* `https://via.placeholder.com/350x150/0000FF/FFFFFF`

## 16. Tarjetas

### Clases importantes
* `div.card`
* `div.card-body`
* `h2.card-title`
* `p.card-text`
* `a.card-link`
* `img.card-img-top`
* `img.card-img-bottom`
* `div.card-header`
* `div.card-footer`
* `div.card-group`
* `div.card-deck`
* `div.card-columns`

### Recursos importantes
  * `https://placeimg.com/640/480/nature`

## 17. Galería de imágenes

### Requisitos importantes

* Tarjetas
* Modales
* Templates de cadenas (backticks)
* Expresiones incrustadas `${expresion}`
* `innerHtml`

## 18. Acordeón

### Clases importantes

* `div.collapse`

### Atributos importante

* `data-toggle = "collapse"`
* `data-target = "#id"`
* `href = "#id"`

### Recursos importantes
* `https://source.unsplash.com/daily`