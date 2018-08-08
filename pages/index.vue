<template>
  <section class="container">
    <div>
      <img class="book-cover" src="~/assets/miraculous.jpeg" alt="Book cover of Miraculous by Jessica Redman">
      <h1 class="title">Jess Redman</h1>
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
  },
  head () {
    return {
      title: "Jessica Redman",
      meta: [
        { hid: 'description', name: 'description', content: 'Jessica Redman - author of Miraculous' }
      ]
    }
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
  width: 200px;
}

@media only screen and (min-width: 999px) {
    .book-cover {
      width: 300px;
    }
}


.title {
  color: #35495e;
  display: block;
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  font-size: 60px;
  font-weight: 300;
  letter-spacing: 1px;
  margin: 10px 0;
}

@media only screen and (min-width: 999px) {
    .title {
      font-size: 100px;
    }
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

