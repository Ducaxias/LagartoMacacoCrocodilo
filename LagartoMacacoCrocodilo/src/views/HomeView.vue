<script setup lang="ts">
import SaibaMais from "../components/SaibaMais.vue"
</script>

<template>
  <main>
    <section id="Inicio">
      <article class="compose">
        <div class="card">
          <h1>Clovis</h1>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Pariatur eius ratione saepe fuga impedit 
            similique! Unde veritatis corporis esse labore, quam aspernatur dolor quibusdam, aliquid vitae 
            inventore maxime blanditiis non?</p>
        </div>
        <div class="parallax"></div>
      </article>
    </section>
    <section id="Galeria">
      <h3>Galeria</h3>
      <div class="Galeria">
        <figure class="item_galeria">
          <img src="" alt="">
        </figure>
        <figure class="item_galeria">
          <img src="" alt="">
        </figure>
        <figure class="item_galeria">
          <img src="" alt="" srcset="">
        </figure>
        <figure class="item_galeria">
          <img src="" alt="">
        </figure>
        <figure class="item_galeria">
          <img src="" alt="">
        </figure>
        <figure class="item_galeria">
          <img src="" alt="">
        </figure>
      </div>
    </section>
    <section id="Exposições">
      <article>
        <h3>Exposições</h3>
        <p>A exposição Nova Era apresenta uma coleção diversificada de obras de arte de 
          renomados artistas contemporâneos e talentosos artistas emergentes. Das pinturas aos esculturas, 
          das instalações às fotografias, esta exposição oferece uma visão abrangente das diferentes formas 
          de expressão artística.</p>
        <div class="banner">
          <img src="" alt="Banner da exposição">
        </div>
      </article>
    </section>
    <section class="Workshops" id="Workshops">
      <h3>Workshops</h3>
      <article class="cardWorkshops">
          <div class="card">
            <h4 class="">A arte contemporânea na vida das pessoas</h4>
            <p class="description">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Excepturi hic aliquid iste 
              explicabo, culpa, atque voluptates tenetur dolorum nisi amet illum voluptatibus expedita nulla 
              magni quis laborum necessitatibus eius voluptas.</p>
            <SaibaMais/>
          </div>
          <div class="card">
            <h4 class="">Esculturas em argila e madeira(entalhe)</h4>
            <p class="description">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Molestiae adipisci 
              deleniti, fugiat expedita asperiores ratione et quas aspernatur voluptatum alias, 
              perspiciatis perferendis. Nesciunt iusto, ab nam labore deserunt fugiat necessitatibus!</p>
            <SaibaMais/>
          </div>
          <div class="card">
            <h4>Diferentes formas de arte e como elas agregam a sociedade</h4>
            <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Error esse illo 
              nam odio nihil id eum saepe incidunt! Molestias esse iusto odit assumenda repudiandae quasi
               quos nesciunt atque possimus excepturi.</p>
            <SaibaMais/>
          </div>
      </article>
    </section>
  </main>
</template>
