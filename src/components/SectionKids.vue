<template>
  <section>
    <div class="container">
      <div class="hero-wrapper grid">
        <div class="hero-image">
          <img src="@/assets/image2.jpeg" alt="" />
        </div>
        <div class="hero-text">
          <h1 class="hero-title-secondary">It’s Kids-Friendly Plants!</h1>
          <p class="hero-text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore.
          </p>
          <button class="btn btn-primary">Pre-Order Now</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.grid {
  /* grid-template-columns: 1fr 1fr; */
  grid-template-columns: repeat(auto-fit, minmax(220px, auto));
  gap: clamp(1rem, -0.6429rem + 10.7143vw, 9rem);
}
.hero-text {
  margin: 28px 0;
}
</style>
