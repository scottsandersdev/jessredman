<template>
  <section class="container">
    <div>
      <img class="book-cover" src="~/assets/miraculous.jpeg" alt="Book cover of Miraculous by Jessica Redman">
      <h1 class="title">Jessica Redman</h1>
      <div class="links">
        <a href="https://twitter.com/jess__red?lang=en" target="_blank" class="button--green">Twitter</a>
        <a href="https://www.goodreads.com/book/show/35650630-the-miraculous" target="_blank" class="button--green">Goodreads</a>
      </div>
    </div>
  </section>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.book-cover {
  width: 350px;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

