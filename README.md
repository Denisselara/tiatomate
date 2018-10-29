# Maquetacion Tia Tomate

## 1) Requerimientos

### a) Material Entregado
Diseñador envía:

a)	Mockup diseñado de landing page:
* 1 navbar sencillo con 4 links al costado derecho
* 1 header de introducción a marca
* 1 sección de descripción producto
* 1 sección nosotros
* 1 sección contacto/negocio
* 1 footer con logo, redes sociales y 4 links

b)	Guía de estilos con:
* Imágenes
* Colores
* Fuentes

### b) Generales
La empresa Tía Tomate (productora de tomates orgánicos), pide crear una maqueta de la página "acerca de".

En ella desean mostrar a sus clientes una pequeña reseña sobre su historia, la procedencia de sus productos y mostrar a las personas que trabajan cosechando estas verduras.

Según sus requerimientos la página debe:

* Ser responsiva
* Mostrar la pasión que sienten por sus tomates
* Dar enfásis a la compra de sus productos
* Mostrar el logo de la empresa

Ellos comentan que crearán el contenido de su página web con la persona encargada de mantener sus redes sociales.

### c) Específicos

Para el maquetado general, se utilizará:
* Bootrstrap 3.3.7
-Navbar default
-Sistema de grillas para 1 header, 3 secciones, 1 footer

### d) Visuales

* Elementos en base de Guía de Estilo

-Colores:
* #E56353
* #686963
* #707070
* #FAFAFA
* #FFFFFF

-Fuentes (Google Fonts):

* Raleway-Bold
* Raleway-ExtraLight
* OpenSans-Regular

-Imágenes:

* 2 logos (navbar, footer)
* 2 imagenes genericas de tomates
* 2 imágenes dueños empresa

## 2) Sketch Desktop

![](maquetacion/Sketch_Desktop2.png?raw=true)

## 3) Sketch mobile

![](maquetacion/Sketch_Mobile2.png?raw=true)

## 4) Estructura CSS

==GLOBAL STYLES==

h1,h2,h3{
  font-family: Raleway;
}

p,li,a,small{
  font-family: OpenSans;
}

==FONT HIERARCHY==
h1{
  font-size: 3em;
}

h2{
  font-size: 2.25em;
}

h3{
  font-size: 1.75em;
}

p{
  color: hsla(0,0%,0.8);
}

==@ media only screen and (max-width : 767px) {==

  h1{
    font-size: 2em;
  }

  h2{
    font-size: 1.625em;
  }

  h3{
    font-size: 1.375em;
  }
}

==BUTTON==
  .button_tiatomate{
  }

  .button_tiatomate:hover{
  }

  .button_tiatomate2{
  }

  .button_tiatomate:hover{
  }

==NAVBAR==
  .navbar_tiatomate{
  }

  .icon-bar{
  }

  .navbar-brand img{
  }

  .navbar{
  }

==HEADER==
  .header_tiatomate{
  }

  .header_tiatomate h1{
  }

  .header_tiatomate p{
  }

  ==@ media only screen and (max-width : 767){==

    .header_tiatomate{
    }

    .header_tiatomate h1{
    }

    .header_tiatomate p{
    }
  }

==DESCRIPCION==

  .descripcion {
  }

  .descripcion h2 {
  }

  .descripcion p {
  }

  .descripcion > hr {
  }

  .descripcion__inner {
  }

  .descripcion__inner h3 {
  }

  .descripcion__inner p {
  }

  .descripcion__inner__image-top {
  }

  .descripcion__inner__image-bottom {
  }

  ==@ media only screen and (max-width : 767px){==

    .descripcion {
    }

    .descripcion h2 {
    }

    .descripcion p {
    }

    .descripcion hr {
    }

    .descripcion__inner {
    }

    .descripcion__inner h3 {
    }

    .descripcion__inner p {
    }

    .descripcion__inner__image-top, .descripcion__inner__image-bottom {
    }
  }

==NOSOTROS==
  .nosotros{
  }

  .nosotros h1{
  }

  .nosotros__personas {
  }

  .nosotros__personas h2 {
  }

  .nosotros__personas p {
  }

  .nosotros__personas > hr {
  }

  .nosotros__personas {
  }

  .nosotros__personas h3 {
  }

  .nosotros__personas p {
  }

  .nosotros__personas__image-top {
  }

  .nosotros__personas__image-bottom {
  }

  ==@ media only screen and (max-width : 767px){==

    .nosotros__personas {
    }

    .nosotros__personas h2 {
    }

    .nosotros__personas p {
    }

    .nosotros__personas hr {
    }

    .nosotros__personas {
    }

    .nosotros__personas h3 {
    }

    .nosotros__personas p {
    }

    .nosotros__personas__image-top, ..nosotros__personas__image-bottom {
    }
  }

==NEGOCIO==
  .negocio{
  }

  .negocio h1{
  }

  .negocio {
  }

  .negocio > hr {
  }

  ==@ media only screen and (max-width : 767px){==

    .negocio {
    }

    .negocio hr {
    }

    .negocio h1{
    }

    .negocio {
    }
  }

==FOOTER==
      .footer{
      }

      .footer__secciones {
      }

      .footer p {
      }

      .footer > hr {
      }

      .footer__secciones p {
      }

      .socialnetworkfooter img {
      }

    ==@ media only screen and (max-width : 767px){==

      .footer p {
      }

      .footer hr {
      }

      .footer__secciones {
      }

      .footer__secciones h2 {
      }

      .footer__secciones p {
      }

      .footer__secciones hr {
      }

      .footer__secciones {
      }

      .footer__secciones p {
      }
    }
