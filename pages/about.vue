<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem, accusantium
      repellat minus cum iusto quisquam totam consequuntur enim assumenda
      cupiditate ipsam temporibus veniam voluptatem provident perspiciatis!
      Explicabo voluptatem ab ratione.
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
const { data } = await useFetch("/api/currency/EUR");
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
