<template>
  <section class="hero">
    <div class="text-content">
      <h1>MÔNICA ARAGÃO</h1>
      <p>Joias com brilho, luxo e exclusividade para realçar sua beleza única.</p>
      <button @click="irParaContato">Contato</button>
    </div>
    <div class="image-content">
      <img src="/hero.jpg" alt="Mulher usando joias" />
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    irParaContato() {
      document.getElementById('contact')?.scrollIntoView({ behavior: 'smooth' })
    }
  }
}
</script>

<style scoped>
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #f3f0f8;
  padding: 60px;
  flex-wrap: wrap;
}

.text-content {
  max-width: 500px;
}

h1 {
  font-size: 48px;
  color: #a26dd4;
}

p {
  margin-top: 15px;
  font-size: 18px;
  color: #333;
}

button {
  margin-top: 25px;
  padding: 12px 24px;
  font-size: 16px;
  background-color: #a26dd4;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.image-content img {
  max-width: 400px;
  border-radius: 10px;
}
</style>