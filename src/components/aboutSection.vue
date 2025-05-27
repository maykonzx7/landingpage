<template>
  <section class="about" id="sobre">
    <div class="container">
      <h2>Sobre nós</h2>
      <div class="content">
        <div class="text">
          <h3>Nossa missão</h3>
          <p>
            Trazer beleza, sofisticação e autenticidade através de joias exclusivas feitas com amor e dedicação.
          </p>
          <h3>Nossa história</h3>
          <p>
            Fundada por apaixonados por moda e design, nossa marca nasceu com o propósito de valorizar a essência de cada pessoa.
          </p>
        </div>
        <div class="image">
          <img src="https://via.placeholder.com/400x300?text=Sobre+nos" alt="Sobre nós" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.about {
  padding: 60px 20px;
  background-color: #fff7f0;
  color: #333;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
}

.about h2 {
  text-align: center;
  font-size: 36px;
  margin-bottom: 40px;
}

.content {
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
  align-items: center;
  justify-content: space-between;
}

.text {
  flex: 1;
}

.text h3 {
  font-size: 22px;
  margin: 20px 0 10px;
}

.text p {
  font-size: 16px;
  line-height: 1.6;
}

.image img {
  max-width: 100%;
  border-radius: 10px;
  box-shadow: 0 0 10px #ccc;
}
</style>