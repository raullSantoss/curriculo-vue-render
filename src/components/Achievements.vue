<script setup>

</script>

<template>
    <section class="fade-in fade-delay-3" aria-labelledby="achievements-title">
    <h2 id="achievements-title">Conquistas</h2>
    <p>Medalha de bronze na Olimpíadas de Matemática</p>
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
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s forwards;
}
.fade-delay-3 {
  animation-delay: 0.75s;
}
@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>