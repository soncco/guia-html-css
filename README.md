# Guía HTML y CSS

*Simple guía en español con ejemplos para empezar con HTML5 y CSS3*

## <a name='INDEX'>Índice</a>

  1. [Introducción](#introduccion)
  2. [Lo básico](#lo-basico)

## <a name='introduccion'>Introducción</a>

Todo sitio web en internet usa HTML. Los sitios web están compuestos por *páginas*, y estas a su vez están hechas de marcas de código (etiquetas) que tienen significado semántico.

HTML es el acrónimo de **Hyper Text Markup Language**, un lenguaje de marcas que como leímos antes, da valor semántico al contenido de una página web.

CSS es el acrónimo de **Cascade Style Sheet**, un lenguaje que nos ayuda a dar color, borde, margen, animación o cambiar de comportamiento a las etiquetas HTML.

En esta pequeña guía aprenderemos desde cero la manera de como usando HTML y CSS juntos podemos crear sitios web.

**[[ Volver al índice ]](#INDEX)**

## <a name='lo-basico'>Lo básico</a>

Las etiquetas HTML pueden tener cualquiera de las siguentes formas:

```html
<etiqueta atributo="valor1" otroatributo="valor2"></etiqueta>
<etiqueta atributo="valor">
<etiqueta atributo>
```

Y la sintaxis CSS puede tener básicamente cualquiera de las siguientes formas (y otras más que trataremos más adelante):

```css
etiqueta {
  propiedad1: valor;
  propiedad2: valor;
  /* Este es un comentario que explica que podemos agregar muchas propiedades más */
}

/* Los comentarios también funcionan aca */
.clase {
  propiedad: valor;
}

#identificador {
  propiedad: valor:
}
```

La regla <code>.clase</code> afecta a todas las etiquetas que tengan ```<etiqueta class="clase"></etiqueta>``` mientras que la regla <code>#identificador</code> afecta a la etiqueta identificada con ```<etiqueta id="identificador"></etiqueta>```

**[[ Volver al índice ]](#INDEX)**