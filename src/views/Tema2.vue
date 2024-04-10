<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Clases y objetos
    .row.justify-content-center.mb-5
      .col-lg-7.mb-lg-0.mb-3
        p Las clases y objetos son el corazón de la programación orientada a objetos y en la construcción de estos elementos, se refleja cada una de las características del paradigma orientado a objetos revisado en el apartado anterior. Algunas veces parece que ambos elementos se traslapan y algunas otras veces se suele hablar de forma indiscriminada de estos dos elementos, por lo cual, a continuación, se ampliará la revisión para comprender sus características y diferencias. 
          br
          br
          |Un objeto en el paradigma orientado a objetos representa un objeto del mundo real, el objeto debe ser especializado y solo se encarga de una tarea. 
      .col-lg-5.col-7: img(src='@/assets/curso/temas/11.svg', alt='')
    h4 Un objeto puede ser: 
    .fondo-3.mb-5.p-3
      .row.justify-content-center
        .col-lg-4.col-7
        .col-lg-7
          SlyderF.mb-5(columnas="col-lg-6 col-xl-6 ")
            .tarjeta.color-primario.p-4
              .row.justify-content-center.mb-3
                .col-6
                  img(src='@/assets/curso/temas/12.svg' alt='AvatarTop')
              p.text-center Cosas tangibles como un avión, un auto o un televisor. 
            .tarjeta.color-primario.p-4
              .row.justify-content-center.mb-3
                .col-6
                  img(src='@/assets/curso/temas/13.svg' alt='AvatarTop')
              p.text-center Roles o papeles como un gerente, un cliente o un vendedor. 
            .tarjeta.color-primario.p-4
              .row.justify-content-center.mb-3
                .col-6
                  img(src='@/assets/curso/temas/14.svg' alt='AvatarTop')
              p.text-center Organizaciones como una empresa o un departamento.  
            .tarjeta.color-primario.p-4
              .row.justify-content-center.mb-3
                .col-6
                  img(src='@/assets/curso/temas/15.svg' alt='AvatarTop')
              p.text-center Interacciones como transacciones o contratos. 
            .tarjeta.color-primario.p-4
              .row.justify-content-center.mb-3
                .col-6
                  img(src='@/assets/curso/temas/16.svg' alt='AvatarTop')
              p.text-center Incidentes como vuelos, sucesos o accidentes. 
            .tarjeta.color-primario.p-4
              .row.justify-content-center.mb-3
                .col-6
                  img(src='@/assets/curso/temas/17.svg' alt='AvatarTop')
              p.text-center Lugares como muelles, carreteras, etc. 
    p.mb-5(data-aos='fade-right') Los objetos se comunican con otros objetos por medio de mensajes y su estructura se describe en la siguiente tabla. 
    .fondo-4.mn.p-5.mb-5
      .titulo-sexto.color-acento-contenido(data-aos='fade-right')
        h5 Tabla 1.  
        span Estructura de un objeto
      .row.justify-content-center.mb-5
        .col-lg-8
          .tabla-a.color-acento-botones.mb-5
            table
              caption Leyenda de la tabla
              thead.border-0
                tr(style="background-color: #00ffdf")
                  th 
                  th 
              tbody
                tr
                  td Identidad (nombre). 
                  td Representa las características del objeto. Son los parámetros que lo definen y lo diferencian de objetos del mismo tipo. 
                tr
                  td Atributos y propiedades (estado). 
                  td Representa las características del objeto. Son los parámetros que lo definen y lo diferencian de objetos del mismo tipo. 
                tr
                  td Métodos. 
                  td Representan el comportamiento del objeto. Acciones que realizan o manejan los datos. 
    p.mb-5(data-aos='fade-right') Ahora, una clase es una abstracción o visión generalizada de un conjunto de objetos que tienen características (atributos y propiedades) y métodos iguales o similares. Es decir, una clase representa las características comunes de un conjunto de objetos, como se muestra en la figura que se encuentra a continuación. 
    .row.justify-content-center.mb-5
      .col-lg-8
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 Figura 3. 
          span Ejemplo clases y objetos
        img(src='@/assets/curso/temas/18.svg', alt='La imagen describe lo que es una clase, los objetos se presentan como personajes, los cuales representan los objetos de una clase, estos tienen atributos y propiedades como: nombre, apellido, edad, estatura, género y también cuentan con métodos como comer, hablar, reír.')
    p.mb-5(data-aos='fade-right') Una clase es un tipo de dato definido por el usuario, no existe en forma concreta, debido a que es solo una abstracción. A partir de la definición de una clase, se pueden construir objetos. Las clases son equivalentes a los tipos de datos y los objetos son los identificadores que se crean a partir de este tipo particular de dato. 
      br
      br
      |Así, una clase puede servir para definir (instanciar) objetos. Un objeto es una instancia de una clase totalmente independiente de otros objetos de la misma clase. La estructura de los objetos corresponderá a la estructura definida por la clase desde la cual se crean, así como se observa en la siguiente figura. 
    .row.justify-content-center.mb-5
      .col-lg-10
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 Figura 4. 
          span Estructura de una clase y objetos 
        img(src='@/assets/curso/temas/19.svg', alt='Imagen que presenta la estructura de una clase y objetos.')
    .fondo-2.mn.p-5
      .titulo-tres-icon.p-3
        h3 Atributos
    .row.justify-content-center.mb-5
      .col-lg-5.mb-lg-0.mb-3
        p.mb-0 Los atributos de los objetos que se definen en las clases, cuando se describen en lenguaje de modelado formal o en un lenguaje de programación, se estructuran de forma similar a como se definen los identificadores, es decir, cada atributo se expresa con un tipo de dato y nombre del identificador. 
          br
          br
          |Adicionalmente, tanto los atributos como los métodos tendrán una especificación, en la que se indica si corresponden a elementos públicos (interfaces visibles) o elementos privados (implementación interna), lo que representa una aplicación de la propiedad del encapsulamiento.  
      .col-lg-7
        .tarjeta.p-4(style="background-color: #8722e2 ")
          ol.lista-ol--cuadro
            li.d-flex.mb-4
              .lista-ol--cuadro__vineta
                span A
              p.mb-0.text-white Lo primero por hacer, es por medio de la abstracción, identificar de la información existente, cuáles son los posibles objetos y las posibles características claves para tener en cuenta al realizar un registro de matrícula y la información esencial relacionada con los estudiantes.    
            li.d-flex.mb-4
              .lista-ol--cuadro__vineta
                span B
              p.mb-0.text-white Puede ser útil también, verificar de estudiantes reales el tipo de información que requiere la institución.        
            li.d-flex.mb-4
              .lista-ol--cuadro__vineta
                span C
              p.mb-0.text-white Luego de esto, se empieza a construir las plantillas (clases) con la estructura de los elementos identificados. Posteriormente, estas clases definidas, permitirán instanciar objetos que corresponden a la información concreta con la que se manipulará el sistema.       
                  
                  



</template>

<script>
export default {
  name: 'Tema2',
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

<style lang="sass">
.fondo-3
  background-image: url(../assets/curso/temas/fondo-3.svg)
  background-repeat: no-repeat
  background-position: 0
  background-size: cover
.fondo-4
  background-image: url(../assets/curso/temas/fondo-4.png)
  background-repeat: no-repeat
  background-position: 0
  background-size: cover
.lista-ol--cuadro__vineta
  min-width: 40px
  height: 40px
  font-weight: bold
  border-radius: 50%
  span
    color: $color-sistema-texto
</style>
