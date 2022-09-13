<template>
  <section>
    <div class="container">
      <div class="title-container">
        <div class="hero-title-secondary">This is What Our Customers Said!</div>
        <button class="btn btn-primary">See All Testimonials</button>
      </div>
      <div class="testimonial-card-wrapper">
        <div class="card">
          <img class="tes-img" src="@/assets/tes.png" alt="" />
          <div class="card-content">
            <p class="testimonial-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet,
              consectetur
            </p>
            <p class="testimonial-name">Katie Simpson</p>
          </div>
        </div>
        <div class="card">
          <img class="tes-img" src="@/assets/tes.png" alt="" />
          <div class="card-content">
            <p class="testimonial-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet,
              consectetur
            </p>
            <p class="testimonial-name">Katie Simpson</p>
          </div>
        </div>
        <div class="card">
          <img class="tes-img" src="@/assets/tes.png" alt="" />
          <div class="card-content">
            <p class="testimonial-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet,
              consectetur
            </p>
            <p class="testimonial-name">Katie Simpson</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.title-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 80px;
}

.hero-title-secondary {
  max-width: 50%;
}

.testimonial-card-wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.card {
  max-width: 356px;
  padding: 52px 30px 30px 30px;
  position: relative;
  border: 0;
}

.tes-img {
  width: 53px;
  position: absolute;
  top: -25px;
  left: 21px;
}

.testimonial-text {
  font-weight: 400;
  font-size: 20px;
  line-height: 36px;
}

.testimonial-name {
  color: #136b5f;
  font-weight: 700;
  margin-top: 26px;
}
</style>
