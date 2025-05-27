<template>
  <section class="products" id="products">
    <h2>Nossa Coleção</h2>
    <div class="products-grid">
      <div class="product-card" v-for="(produto, index) in produtos" :key="index">
        <img :src="produto.imagem" :alt="produto.nome">
        <h3>{{ produto.nome }}</h3>
        <p class="price">R$ {{ produto.preco }}</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProductsSection',
  data() {
    return {
      produtos: [
        { nome: 'Anel de Diamante', preco: '2.999,00', imagem: 'https://via.placeholder.com/200x200?text=Anel' },
        { nome: 'Colar de Pérolas', preco: '1.899,00', imagem: 'https://via.placeholder.com/200x200?text=Colar' },
        { nome: 'Brincos de Ouro', preco: '999,00', imagem: 'https://via.placeholder.com/200x200?text=Brincos' },
        { nome: 'Pulseira de Prata', preco: '599,00', imagem: 'https://via.placeholder.com/200x200?text=Pulseira' },]
    }
  }
}
</script>

<style scoped>
.products {
  padding: 60px 20px;
  background-color: #fff;
}

h2 {
  text-align: center;
  font-size: 36px;
  margin-bottom: 40px;
  color: #333;
}

.products-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
  max-width: 1200px;
  margin: 0 auto;
}

.product-card {
  text-align: center;
  padding: 20px;
  border-radius: 10px;
  background-color: #fff;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.product-card:hover {
  transform: translateY(-5px);
}

.product-card img {
  width: 100%;
  max-width: 200px;
  height: auto;
  border-radius: 8px;
  margin-bottom: 15px;
}

.product-card h3 {
  font-size: 20px;
  margin: 10px 0;
  color: #333;
}

.price {
  font-size: 18px;
  color: #666;
  font-weight: bold;
}
</style>