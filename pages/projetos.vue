<template>
  <div>
    <div class="bg-image-container">
      <img class="bg-projeto" src="projetos.png" width="100%" height="100%" />
    </div>
    <div class="center-div content-main">
      <p>
        Apresentando alguns dos meus principais projetos. clique na image para
        ser direcionado ate o repositório ou site da aplicação
      </p>
    </div>

    <div class="card-body-fist">
      <div class="card-template">
        <CardIndex href="https://gabrielfernandes87f.github.io/my-pages/">
          <div class="card-main">
            <div>
              <div class="bg-image-container">
                <img
                  class="bg-projeto img-projeto"
                  src="page.png"
                  width="400px"
                />
              </div>
              <p class="color-white">
                Lading page hospedada no Github. Aqui coloquei meus
                certificados, currículo, e falei um pouco mais sobre minha
                trajetória profissional. Feito apenas com html, css e javascript
              </p>
            </div>
          </div>
        </CardIndex>
      </div>

      <div class="card-template">
        <CardIndex href="https://next-api-liard.vercel.app/">
          <div class="card-main">
            <div>
              <div class="bg-image-container">
                <img
                  class="bg-projeto img-projeto"
                  src="api.png"
                  width="400px"
                />
              </div>
              <p class="color-white">
                Projetinho consumindo uma api do Github feito com NextJs e
                hospedado na Vercel.
              </p>
            </div>
          </div>
        </CardIndex>
      </div>

      <div class="card-template">
        <CardIndex href="https://http://142.93.127.99:8080">
          <div class="card-main">
            <div>
              <div class="bg-image-container">
                <img
                  class="bg-projeto img-projeto"
                  src="fotos.png"
                  width="400px"
                />
              </div>
              <p class="color-white">
                Site de fotografia, sempre foi um sonho ter um site onde eu
                pudesse colocar as minhas fotos. Trabalhei muito anos como
                fotógrafo profissional, aqui você vai conhecer um pouco do meu
                de Gabriel fotógrafo. Esse site foi feito em Laravel com Docker
                e hospedei ele na Digital Ocean. O navegador informa que esse
                site não é seguro porque ele não tem o certificado ssl. Não
                coloquei ainda, não tenho domínio pra usar aqui.
              </p>
            </div>
          </div>
        </CardIndex>
      </div>

      <div class="card-template">
        <CardIndex href="https://github.com/Gabrielfernandes87f/patins">
          <div class="card-main">
            <div>
              <div class="bg-image-container">
                <img
                  class="bg-projeto img-projeto"
                  src="patins.png"
                  width="400px"
                />
              </div>
              <p class="color-white patins">
                Eu ja tenho 5 anos que ando de patins, pensando em juntar mais
                pessoas pra andar na minha cidade, resolvi criar um site. Esse
                site eu tinha feito o deploy dele na Digital Ocean, mas passou
                um tempo e não conseguir pessoas para colaborar, tirei do ar.  O
                projeto Turma do patins tinha sistema de login feito com
                Jetstream, usuário poderia fazer publicações falando lugar onde
                ia andar, publicar eventos e confirmar presença no eventos dos
                outros patinadores, tinha um filtro mostrando quem confirmou
                presença. Site Laravel com Docker, fácil de clonar e testar.
              </p>
            </div>
          </div>
        </CardIndex>
      </div>

      <div class="card-template">
        <CardLink to="/">
          <p class="btn-voltar">Voltar</p>
        </CardLink>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import CardIndex from '~/components/CardIndex.vue'
import CardLink from '~/components/CardLink.vue'

export default Vue.extend({
  name: 'IndexPage',
  data() {
    return {}
  },
  components: {
    CardIndex,
    CardLink,
  },
})
</script>
