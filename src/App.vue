<script setup>
</script>

<template>
  <section>
    <a href="https://double-image.vercel.app/" target="_blank">2 Render Target (Video & Image)</a><br>
    <a href="https://mihairazvan.vercel.app/" target="_blank">Geometry distortion & RGB Shift & Post Processing Effect</a><br>
    <a href="https://homepage-ten-tawny.vercel.app/" target="_blank">Simple Game</a><br>
    <a href="https://vercel.com/mihairazvan9/pixel-distortion" target="_blank">Pixel distortion</a><br>
    <a href="https://particle-zoom.vercel.app/" target="_blank">Image distortion to particle</a><br>
    <a href="https://particle-wave.vercel.app/" target="_blank">Image particle wave</a><br>
    <a href="https://test-webxr.vercel.app/" target="_blank">Augment Reality</a><br>
  </section>
</template>

<style lang="scss">
  body {
    background: #151518;
  }

  section {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;
    background: #151518;

    a {
      text-decoration: none;
      font-size: 20px;
      font-weight: 600;
      color: #fff;

      &:hover {
        color: #4ed5d5;
      }
    }
  }
</style>
