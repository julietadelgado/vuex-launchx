<template>
    <div class="botones">
      <button @click="$store.dispatch('bajarContador')">-</button> <!-- $store.commit('bajarContador') para las mutaciones -->
      <button @click="$store.dispatch('subirContador')">+</button>
    </div>
</template>

<script>
export default {
  name: 'Botones',
}
</script>