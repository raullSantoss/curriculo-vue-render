<script setup>

</script>

<template>
    <section class="fade-in fade-delay-4" aria-labelledby="contact-title">
    <h2 id="contact-title">Contato</h2>
    <p>Telefone:</p>
    <a class="contact-button" href="tel:+5519998532744" aria-label="Ligar para Raul Toffoletto dos Santos">+55 19 99853-2744</a>
  </section>
</template>

<style scoped>
    h2 {
  font-size: 1.6rem;
  color: #90caf9;
  border-bottom: 2px solid #90caf9;
  padding-bottom: 0.25rem;
  margin-top: 2rem;
}
p {
  font-weight: 300;
  font-size: 1rem;
  line-height: 1.5;
  margin-bottom: 0.8rem;
}
.contact-button {
  margin-top: 1.5rem;
  display: inline-block;
  background: #4dabf5;
  color: #142850;
  font-weight: 700;
  text-decoration: none;
  padding: 0.75rem 1.5rem;
  border-radius: 8px;
  box-shadow: 0 3px 10px rgba(38, 132, 255, 0.6);
  transition: background 0.3s ease;
}
.contact-button:hover {
  background: #1976d2;
  color: #e3f2fd;
}
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s forwards;
}
.fade-delay-4 {
  animation-delay: 1s;
}
@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>