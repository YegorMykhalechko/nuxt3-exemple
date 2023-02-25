<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Project Name</NuxtLink>
        <ul>
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products">Products</NuxtLink>
          </li>
        </ul>
        <a href="/about">normal link</a>
      </nav>
    </header>
    <h2>Home</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem, accusantium
      repellat minus cum iusto quisquam totam consequuntur enim assumenda
      cupiditate ipsam temporibus veniam voluptatem provident perspiciatis!
      Explicabo voluptatem ab ratione.
    </p>
  </div>
</template>

<script setup></script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
