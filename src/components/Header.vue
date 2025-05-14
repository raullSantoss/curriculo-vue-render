<script setup>

</script>

<template>
  <h1 class="fade-in">Raul Toffoletto dos Santos</h1>
</template>

<style scoped>
    h1 {
  font-size: 2.4rem;
  color: #bbe1fa;
  text-align: center;
  margin-bottom: 1rem;
  text-shadow: 1px 1px 6px #1565c0;
}
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s forwards;
}
@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
@media (max-width: 480px) {
  h1 {
    font-size: 2rem;
  }
}
</style>