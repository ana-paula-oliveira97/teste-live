<template>
  <div class="tipo">
    <div class="navegacao">
      <p><NuxtLink class="navegacao" to="/">Início</NuxtLink> > Meias</p>
      <h1>Tipo e tamanho das meias disponiveis.</h1>
      <b-table striped hover :items="meia"></b-table>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      meia: [
        { Tamanho: 0, Modelo: "Meia-calça", Cor: "Rosa" },
        { Tamanho: 21, Modelo: "3/4", Cor: "Vermelho" },
        { Tamanho: 39, Modelo: "neylon", Cor: "Branco" },
        { Tamanho: 38, Modelo: "Algoodão", Cor: "Branco" },
        { Tamanho: 42, Modelo: "Sapatilha", Cor: "Preto" },
        { Tamanho: 0, Modelo: "Meia arrastão", Cor: "Marrom" },
        { Tamanho: 36, Modelo: "Chinelo", Cor: "Verde" },
        { Tamanho: 0, Modelo: "Meia arrastão", Cor: "Preto" },
      ],
    };
  },
};
</script>