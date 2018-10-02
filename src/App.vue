<template lang="pug">
  #App.layout
    // - landing page Ladrillos Lark cintiatahirih.jp@gmail.com
    header.layout__header
      .layout__header--logo
        img(src="../static/images/logo/lark.svg", alt="Ladrillos Lark")
      nav.layout__header--navbar
        ul.layout__header--list
          li PRODUCTOS
          li CLIENTES
          li UBÍCANOS
          li COTIZAR
          li NOTICIAS
          li PROCESO
    main.layout__body
      section
        h1 ¿CÓMO PRODUCIR LADRILLOS DE CALIDAD?
        p
          | La producción remota desde tiempos antiguos y el uso empleado ha evolucionado en conjunto con los nuevos métodos de fabricación que han surgido.
        p
          | Hoy en día es más práctico poder fabricarlos. No existe complejidad en convertir la arcilla, el agua y la tierra en conjunto en un ladrillo. A continuación, verás las etapas que siguen los fabricantes hasta llegar al resultado final. Use el scroll(rueda del mouse) para navegar.
        ul
          li
            span  01.-
            | Extracción
          li
            span  02.-
            | Molienda
          li
            span  03.-
            | Prensadora
          li
            span  04.-
            | Cortadora
          li
            span  05.-
            | Secadora
          li
            span  06.-
            | Apiladero
          li
            span  07.-
            | Prehorno
          li
            span  08.-
            | Horno
      section
        h2  Bienvenido
        p
          | Ahora conocerás el proceso productivo para la correcta realización de unos ladrillos de calidad
      section
        div
          span Primer nivel
          div
            h3  Extracción
            h4  Materia Prima
          div
            p
              | El proceso productivo empieza por la minuciosa selección de los principales insumos, 3 tipos de arcilla y tierra, sumado a esto, el control de calidad de la materia prima que empleamos.
        div
          span Segundo nivel
          div
            h3  Molienda
            h4  Creando partículas
          div
            p
              | Transportamos el 50% de tierra y arcilla por el molino, para luego transformar la materia prima en partículas muy finas, obteniendo una granulometría de acuerdo al estándar del tipo de ladrillo que se va a fabricar. Y luego los insumos, junto al agua, pasan por la mezcladora, creando así, una masa de color chocolate.
        div
          span Tercer nivel
          div
            h3  Prensadora
            h4  Dando forma
          div
            p
              | La mezcla es transportada por diferentes moldes, para todos los tipos de ladrillos que se van a fabricar. Y luego se le coloca el sello de distinción con el logo de ladrillos LArk.
            p
              | La longitud de la masa que sale por la boquilla de la presadora es de 100cm.
        div
          span Cuarto nivel
          div
            h3  Cortadora
            h4  Medida exacta
          div
            p
              | Luego el ladrillo, aún estando humedo, es cortado en serie. Las medidas varían de acuerdo al tipo de línea de producto.
        div
          span Quinto nivel
          div
            h3  Secadora
            h4  Adios humedad
          div
            p
              | Contamos con un moderno sistema de secado rápido traído desde Francia e Italia. El ladrillo, aún estando crudo, ingresa a los hornos y alcanza temperaturas de hasta 500°, que ayudan a eliminar el 85% de agua para el secado del ladrillo, otorgándole un color grisaceo.
        div
          span Sexto nivel
          div
            h3  Apiladero
            h4  Agrupando
          div
            p
              | Una vez secado el ladrillo, es transportado en grupo a la zona de apilado. Donde existen unas máquinas con una especie de tenazas, llamadas apiladores, que se encargan de transportar el material a una movilidad con destino hacia el horno.
        div
          span Séptimo nivel
          div
            h3  Secado final
            h4  Materia Prima
          div
            p
              | Lark, cuenta con modernos sistemas de fabricación industrial y hornos de última generación, que nos aseguran un proceso de secado uniforme para eliminar la humedad restante.
        div
          span Octavo nivel
          div
            h3  Horno
            h4  Parada final
          div
            p
              | Para terminar con el proceso de cocción, nuestros hornos se encargan de otrogarle el color rojizo tan característico, brindándonos un ladrillo de calidad.
    footer.layout__footer
      ul
        li LADRILLOS LARK 2018
        li HOLA@LADRILLOSLARK.COM
        li
      ul
        li
          img(src="", alt="FACEBOOK")
          span FACEBOOK
        li
          a(href="#")
            img(src="", alt="YOUTUBE")
            span  YOUTUBE
        li
          a(href="#")
            img(src="", alt="INICIAR CHAT")
            span INICIAR CHAT
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
  @import 'normalize.css';
  @import '../static/css/fonts.css';
  @import '../static/css/layout.css';
  body {
    font-family: 'gotham_bold';
  }
</style>
