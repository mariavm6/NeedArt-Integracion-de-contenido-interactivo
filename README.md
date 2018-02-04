# Añadir un carrusel a la interfaz del escaparate virtual y mejorar el aspecto e interactividad de una interfaz web NeedArt!

En esta práctica debíamos dotar a nuestra página web de animación y hacerla más vistosa e interactiva mediante la utilización de CSS y JQuery.

## Requisitos funcionales

**1.Incluir un carrusel** 
Este debía incluir al menos 3 imágenes relacionadas con la temática de la página web.
Para hacer la animación del carrusel hemos utilizado CSS y JQuery.
Nos hemos basado en el video de youtube:
- Como hacer un Slider con Jquery y sin plugins.
https://www.youtube.com/watch?v=uzLabNV0rmQ&t=11s

**2.Más vistosa (menú)**
La página debe ser más vistosa, se pide hacer un efecto de scroll hacia abajo e implementar un efecto similar al de la página:
 http://annaeshwood.com/
 Para nuestra animación hemos utilizado la documentación de la url: 
 www.cwdesigns.de/jquery-scrollflow-plugin.html
 Hemos incluido la clase (class="scrollflow -slide-top -opacity") en los elementos de las imágenes para que estas subieran y bajaran al hacer scroll.
 También hemos animado las letras con ayuda de la siguiente web:
 https://codepen.io/SitePoint/pen/MwEaQM
 CSS Animations on Scroll - Slide in From Left
 Y al igual que en la anterior, le hemos dado la clase (class="fa fa-quote-left") a los elementos texto para que se movieran de izquierda a derecha en la página al hacer scroll.

**3.Microinteracciones**

1) El botón de las redes sociales en las páginas de detalles, al pasar por él se despliega una lista de varias redes con su icono y su nombre
2) En el menú de navegación al pasar el ratón por encima de los elementos se despliega una pestaña con los sub-elementos.
3) En el menú también vemos como al mover el puntero por encima de los elementos principales estos se subrayan.
4) En las páginas de detalles de los cuadros y fotos vemos como el botón comprar tiene una animación.
5) Los enlaces de la página cambian de color al hacer el hover.
6) En el formulario los botones de Facebook, Twitter y Registrar tienen otra animación.
7) Hemos aplicado una transición al cambiar de página cuando hacemos click con Jquery, la idea la hemos sacado de esta web:
http://webcache.googleusercontent.com/search?q=cache:http://www.bufa.es/transicion-fade-paginas-jquery/&gws_rd=cr&dcr=0&ei=d2F3Wo-2AcfuUvXqnegK
Cada vez que se cambia de página el cambio de una a otra se vuelve algo más lento.

**4. Menú de navegación**
Se pedía crear un menú similar al de la página:
http://reseau.coop/.
Nosotras hemos utilizado la página web: 
https://programadorwebvalencia.com/menu-desplegable-de-varios-niveles-con-jquery-y-sass/ para hacer un menú similar con ayuda de CSS y JQuery y posicionarlo en fixed.

**5. Imágenes**
Se pide que se comporten como un banco de imágenes parecido a https://pixabay.com/es/.
En la página principal al poner el puntero por encima de las imágenes vemos como aparecen los iconos de favoritos, representado por un corazón y de like por una estrella. También se encuentra un botón de detalles que nos lleva a la descripción de la foto y al botón de redes sociales.
La animación la hemos sacado de:
https://tympanus.net/codrops/2011/11/02/original-hover-effects-with-css3/.
Hemos decidido meter la descripción de las imágenes y el precio en la página de destalles en vez de en la principal porque creemos que el tamaño de las imágenes en el índex es demasiado pequeño y no se vería bien.
Los iconos de favorito y like al hacer click llaman a una función que va sumando los clicks.

**6.Aviso de uso de cookies**
Se mostrará un aviso de uso de cookies y se pedirá la aceptación de su uso la primera vez que se acceda a la página.

**CSS**
En el CSS de todas las hojas de estilo solo se han utilizado clases como se pedía en la práctica.

**Material a entregar**

Se publicará la página en GitHub y Github pages junto a un fichero README.md en el que se describa cómo se ha implementado

#### Autoras

- **Gema de la Fuente Romero** - [Github](https://github.com/Gema-de-la-Fuente)

- **María Villalobos Martín** - [Github](https://github.com/mariavm6)
