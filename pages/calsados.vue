<template>
  <div class="navegacao">
    <p><NuxtLink class="navegacao" to="/">Início</NuxtLink> > Calsados</p>

    <div class="tipo">
      <h1>Tipo e tamanho dos calsados disponiveis.</h1>
      <b-table striped hover :items="calsados"></b-table>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      calsados: [
        { Tamanho: 40, Modelo: "Chinelo", Cor: "Rosa" },
        { Tamanho: 21, Modelo: "Salto-Alto", Cor: "Vermelho" },
        { Tamanho: 39, Modelo: "Sapatilha", Cor: "Branco" },
        { Tamanho: 38, Modelo: "Tênis", Cor: "Branco" },
        { Tamanho: 42, Modelo: "Sapatilha", Cor: "Preto" },
        { Tamanho: 37, Modelo: "Bota", Cor: "Marrom" },
        { Tamanho: 36, Modelo: "Chinelo", Cor: "Verde" },
        { Tamanho: 35, Modelo: "Salto-Alto", Cor: "Preto" },
      ],
    };
  },
};
</script>