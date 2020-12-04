<template>
  <div>
    <div>
      <div class="navegacao">
        <p><NuxtLink class="navegacao" to="/">Início</NuxtLink> > Pack</p>
        <div class="mt-4">
          <h4>Nossos Packs disponiveis.</h4>
        </div>
      </div>
      <div class="pes">
        <b-card-group deck>
          <b-card
            title="Pack Padrão"
            img-src="~/assets/img/pe 300.jpg"
            img-alt="Image"
            img-top
          >
            <b-card-text>
              Esse pack possui 10 fotos com posições deveras.<br />
              Com R$14,99 pode escolher as posições e a cor do esmalte.
            </b-card-text>
          </b-card>

          <b-card
            title="Pack Good"
            img-src="~/assets/img/pe-e-mao 300.jpg"
            img-alt="Image"
            img-top
          >
            <b-card-text>
              Esse pack possui 14 fotos com posições deveras.<br />
              Com R$14,99 pode escolher as posições e a cor do esmalte e a
              modelo de sua preferencia.
            </b-card-text>
          </b-card>

          <b-card
            title="Pack Diamante"
            img-src="~/assets/img/pe-e-perna 300.jpg"
            img-alt="Image"
            img-top
          >
            <b-card-text>
              Esse pack possui 20 fotos com posições deveras.<br />
              Com R$14,99 pode escolher as posições e a cor do esmalte e a
              modelo de sua preferencia.
            </b-card-text>
          </b-card>
          <b-card
            title="Pack Platinum"
            img-src="~/assets/img/pe-e-flores 300.jpg"
            img-alt="Image"
            img-top
          >
            <b-card-text>
              Esse pack possui 25 fotos com posições deveras.<br />
              Com R$14,99 pode escolher as posições e a cor do esmalte e a
              modelo de sua preferencia e um video curto de 1 á 3 minutos com um
              brinde aleatorio.
            </b-card-text>
          </b-card>
          <b-card
            title="Pack Supremo"
            img-src="~/assets/img/pe-cobra 300.jpg"
            img-alt="Image"
            img-top
          >
            <b-card-text>
              Esse pack possui 30 fotos com posições deveras.<br />
              Com R$14,99 pode escolher as posições e a cor do esmalte e a
              modelo de sua preferencia e um video curto de até 5 minutos com 2
              brindes surpresa .
            </b-card-text>
          </b-card>
        </b-card-group>
      </div>
    </div>
  </div>
</template>