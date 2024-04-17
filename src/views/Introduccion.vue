<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .fondo-i.p-5.mn
      .tarjeta(style="background-color: #debefb ").p-4.imagen-ab.mb-5
        .row.justify-content-center.align-items-center
          .col-lg-2.d-lg-block.d-none.imagen-ab__img: img(src='@/assets/curso/temas/1.svg', alt='')
          .col-lg-2.col-7.d-block.d-none: img(src='@/assets/curso/temas/1.svg', alt='')
          .col-lg-10
            p.mb-0 ¿Sabías que algunos de los elementos fundamentales que se usan para la descripción de un algoritmo en un lenguaje de programación, son los identificadores? Estos pueden ser variables o constantes, dependiendo del comportamiento de los valores que registramos en ellos. 
      .row.justify-content-center.mb-5
        .col-lg-7.mb-lg-0.mb-3
          p Estos identificadores se componen principalmente de tres elementos: nombre del identificador, valor almacenado y posición física de la memoria donde se encuentra. Para poder utilizar identificadores, se debe realizar el proceso de declaración del identificador, donde se define el tipo de dato asociado, el cual indica el tamaño a reservar en la memoria y el nombre de dicho identificador.  
            br
            br
            |Cuando el problema a desarrollar requiere gran cantidad de información y adicionalmente, la información se compone de diversos tipos de datos, el mecanismo de identificadores se vuelve obsoleto, no solo por la gran cantidad de estructuras de memoria que se deberán construir, sino porque su gestión también será más compleja.
          .tarjeta.p-4.color-primario 
            p.mb-0 Al tener problemas cada vez más complejos y grandes cantidades de datos, se requieren mejores mecanismos para gestionar los datos y es a partir de este escenario, que surge la programación orientada a objetos, como un paradigma que busca aproximar el manejo de la información, desde la forma como es procesada internamente en los programas a como realmente se representa en la vida cotidiana.
        .col-lg-5.col-7: img(src='@/assets/curso/temas/2.png', alt='')
      p.mb-5(data-aos='fade-right') A lo largo del componente formativo, se profundizará sobre los conceptos en los que se fundamenta el paradigma y luego se examinarán en detalle algunos de los elementos centrales que se utilizan para implementar el paradigma. 
        br
        br
        | #[b Bienvenido.] 
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass">
.fondo-i
  background-image: url(../assets/curso/temas/fondo-i.svg)
  background-repeat: no-repeat
  background-position: 0
  background-size: cover
.imagen-ab
  position: relative
  &__img
    img
      position: absolute
      left: 0
      width: 150px
      top: 0
      transform: translate(20px,0)
</style>
