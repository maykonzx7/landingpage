<template>
  <header class="header">
    <nav>
      <h1>RIRI</h1>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#lookbook">Lookbook</a></li>
        <li><a href="#about">About</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderSection'
}
</script>

<style scoped>
.header {
  padding: 1rem;
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
}

ul {
  display: flex;
  list-style: none;
  gap: 2rem;
}

a {
  text-decoration: none;
  color: #333;
}
</style>