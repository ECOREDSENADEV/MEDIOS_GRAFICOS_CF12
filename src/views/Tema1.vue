<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Composición y armado de productos editoriales
    
    figure.mb-4
      img(src='@/assets/curso/tema1/img_intrt1.png', alt='intro tema1')
    
    span.bgrh3.text-black.position-relative ¿Qué es la composición?                
      img.hijotext(src='@/assets/curso/tema1/imgtext.svg', alt='intro tema1')

    p.mt-4.mb-4 La composición es una expresión utilizada en la pintura, el diseño, la escultura y la fotografía y, 
      span.bgrspan se emplea para crear el uso equilibrado de los diferentes elementos gráficos 
      | que se encuentran en un espacio de trabajo visual, de esta forma se podrá dar un mensaje de forma clara a un público objetivo.
    
    .cajon.color-secundario.p-5.mb-4
      p La composición en el área de las artes visuales logra satisfacer algunas necesidades prácticas y estéticas, es la manera en la que se comunica y se ordenan los diferentes elementos conceptuales, técnicos y visuales con los que un creador (diseñador, ilustrador, escritor, entre otros) necesita para la creación de una estructura visual en el diseño de piezas gráficas impresas, conformadas por la estructura compositiva y la planeación.
      sapn La composición comprende la relación y las diferentes elecciones entre tamaños, coleres, texturas, alineamientos, pesos.
    
    p.text-center.mb-4 Al momento de diseñar una composición es importante tener en cuenta los siguientes elementos:

    .row.mb-5
      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar.pt-5
          img.contenavatar(src='@/assets/curso/tema1/tr1.svg' alt='AvatarTop')
          //- .tarjeta debe ir acompañado de una de una de estas clases => 
          //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
          //- estas clases tambien tienen un modificador --borde
          .tarjeta.color-primario
            .text-white.p-4
              h2.text-center El texto
              p Es un conjunto tipográfico determinado, el cual hace parte de toda publicación y se caracteriza por hacer parte de un estilo propio o familia tipográfica, es importante mencionar que cada uno de los diferentes estilos tipográficos se encarga de expresar conceptos definidos. (se debe tener en cuenta que los textos tipográficos dentro de una composición deben ser legibles y claros para el lector).


      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar.pt-5
          img.contenavatar(src='@/assets/curso/tema1/tr2.svg' alt='AvatarTop')
          //- .tarjeta debe ir acompañado de una de una de estas clases => 
          //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
          //- estas clases tambien tienen un modificador --borde
          .tarjeta.color-secundario
            .p-4
              h2.text-center Las imágenes
              p Hacen referencia a un número de objetos determinados y su distribución espacial en la cual es presentado teniendo en cuenta su escala y tamaño representados por el color y forma esto permite expresar lo que se desea mostrar en un texto para así darle fuerza.


      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar.pt-5
          img.contenavatar(src='@/assets/curso/tema1/tr3.svg' alt='AvatarTop')
          //- .tarjeta debe ir acompañado de una de una de estas clases => 
          //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
          //- estas clases tambien tienen un modificador --borde
          .tarjeta.color-primario
            .p-4
              h2.text-center Las márgenes y cuadrícula

              p Son una parte fundamental a la hora de crear una composición ya que dependiendo de su ubicación y proporción dependerá la posición de los textos e imágenes en un arte gráfico final.

      
      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar.pt-5
          img.contenavatar(src='@/assets/curso/tema1/tr4.svg' alt='AvatarTop')
          //- .tarjeta debe ir acompañado de una de una de estas clases => 
          //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
          //- estas clases tambien tienen un modificador --borde
          .tarjeta.color-secundario
            .p-4
              h2.text-center El formato

              p Dependerá de la necesidad de un cliente objetivo, es decir que tamaño se puede utilizar, que tipo de papel y cuál será su posición (vertical – horizontal) optimizando al máximo su uso, si se tiene como referencia un pliego este permitirá más información con un porcentaje menor de páginas y una mejor distribución de cada pieza gráfica, o por el contrario un pliego pequeño tendrá menos información y más cantidad de páginas.

    .row.mb-5
      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar.pt-5
          img.contenavatar(src='@/assets/curso/tema1/tr5.svg' alt='AvatarTop')
          //- .tarjeta debe ir acompañado de una de una de estas clases => 
          //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
          //- estas clases tambien tienen un modificador --borde
          .tarjeta.color-primario
            .text-white.p-4
              h2.text-center Espacios en blanco

              p Cabe resaltar que cada publicación cuenta con espacios vacíos, los cuales permiten generar una impresión de alivio, de calma, de tranquilidad, a la vista de un espectador, no se trata de saturar un espacio visual grafico de textos e imágenes para mostrar un contenido, siempre debe ser equilibrado, para que este sea agradable a la vista.


      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar.pt-5
          img.contenavatar(src='@/assets/curso/tema1/tr6.svg' alt='AvatarTop')
          //- .tarjeta debe ir acompañado de una de una de estas clases => 
          //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
          //- estas clases tambien tienen un modificador --borde
          .tarjeta.color-secundario
            .p-4
              h2.text-center El contexto o concepto

              p Se debe determinar a qué público está orientado el diseño, esto es lo más importante dentro de una composición editorial, de su desarrollo dependerá que una publicación cumpla las expectativas de un público determinado, puesto que cada mercado tiene distintas características.


      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar.pt-5
          img.contenavatar(src='@/assets/curso/tema1/tr7.svg' alt='AvatarTop')
          //- .tarjeta debe ir acompañado de una de una de estas clases => 
          //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
          //- estas clases tambien tienen un modificador --borde
          .tarjeta.color-primario
            .p-4
              h2.text-center Color

              p Se establece con un concepto claro por parte de los creadores y su público, la gama de colores estará presente detrás de cada edición. 

      
      .col-md-3.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar.pt-5
          img.contenavatar(src='@/assets/curso/tema1/tr8.svg' alt='AvatarTop')
          //- .tarjeta debe ir acompañado de una de una de estas clases => 
          //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
          //- estas clases tambien tienen un modificador --borde
          .tarjeta.color-secundario
            .p-4
              h2.text-center Equilibrio y armonía

              p Antes de hacer la entrega del producto es importante verificar que esta contiene una sinergia en su totalidad dando un mensaje claro dentro de un contexto determinado, aquí se debe ser autocritico y realizar los ajustes necesarios con el fin de hacer de un entregable un contenido atractivo al público.
    
    span.bgrh3.text-black.position-relative El diseño editorial                 
      img.hijotext(src='@/assets/curso/tema1/imgtext.svg', alt='intro tema1')
    
    div.mb-5
      p.mt-4 Forma parte del diseño gráfico, es decir, es una rama de esta profesión. En el caso editorial, este se encarga de la 
        span.bgrspan producción y diagramación de cualquier tipo de pieza literaria.  
        | Pueden ser libros, revistas, manuales, diarios, fanzines, folletos informativos, entre otros. Normalmente este tipo de piezas o documentos están compuestos por muchos pliegos o páginas y cuentan con diseños de composición y tipografías que son realizados de manera más regular que en otro tipo de diseños.

    .tarjeta.bgrspan.p-3.mb-5.position-relative.pt-5
        .row.justify-content-between.align-items-center
          .col-3
          .col.mb-3.mb-sm-0
            h3.mb-1 Características del diseño editorial
            p.text-small A continuación, observe el video Conceptos básicos diseño editorial para tener una mayor contextualización de este tema, sus elementos, características, entre otros.  
          .col-sm-auto
            a.boton.color-acento-contenido.texto-blanco(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
              span Descargar
              i.fas.fa-file-download
          img.hijoacct(src="@/assets/curso/tema1/img-actio1.svg")

    p La función principal del diseño editorial es la de maquetación y al momento de desarrollar una pieza gráfica, que esta pueda pasar por las diferentes etapas de ajustes, correcciones de diseño y su entorno, con el fin de llegar al resultado esperado; el diseño editorial cuenta con tres características principales: el texto, imágenes y retícula, diferenciados así:

    figure.mb-4
      .row  
        .col-md-3
        .col-md-6
          img(src='@/assets/curso/tema1/img_infog.svg', alt='intro tema1')
    
    p.text-center.mb-5 De igual forma, cuenta con tres componentes básicos: el target, la tipografía y los recursos económicos, representados así:

    .row.mb-5.brgflyp
      .col-sm-6.col-xl-4.mb-4.mb-xl-0.p-4.contenflip
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img
              img.brgflyp2.pt-5(src='@/assets/curso/tema1/imf_flyp1.svg', alt='intro tema1')
              h3.p-4.text-center.text-black El target

            .tarjeta-flip__contenido.p-2.p-xl-5
              h1.text-center El target
              p Se debe realizar un análisis del mercado cuantitativo y cualitativo, definiendo el consumidor final (o potencial), para ello es importante conocer el tipo de lector (sus intereses y gustos) al cual estará dirigido el diseño editorial.
 
      .col-sm-6.col-xl-4.mb-4.mb-xl-0.p-4.contenflip
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img
              img.brgflyp2.pt-5(src='@/assets/curso/tema1/imf_flyp2.svg', alt='intro tema1')
              h3.p-4.text-center.text-black La tipografía
            .tarjeta-flip__contenido.p-2.p-xl-5
              h1.text-center La tipografía
              p Esta debe ser afín al público objetivo, coherente a un estilo o marca, importante que sea tendencia, novedosa y fresca a simple vista, el éxito del diseño editorial dependerá en gran parte del tipo de tipografía a utilizar, por ello es indispensable escoger correctamente fuentes y tamaños.


      .col-sm-6.col-xl-4.mb-4.mb-xl-0.p-4.contenflip
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img
              img.brgflyp2.pt-5(src='@/assets/curso/tema1/imf_flyp3.svg', alt='intro tema1')
              h3.p-4.text-center.text-black Los recursos económicos

            .tarjeta-flip__contenido.p-2.p-xl-5
              h1.text-center Los recursos económicos
              p Es necesario contar con un presupuesto adecuado para la creación del diseño editorial, si se cuenta con un buen presupuesto posiblemente tendrá un buen producto, el esperado, cabe resaltar que no se requiere tener un presupuesto robusto para la creación de un diseño optimo, sin embargo, en el caso de que se cuente con un presupuesto mínimo, no limitará a que sea un resultado negativo o sea un mal diseño.
 

      





</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
