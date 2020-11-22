<template>
  <div>
    <div class="navegacao">
      <p><NuxtLink class="navegacao" to="/">Início</NuxtLink> > Audio</p>
    </div>
    <h1>Audios persinalidados.</h1>
    <b-table striped hover :items="meia"></b-table>
    <p>Mais que 5 minutos, entrar em contado por E-mail</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      meia: [
        { Duração: 1, tamanho: "minutos", Cor: "Rosa" },
        { Duração: 2, tamanho: "minutos", Cor: "Vermelho" },
        { Duração: 3, tamanho: "minutos", Cor: "Branco" },
        { Duração: 4, tamanho: "minutos", Cor: "Branco" },
        { Duração: 5, tamanho: "minutos", Cor: "Preto" },
      ],
    };
  },
};
</script>