<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Paradigma orientado a objetos  
    .row.justify-content-center.mb-5
      .col-lg-7.mb-lg-0.mb-3(data-aos="fade-right")
        p El paradigma orientado a objetos es un concepto que inició en los años 70, pero que se logró estandarizar alrededor de 1997 con la aparición del Lenguaje Unificado de Modelado UML, teniendo presente que la palabra objetos no hace referencia necesariamente a componentes gráficos de un sistema de información (Rumbaugh, et al., 2004).
        .cajon-b.color-primario.p-3.mb-3
          p.mb-0.fw-bold Según Booch et al. (2007), para que un sistema o modelo sea orientado a objetos debe tener los siguientes elementos:  
        .tarjeta.color-acento-contenido.p-4
          ul.lista-ul--color.listado-h.mb-0
            li.d-flex.align-items-center
              i.fas.fa-circle.fa-xs(style="color: #361a69; font-size: 8px ").mb-0
              p.mb-0(style="color: #12263f") Abstracción 
            li.d-flex.align-items-center
              i.fas.fa-circle.fa-xs(style="color: #361a69; font-size: 8px ").mb-0
              p.mb-0(style="color: #12263f") Encapsulamiento 
            li.d-flex.align-items-center
              i.fas.fa-circle.fa-xs(style="color: #361a69; font-size: 8px ").mb-0
              p.mb-0(style="color: #12263f") Modularidad 
            li.d-flex.align-items-center
              i.fas.fa-circle.fa-xs(style="color: #361a69; font-size: 8px ").mb-0
              p.mb-0(style="color: #12263f") Jerarquía 
            li.d-flex.align-items-center
              i.fas.fa-circle.fa-xs(style="color: #361a69; font-size: 8px ").mb-0
              p.mb-0(style="color: #12263f") Polimorfismo 
      .col-lg-5.col-7.mb-lg-0.mb-3(data-aos="fade-left"): img(src='@/assets/curso/temas/3.svg', alt='') 
    .fondo-2.p-5.mn.mb-5
      .titulo-tres-icon.p-3
        h3 Abstracción 
      .row.justify-content-center.mb-5
        .col-lg-10
          
          .bloque-texto-d.color-secundario.p-4
            .bloque-texto-d__texto.mb-2
              i.fas.fa-quote-left(style="color: #3a1d71")
              h3.text-regular La abstracción es un proceso natural del ser humano y consiste esencialmente en la identificación de características claves según el contexto y conocimiento de las personas. De tal forma, se constituye en el medio mediante el cual se enfrentan los problemas complejos para extraer las características esenciales y posteriormente, representar dichas características en objetos.
                br
                br
                |La abstracción se enfoca en la vista externa de los elementos, lo cual permite separar su comportamiento esencial de su implementación e ignorar detalles internos. Mediante la abstracción hay un énfasis en el qué es y qué hace y no en el cómo debe implementarse o cómo funciona algo.
              i.fas.fa-quote-right(style="color: #3a1d71")
            .bloque-texto-d__autor 
              .h5.mb-0 - Aguilar, 2021
      p #[b Analicemos el siguiente ejemplo, sobre el proceso de abstracción..] 
        br 
        | En diferentes escenarios se aplican ciertos niveles de abstracción, por ejemplo, a la hora de decidir qué teléfono celular se desea comprar.
      .row.justify-content-center.mb-4
        .col-lg-7.mb-lg-0.mb-3
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--morada")
            div(titulo="Edad adulta ")
              p.mb-0 Una persona de negocios de edad adulta, puede interesarle la disponibilidad de comunicación por medio de telefonía móvil, así como la conectividad a las redes de datos y la facilidad con la que pueda conectarse a cualquiera de esas redes. 
            div(titulo="Adolescente ")
              p.mb-0 Probablemente una persona más joven, por ejemplo, un adolescente, podría interesarle más las capacidades para soportar diferentes tipos de archivos multimedia y la velocidad con la que se puedan ejecutar juegos. 
            div(titulo="Desarrollador ")
              p.mb-0 Una persona que desarrolla #[em software] para móviles, podrían interesarle más otras características como el tipo de sistema operativo, la operatividad con los sensores disponibles, y cosas de ese estilo. 
        .col-lg-5.col-7.mb-lg-0.mb-3(data-aos="fade-left"): img(src='@/assets/curso/temas/4.png', alt='')
      p.mb-5(data-aos='fade-right') Podemos concluir que lo que se busca ahora, es llevar ese mismo proceso para entender la esencia de los problemas complejos a desarrollar, y construir, a partir de esas abstracciones, que representan todos los elementos involucrados. 
    .titulo-tres-icon.p-3
      h3 Encapsulamiento
    .fondo-2.p-5.mn.mb-5
      .row.justify-content-center.mb-5
          .col-lg-10
            
            .bloque-texto-d.color-secundario.p-4
              .bloque-texto-d__texto.mb-2
                i.fas.fa-quote-left(style="color: #3a1d71")
                h3.text-regular El encapsulamiento es el proceso que permite agrupar datos y también operaciones que relacionan estos datos bajo una misma unidad lógica. 
                  br
                  br
                  |La encapsulación además, trae consigo algo llamado ocultamiento de datos, que consiste en la posibilidad de separar los elementos esenciales con los que se opera algo (interfaz – externa y pública) y de los detalles de su implementación (interna y privada). El encapsulamiento es un proceso que se debe realizar luego del proceso de abstracción.
                i.fas.fa-quote-right(style="color: #3a1d71")
              .bloque-texto-d__autor 
                .h5.mb-0 - Aguilar, 2021
      .row.justify-content-center.mb-5
        .col-lg-7.mb-lg-0.mb-3
          h5 A continuación, presentamos un ejemplo de encapsulamiento. 
          p Un control remoto, agrupa varios elementos que tienen funcionamientos particulares pero que en conjunto permiten la manipulación a distancia de un televisor. 
          p Adicionalmente, como usuarios de un control remoto interactuamos con él mediante su interfaz externa y pública, es decir, sus botones de colores, cada botón tiene un identificador que es conocido para nosotros y mediante el cual manipulamos el televisor.
          .tarjeta.p-4(style="background-color: #f2e5fd ")  
            p.mb-0 Como usuarios de un control remoto no es esencial su implementación (interna y privada), es decir, cómo interactúan las ondas de luz de baja frecuencia o las señales que son decodificadas por los aparatos electrónicos. 
        .col-lg-5.col-7(data-aos="fade-left"): img(src='@/assets/curso/temas/5.png', alt='')
    .fondo-2.mn.mb-5.p-5
      .titulo-tres-icon.p-3
        h3 Modularidad  
      p.mb-5(data-aos='fade-right') La modularidad es la propiedad que permite dividir una aplicación o sistema en partes más pequeñas, idealmente deben ser muy independientes (bajo acoplamiento) y altamente funcionales (alta cohesión). 
      p Dividir un sistema en partes más pequeñas, tiene varios beneficios, entre los cuales se pueden listar: 
        .row.justify-content-center.mb-5
          .col-lg-8
            .tarjeta.p-4.mb-3(style="background-color: #8722e2 ")
              .row.justify-content-center.align-items-center
                .col-lg-2.col-5: img(src='@/assets/curso/temas/6.svg', alt='').mb-4.mb-lg-0
                .col-lg-10
                  p.mb-0.text-white Se produce la complejidad. Los problemas más pequeños son más fáciles de resolver que los problemas grandes. 
            .tarjeta.color-primario.p-4
              .row.justify-content-center.align-items-center
                .col-lg-2.col-5: img(src='@/assets/curso/temas/6.svg', alt='').mb-4.mb-lg-0
                .col-lg-10
                  p.mb-0.text-white Cada módulo puede ser ejecutado y probado de forma independiente, lo cual facilita la corrección de errores y permite que un problema pueda ser desarrollado por varias personas en forma paralela. 
      h5 Como ejemplo de modularidad, tenemos:  
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-4.col-8.mb-lg-0.mb-3: img(src='@/assets/curso/temas/7.png', alt='')
        .col-lg-8
          .tarjeta.p-4(style="background-color: #f2e5fd ")  
            p Un vehículo se puede construir a partir del desarrollo de cada una de sus partes de forma independiente, e incluso, por fabricantes diferentes: puertas, ventanas, motor, chasis, asientos, llantas, etc.  
                    
            p Luego, en un proceso que la mayoría de las veces es automatizado, se unen estas partes para producir el vehículo.
            
            p.mb-0 Cuando el vehículo es reparado u optimizado, se puede cambiar cada una de sus partes, de forma individual. 
    .fondo-2.mn.mb-5.p-5
      .titulo-tres-icon.p-3
        h3 Jerarquía
      .row.justify-content-center.mb-5
        .col-lg-7.mb-lg-0.mb-3(data-aos="fade-right")
          p.mb-0 Las jerarquías son clasificaciones y ordenaciones de las abstracciones de un problema (Aguilar, 1998), permiten comprender de forma general la estructura de un sistema y favorecen, en algunos casos, la reutilización de características y comportamientos de las abstracciones definidas. 
            br
            br
            |Las jerarquías que se producen desde el punto de vista de la estructura de objetos se les conoce como agregación y composición, y las jerarquías que se producen desde las estructuras de clases se les conoce como generalización y especialización.
        .col-lg-5.col-7: img(src='@/assets/curso/temas/8.png', alt='') 
      h5 Conozcamos la jerarquía de un computador de escritorio: 
      .titulo-sexto.color-acento-contenido(data-aos='fade-right')
        h5 Figura 1. 
        span Jerarquía de un computador de escritorio 
      img.mb-4.d-none.d-lg-block(src='@/assets/curso/temas/9.png', alt='Imagen que presenta la jerarquía de un computador de escritorio, compuesto por un monitor, el teclado, el mouse y la torre.')
      img.mb-4.d-lg-none.d-block(src='@/assets/curso/temas/9rp.svg', alt='Imagen que presenta la jerarquía de un computador de escritorio, compuesto por un monitor, el teclado, el mouse y la torre.')
      p.mb-5 Dependiendo del nivel de dependencia que existe entre la abstracción que agrupa y las abstracciones que son partes, se definen relaciones de composición o agregación. 
      .tarjeta.p-4(style="background-color: #f2e5fd ")  
        p.mb-0 La representación de las uniones entre las abstracciones de una jerarquía usa símbolos diferentes para diferenciar lo que son jerarquías de clases y jerarquías de objetos. Esto se detalla en el tema de diagrama de clases. 
    .fondo-2.mn.mb-5.p-5
      .titulo-tres-icon.p-3
        h3 Polimorfismo  
      p.mb-5(data-aos='fade-right') Es la característica que permite que una abstracción tome diferentes formas o diferentes comportamientos según el contexto. Esta característica se potencia en compañía de las jerarquías vistas anteriormente. 
        br
        br
        | #[b En la siguiente figura], se muestra un ejemplo de una jerarquía sobre figuras planas y adicionalmente, se indica que hay un comportamiento llamado Calcular Área, es decir, todas las figuras planas pueden calcular su área. 
      .titulo-sexto.color-acento-contenido(data-aos='fade-right')
        h5 Figura 2. 
        span Ejemplo de una jerarquía sobre figuras planas 
      img.mb-4.d-none.d-lg-block(src='@/assets/curso/temas/10.png', alt='Imagen que presenta un ejemplo de una jerarquía sobre figuras planas.')
      img.mb-4.d-lg-none.d-block(src='@/assets/curso/temas/10rp.svg', alt='Imagen que presenta un ejemplo de una jerarquía sobre figuras planas.')
      p.mb-5(data-aos='fade-right') En la jerarquía de clases del ejemplo anterior, las abstracciones rectángulo, círculo y triángulo heredan las características de la abstracción figura plana incluyendo el comportamiento de Calcular Área. Sin embargo, este comportamiento tiene diferentes formas de calcularse dependiendo qué abstracción de la jerarquía es la que la utilice: 
      .row.justify-content-center.mb-5
        .col-lg-10
          .tarjeta.p-4(style="background-color: #f2e5fd ")  
            ul.fa-ul
              li.mb-2
                i.fas.fa-circle.fa-xs(style="color: #361a69; font-size: 8px ").mb-0 
                p.mb-0(style="color: #12263f") Para el caso de la abstracción rectángulo, el cálculo de área se obtiene luego de multiplicar el valor de la base y la altura de la figura. 

              li.mb-2
                i.fas.fa-circle.fa-xs(style="color: #361a69; font-size: 8px ").mb-0
                p.mb-0(style="color: #12263f") Para la abstracción círculo, se debe multiplicar la constante π (Pi) por el valor del radio al cuadrado. 
              li
                i.fas.fa-circle.fa-xs(style="color: #361a69; font-size: 8px ").mb-0
                p.mb-0(style="color: #12263f") Para la abstracción triángulo se calcula diferente, en este caso, el cálculo del área se obtiene luego de multiplicar el valor de la base por la altura de la figura y dividir el valor entre dos. 

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

<style lang="sass">
.cajon-b:before
  height: 100%
  opacity: .2
.listado-h
  display: flex
  flex-wrap: wrap
  justify-content: center
  align-self: start
  li
    margin: 0 .5rem
.fondo-2
  background-image: url(../assets/curso/temas/fondo-2.svg)
  background-repeat: no-repeat
  background-position: 0
  background-size: cover
.bloque-texto-d:before
  opacity: .2
.acordion__header
  h3
    color: $white
</style>
