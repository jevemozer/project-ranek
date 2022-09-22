<template>
  <header>
    <nav>
      <router-link to="/" class="logo">
        <img src="@/assets/ranek.svg" alt="ranek" />
      </router-link>
      <router-link to="/Login">Vender / Login</router-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: "TheHeader",
};
</script>

<style scoped></style>
