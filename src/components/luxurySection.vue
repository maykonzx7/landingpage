<template>
  <section class="luxury" id="luxury">
    <div class="content">
      <div class="text">
        <h2>Brilho, Luxo <br />Exclusividade</h2>
        <p>
          Cada peça é desenhada para destacar a beleza única de quem a usa. Use nossas joias como
          uma forma de expressão, poder e sofisticação.
        </p>
      </div>
      <div class="images">
        <img src="https://via.placeholder.com/180x180?text=Joia+1" alt="Joia 1" />
        <img src="https://via.placeholder.com/180x180?text=Joia+2" alt="Joia 2" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'LuxurySection'
}
</script>

<style scoped>
.luxury {
  padding: 60px;
  background-color: #f8f8f8;
}

.content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
  align-items: center;
  justify-content: space-between;
}

.text {
  flex: 1;
  min-width: 300px;
}

.text h2 {
  font-size: 36px;
  margin-bottom: 20px;
  color: #333;
}

.text p {
  font-size: 18px;
  line-height: 1.6;
  color: #666;
}

.images {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.images img {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.images img:hover {
  transform: scale(1.05);
}
</style>

<style scoped>
.luxury {
  padding: 60px;
  background-color: #f5f5f5;
}

.content {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  gap: 40px;
}

.text {
  max-width: 400px;
}

.text h2 {
  font-size: 32px;
  margin-bottom: 16px;
  color: #000;
}

.text p {
  font-size: 18px;
  color: #333;
  line-height: 1.5;
}

.images {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.images img {
  width: 180px;
  height: 180px;
  border-radius: 10px;
  object-fit: cover;
  box-shadow: 0 0 10px #ccc;
}
</style>