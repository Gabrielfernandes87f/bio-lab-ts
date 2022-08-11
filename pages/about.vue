<template>
  <div class="about-body">
    <div class="about-main">
      <div class="block">
        // About
        <h1>Gabriel Fernandes</h1>

        <p class="">
          Meu nome é Gabriel Fernandes, desenvolvedor web. Por meio desta
          pagina, gostaria de manifestar o meu interesse pelo cargo de
          desenvolvedor front-end ou full stack com Laravel ou Nuxt.js, também
          estou aberto para aprender novas stacks.
        </p>
        <ul>
          <p class="bold">Desenvolvedor full stack web</p>
          <p class="bold color-bold">Stack:</p>
          <li>
            Web: HTML, CSS, JavaScript,ECMAScript, PHP, Laravel, Vue.jS, NuxtJs,
            Scss, Tailwind, Bootstrap; - Banco de Dados: MySQL, SQL; -
            Versionamento: Git, GitHub, bitbucket;
          </li>
        </ul>
        <ul>
          <p class="bold color-bold">DevOps:</p>
          <li>Github: GitPages,</li>
          <li>Vercel: Next.js, Nuxt.js</li>
          <li>Digital Ocean: Docker, Laravel, MySQL, Jetstream</li>
          <li>Hosting: WordPress, Laravel</li>
          <li>Heroku: Nuxt.js</li>
        </ul>
        <p class="bold">
          Atualmente Melhorando minhas habilidades em - Nuxt - Scss - SQL - API
          - adonis - typescript - Vuex
        </p>
        <p class="color-bold">Skils:</p>
        <p>
          CSS3, HTML5. Javascript, MySQL, Linux, Docker, Bootstrap, Tailwind,
          Laravel, Stripe, Git e Github, Git Workflow, Nuxt.js
        </p>
        <p>
          Gostaria de destacar alguns pontos em minha trajetória profissional
          que poderão ser de seu interesse:
        </p>
        <ul>
          <li>
            Meu amplo conhecimento e experiência nas áreas de front-end,
            back-end e devOps, possibilitam meu domínio em programar, refaturar
            e fazer o deploy da aplicação.
          </li>
          <br />
          <li>
            Estou sempre buscando melhorar meus conhecimentos como
            desenvolvedor, estudando Scss, Api, Adonis.js, NuxtJs, typescript
          </li>
        </ul>
        <div>
          <div class="card-template">
            <CardDownloads>
              <p class="btn-curriculo">Baixar Currículo</p>
            </CardDownloads>
          </div>
          <div class="card-template">
            <CardLink to="/">
              <p class="btn-voltar">Voltar</p>
            </CardLink>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import CardLink from '~/components/CardLink.vue'

export default defineComponent({
  data() {
    return {
      //
    }
  },
  components: { CardLink },
})
</script>
