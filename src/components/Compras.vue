<template>
  <div>
    <v-card v-if="open">uugvvhc</v-card>
    <v-card v-else @click="abertura">fecjadfolkjhgchjklç</v-card>

    <v-btn v-if="!open" @click="abertura()">abrir card</v-btn>
    <v-btn v-else @click="fechamento()">fechar card</v-btn>
  </div>
</template>

<script>
export default {
  name: 'Compras',

  data: () => ({
    open: false,
  }),
  methods: {
    abertura() {
      this.open = true;
    },
    fechamento() {
      this.open = false;
    }

  }


}
</script>
