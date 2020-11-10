<template>
  <div>
    <p></p>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        caption="Promoção de black friday"
        text="Todo mês de Novembro o pack god esta R$ 59,99"
        img-src="~/assets/img/banner 2.jpg"
      ></b-carousel-slide>

      <!-- Slide with blank fluid image to maintain slide aspect ratio -->
      <b-carousel-slide
        caption="Conheça nossos varios packs !"
        text="Fotos e videos com a forma de pagamendo que melhor se encaixar no seu
          orçamento. Parcelando em ate 5X sem juros no cartão."
        img-src="~/assets/img/banner 3.jpg"
      ></b-carousel-slide>
    </b-carousel>

    <p class="mt-4"></p>
    <div>
      <b-card-group>
        <b-card
          title="Pack de fotos de Pé"
          img-src="~/assets/img/pe-pena.jpg"
          img-alt="Image"
          img-top
        >
          <b-card-text>
            Com varios categorias de packs, do básico ao mais avançado.<br />
            Alem de imagens contamos ainda em alguns packs vídeos com a
            Possibilidade de escolha do cliente.
          </b-card-text>
          <template #footer>
            <b-button variant="outline-success"
              ><NuxtLink to="/pack-pe">Mais informações</NuxtLink></b-button
            >
          </template>
        </b-card>

        <b-card
          title="Calsados usados"
          img-src="~/assets/img/sapato 3.jpg"
          img-alt="Image"
          img-top
        >
          <b-card-text>
            Com sapatos usados pelas modelos das fotos, pode-se adquirir
            qualquer um, ou fazer seu pedido especial com modelo e tamanho.
          </b-card-text>
          <template #footer>
            <b-button variant="outline-success"
              ><NuxtLink to="/calsados">Mais informações</NuxtLink></b-button
            >
          </template>
        </b-card>

        <b-card
          title="Meias usadas"
          img-src="~/assets/img/meia 4.jpg"
          img-alt="Image"
          img-top
        >
          <b-card-text>
            Assim como os calçados, as meias estão disponíveis, contando com
            vários modelos e tamanhos, o cliente podendo fazer uma encomenda
            especial.
          </b-card-text>
          <template #footer>
            <b-button variant="outline-success"
              ><NuxtLink to="/meias">Mais informações</NuxtLink></b-button
            >
          </template>
        </b-card>
      </b-card-group>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
};
</script>