<script setup>

</script>

<template>
    <section class="fade-in fade-delay-2" aria-labelledby="skills-title">
    <h2 id="skills-title">Habilidades</h2>
    <ul class="info-list" role="list">
      <li>
        <svg viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2Zm1.12 14.54v1.89a1 1 0 0 1-2 0v-2.81a.5.5 0 0 1 .5-.5h.89a1 1 0 0 1 .61 1.42l-.61 1Zm.35-8a1.1 1.1 0 0 0-1.67 1.43l.33.41a.53.53 0 0 1-.1.7 2.92 2.92 0 0 0-.44.47 3.11 3.11 0 0 0 0 3l.15.23a.54.54 0 0 1-.1.7l-.42.4a1.11 1.11 0 0 0 1.67 1.43 3.9 3.9 0 0 0 1.43-2.1 3.37 3.37 0 0 0-.54-3 3.68 3.68 0 0 0-1.36-1.26Z"/>
        </svg>
        Inglês Intermediário
      </li>
    </ul>
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
.info-list {
  list-style: none;
  margin-top: 1rem;
  padding-left: 0;
}
.info-list li {
  margin-bottom: 1rem;
  font-weight: 500;
  font-size: 1.1rem;
  display: flex;
  align-items: center;
}
.info-list li svg {
  width: 20px;
  height: 20px;
  margin-right: 12px;
  fill: #90caf9;
  flex-shrink: 0;
}
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s forwards;
}
.fade-delay-2 {
  animation-delay: 0.5s;
}
@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>