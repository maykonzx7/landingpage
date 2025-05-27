<template>
  <section class="lookbook" id="lookbook">
    <div class="lookbook-content">
      <div class="text">
        <h2>LOOK BOOK</h2>
        <p>
          Explore o universo da joalheria e veja como nossas peças ganham vida com estilo,
          elegância e personalidade. Inspire-se com nossas composições exclusivas.
        </p>
      </div>
      <div class="image">
        <img src="https://via.placeholder.com/300x400?text=Lookbook" alt="Modelo com joias" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'LookbookSection'
}
</script>

<style scoped>
.lookbook {
  padding: 60px;
  background-color: #a26dd4;
  color: white;
}

.lookbook-content {
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
  align-items: center;
  justify-content: center;
}

.text {
  max-width: 500px;
}

.text h2 {
  font-size: 36px;
  margin-bottom: 20px;
}

.text p {
  font-size: 18px;
  line-height: 1.6;
}

.image img {
  border-radius: 10px;
  max-width: 100%;
  height: auto;
  box-shadow: 0 0 10px #00000044;
}
</style>