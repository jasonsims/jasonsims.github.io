<script setup></script>

<template>
  <div class="page-home">
    <div class="hero-unit">
      <h1>Trust the Nyan</h1>
      <img src="@/assets/nyan.gif" alt="Nyan Cat" class="nyan-cat-img" />
    </div>
    <div class="button-group">
      <button id="button1">Button 1</button>
      <button id="button2">Button 2</button>
      <button id="button3">Button 3</button>
    </div>
  </div>
</template>
<style scoped>
.nyan-cat-img {
  border: solid 4px var(--text-color);
  box-shadow:
    0 10px 20px rgba(0, 0, 0, 0.19),
    0 6px 6px rgba(0, 0, 0, 0.23);
}

.button-group {
  display: flex;
  gap: 10px;
}

button {
  background-color: var(--primary-color);
  padding: 8px 20px;
  border: solid 4px var(--text-color);
}
</style>
