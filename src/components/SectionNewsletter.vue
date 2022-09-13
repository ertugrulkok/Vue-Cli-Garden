<template>
  <section class="newsletter">
    <div class="newsletter-wrapper">
      <div class="newsletter-content">
        <h1 class="hero-title-secondary">
          Subscribe to Our Newsletter For Weekly Article Update.
        </h1>
        <p class="blog-text">
          We have gardening-related blog so we can share our thought and
          rutinity in our blog that updated weekly. We will not spam you, we
          promise.
        </p>
        <div class="input-wrapper">
          <div class="col-8">
            <label class="visually-hidden" for="inlineFormInputGroupUsername"
              >Username</label
            >
            <div class="input-group">
              <div class="input-group-text">
                <i class="fa-regular fa-envelope"></i>
              </div>
              <input
                type="email"
                class="form-control"
                id="inlineFormInputGroupUsername"
                placeholder="Enter your e-mail address"
              />
            </div>
          </div>
          <button class="btn btn-primary">Subscribe</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.newsletter-wrapper {
  background-color: #136b5f;
  max-width: 1264px;
  margin: auto;
  text-align: center;
  padding: 70px 0;
  border-radius: 40px;
}

.newsletter-content {
  max-width: 700px;
  margin: auto;
}
.hero-title-secondary {
  color: #fff;

  margin: auto;
  font-size: 50px;
  margin-bottom: 27px;
}

.blog-text {
  color: #fff;
  text-align: center;
  margin: auto;
  padding: 0 4rem;
}

.input-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 1rem;
  margin-top: 2rem;
}

.input-group {
  max-width: 468px;
}

.input-group input {
  color: #a0c4bf;
}

.form-control {
  background-color: #42897f;
  border: none;
  border-radius: 34px;
  padding: 1rem;
}

.form-control::placeholder {
  color: #a0c4bf;
}
.form-control:focus {
  background-color: #42897f;
}

.input-group-text {
  background: #42897f;
  border: none;
  border-radius: 34px;
  font-size: 30px;
  color: #fff;
  padding-left: 2rem;
}
</style>
