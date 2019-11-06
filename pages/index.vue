<template lang="pug">  
  #cv.py-10.px-2.mx-auto.container(class="lg:py-10 lg:px-12")
    header.flex.flex-col.flex-wrap.font-bold.justify-center.items-center(class="lg:flex-row lg:items-center")
      #foto.order-1(class="lg:w-1/4 lg:order-3 lg:flex lg:justify-end")
        img(src="/avatar.jpg" class="lg:h-56 lg:w-56").h-48.w-48.rounded-full
      #presentacion.text-center.order-2.w-full(class="lg:w-1/2 lg:order-1 lg:text-left")
        h1.text-4xl(class="lg:text-5xl") Sebastian Cardoso
        h2.text-3xl(class="lg:text-4xl").text-blue-500 Web developer
        #contact.flex.flex-col.justify-center.mt-3.w-full(class="lg:flex-row lg:justify-start")
          h3.mb-3.flex.justify-center
            img.float-left(src="/icons/email.svg").mr-1
            span hi@sebastiancardoso.com
          h3.ml-5.flex.justify-center
            img.float-left(src="/icons/location.svg").mr-1.mb-3
            span La Plata, Buenos Aires
      #social-network.w-full.order-3(class="lg:w-1/4 lg:order-2")
        ul.flex.justify-around(class="lg:flex-col lg:justify-end").mt-10
          li
            a(href="http://sebastiancardoso.com").flex.justify-end.text-right.mb-3.items-center
              span.hidden(class="lg:block hover:underline hover:text-blue-800") sebastiancardoso.com
              img(src="/icons/web.svg" class="lg:h-10 w-10" ).ml-2
          .flex.justify-end.text-right.mb-3.items-center
            a(href="http://linkedin.com/in/sebastiancardoso92").flex.justify-end.text-right.items-center
              span.hidden(class="lg:block hover:underline hover:text-blue-800") sebastiancardoso92
              img(src="/icons/linkedin.svg" class="lg:h-10 w-10" ).ml-2
          li
            a(href="http://github.com/sebaveg").flex.justify-end.text-right.items-center
              span.hidden(class="lg:block hover:underline hover:text-blue-800") sebavaeg
              img(src="/icons/github.svg" class="lg:h-10 w-10" ).ml-2
        
    main.flex.flex-col.flex-wrap.justify-between.mt-20(class="lg:flex-row lg:justify-between lg:items-stretch")
      div(class="lg:w-1/2").px-4
        h3.border-b.border-gray-600.font-bold.mb-5.text-3xl.text-blue-600.text-center(class="lg:text-4xl") Experiencia
        
        a(href="http://geounity.herokuapp.com/" class="hover:underline hover:text-blue-800")
          h4.text-2xl.font-bold.text-center Geounity
        #calendar.flex.justify-center
          img(src="/icons/calendar.svg").h-5.w-5.mr-2
          span: i.text-center.text-gray-500 May-19 al Presente
        h4.mt-2 Aplicación para mediación de debates entre personas y comunidades.
        ul.custom-list.mt-2
          li Frontend desarrollado con <b>Vue</b>, Vuex y Nuxt.
          li Backend API desarrollado con <b>Node</b>, Express y Sequelize.
          li Base de Datos diseñada e implementada con <b>Postgres</b> y <b>MongoDB</b>.
          li Integración del frontend con el backend y la base de datos.

        a(href="https://reversi-game.sebastiancardoso92.now.sh/" class="hover:underline hover:text-blue-800")
          h4.text-2xl.font-bold.text-center.mt-5 Reversi-Game
        #calendar.flex.justify-center
          img(src="/icons/calendar.svg").h-5.w-5.mr-2
          span: i.text-center.text-gray-500 Jun-19 a Ago-19
        h4.mt-2 Juego de mesa para dos personas también conocido como 'Othello'.
        ul.custom-list.mt-2
          li Frontend desarrollado con <b>React</b> y Redux.
          li Unit testing con Jest y Enzyme.

        a(href="https://next-podcasts.sebastiancardoso92.now.sh/" class="hover:underline hover:text-blue-800")
          h4.text-2xl.font-bold.text-center.mt-5 Listen Podcast
        #calendar.flex.justify-center
          img(src="/icons/calendar.svg").h-5.w-5.mr-2
          span: i.text-center.text-gray-500 Ago-19
        h4.mt-2 Pequeña aplicación para escuchar Podcast
        ul.custom-list.mt-2
          li Frontend desarrollado con Next.
          li Comunicación con API de Audioboom.

      div.mt-20.px-4(class="lg:w-1/2 lg:mt-0")
        h3.border-b.border-gray-600.font-bold.mb-5.text-3xl.text-blue-600.text-center(class="lg:text-4xl") Educación
        
        h4.text-2xl.font-bold.text-center Educación Online y autodidacta
        .flex.justify-center
          img(src="/icons/calendar.svg").h-5.w-5.mr-2
          span: i.text-center.text-gray-500 Feb-18 a Presente
        .flex.justify-center
          <svg class="svg-gray" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-4.198 0-8 3.403-8 7.602 0 4.198 3.469 9.21 8 16.398 4.531-7.188 8-12.2 8-16.398 0-4.199-3.801-7.602-8-7.602zm0 11c-1.657 0-3-1.343-3-3s1.343-3 3-3 3 1.343 3 3-1.343 3-3 3z"/></svg>
          span: i.text-center.text-gray-500 Web
        ul.custom-list.mt-2
          li Documentación, artículos, videos, otros proyectos, etc.
          li Platzi.
          li EDteam.

        h4.text-2xl.font-bold.text-center.mt-5 Facultad de Informática UNLP
        .flex.justify-center
          img(src="/icons/calendar.svg").h-5.w-5.mr-2
          span: i.text-center.text-gray-500 Feb-10 a Nov-14
        .flex.justify-center
          <svg class="svg-gray" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-4.198 0-8 3.403-8 7.602 0 4.198 3.469 9.21 8 16.398 4.531-7.188 8-12.2 8-16.398 0-4.199-3.801-7.602-8-7.602zm0 11c-1.657 0-3-1.343-3-3s1.343-3 3-3 3 1.343 3 3-1.343 3-3 3z"/></svg>
          span: i.text-center.text-gray-500 La Plata

        .mt-20.px-4(class="lg:w-1/2")
        h3.border-b.border-gray-600.font-bold.mb-5.text-3xl.text-blue-600.text-center(class="lg:text-4xl") Idiomas
        
        .w-full
          .flex
            p.float-left.font-bold.mr-2(class="w-2/12") Inglés: 
            .shadow.w-full.bg-gray-500(class="10/12")
              .bg-blue.text-xs.leading-none.py-1.text-center.text-white.bg-blue-500(style="width: 75%") 75%
          .flex.mt-2
            p.float-left.font-bold.mr-2(class="w-2/12") Español: 
            .shadow.w-full.bg-gray-500(class="10/12")
              .bg-blue.text-xs.leading-none.py-1.text-center.text-white.bg-blue-500(style="width: 100%") Nativo
      
        .mt-20.px-4(class="lg:w-1/2")
        h3.border-b.border-gray-600.font-bold.mb-5.text-3xl.text-blue-600.text-center(class="lg:text-4xl") Skills
        
        h4.text-2xl.font-bold.mb-2 Stack dev presente
        ul
          li.mr-2.mb-4.inline-block: a(href="https://htmlreference.io/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 HTML5
          li.mr-2.mb-4.inline-block: a(href="https://cssreference.io/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 CSS3
          li.mr-2.mb-4.inline-block: a(href="https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 JavaScript
          li.mr-2.mb-4.inline-block: a(href="https://es-vuejs.github.io/vuejs.org/v2/guide/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Vue.js
          li.mr-2.mb-4.inline-block: a(href="https://vuex.vuejs.org/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Vuex
          li.mr-2.mb-4.inline-block: a(href="http://nuxtjs.org/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Nuxt.js
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Pug
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Sass
          li.mr-2.mb-4.inline-block: a(href="https://nodejs.org/dist/latest-v12.x/docs/api/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Node
          li.mr-2.mb-4.inline-block: a(href="https://www.postgresql.org/docs/12/index.html").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Postgres
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Git
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Linux
          li.mr-2.mb-4.inline-block: a(href="https://firebase.google.com/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Firebase

        h4.text-2xl.font-bold.mb-2 Stack dev previo
        ul.inline-block
          li.mr-2.mb-4.inline-block: a(href="https://es.reactjs.org/tutorial/tutorial.html").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 React
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Redux
          li.mr-2.mb-4.inline-block: a(href="https://nextjs.org/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Next
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Stylus
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 jQuery
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Gulp
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Grunt
          li.mr-2.mb-4.inline-block: a(href="#").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 MySql
          li.mr-2.mb-4.inline-block: a(href="https://www.mongodb.com/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 Mongodb
          li.mr-2.mb-4.inline-block: a(href="https://strapi.io/").bg-blue-500.font-bold.rounded.text-white.py-2.px-4.mb-6 HeadlessCMS
</template>

<style>
.custom-list {
  list-style: none;
  padding-left: 1em;
}
.custom-list li::before {
  content: '\2022';
  color: #4299e1;
  font-weight: bold;
  display: inline-block;
  width: 1em;
  margin-left: -1em;
}
.svg-gray {
  fill: lightgray !important;
}
</style>
