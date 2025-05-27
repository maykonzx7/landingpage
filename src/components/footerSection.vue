<template>
  <footer class="footer">
    <div class="footer-content">
      <p>&copy; 2025 Monica Aragão - Todos os direitos reservados.</p>
      <ul class="footer-links">
        <li><a href="#produtos">Produtos</a></li>
        <li><a href="#lookbook">Lookbook</a></li>
        <li><a href="#sobre">Sobre nós</a></li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {}
</script>

<style scoped>
.footer {
  background-color: #1a1a1a;
  color: white;
  padding: 30px 20px;
  text-align: center;
}

.footer-content {
  max-width: 1000px;
  margin: auto;
}

.footer-links {
  list-style: none;
  padding: 0;
  margin-top: 15px;
  display: flex;
  justify-content: center;
  gap: 20px;
}

.footer-links a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.footer-links a:hover {
  text-decoration: underline;
}
</style> s