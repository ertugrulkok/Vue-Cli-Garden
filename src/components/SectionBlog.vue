<template>
  <section>
    <div class="container">
      <h1 class="hero-title-secondary">Best Curated Gardening Article</h1>
      <div class="blog-wrapper grid">
        <div class="colblog">
          <!-- card 1 -->
          <div class="blog-card">
            <img
              class="blog-image blog-big-image"
              src="@/assets/image1.jpeg"
              alt=""
            />
            <div class="blog-bottom">
              <h3 class="blog-title">
                Best Plants That Kids Friendly in 2021, How Much do You Own?
              </h3>
              <p class="blog-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet,
                consectetur <a class="read-more" href="#"> Read More</a>
              </p>
            </div>
          </div>
        </div>
        <div class="colblog blog-card-right">
          <!-- card 2 -->
          <div class="blog-card flex">
            <img class="blog-image" src="@/assets/image1.jpeg" alt="" />
            <div class="blog-bottom">
              <h3 class="blog-title">
                Best Plants That Kids Friendly in 2021, How Much do You Own?
              </h3>
              <p class="blog-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet,
                consectetur <a class="read-more" href="#"> Read More</a>
              </p>
            </div>
          </div>
          <!-- card 3 -->
          <div class="blog-card flex">
            <img class="blog-image" src="@/assets/image1.jpeg" alt="" />
            <div class="blog-bottom">
              <h3 class="blog-title">
                Best Plants That Kids Friendly in 2021, How Much do You Own?
              </h3>
              <p class="blog-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet,
                consectetur <a class="read-more" href="#"> Read More</a>
              </p>
            </div>
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
.hero-title-secondary {
  margin-bottom: 5rem;
}

.blog-wrapper {
  grid-template-columns: 1fr 2fr;
}

.blog-card {
  background-color: #fff;
  padding: 1.3rem;
  border-radius: 30px;
  box-shadow: 0px 4px 120px rgba(89, 113, 105, 0.06);
}

.blog-image {
  border-radius: inherit;
  width: 220px;
  object-fit: cover;
  object-position: top;
}

.blog-big-image {
  width: 100%;
  height: 220px;
}

.hero-title-secondary {
  text-align: center;
}

.blog-card-right {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
</style>
