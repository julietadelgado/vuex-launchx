<template>
    <div class="exponencial">
      {{$store.state.contador }} <sup>2</sup> = {{ $store.getters.cuadrado }}
    </div>
</template>

<script>
export default {
  name: 'Exponente',
}
</script>