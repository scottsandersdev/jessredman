<template>
  <section class="homepage">
    <nav>
      <ul class="homepage-nav">
        <li class="homepage-link--sunflower">
          <img class="homepage-link__image--sunflower" src="~assets/sunflower.png" alt="">
          <p class="homepage-link--text">About Me</p>
        </li>
        <li class="homepage-link--book">
          <img class="homepage-link__image--book" src="~assets/book.png" alt="">
          <p class="homepage-link--text">Books</p>
        </li>
        <li class="homepage-link">
          <img class="homepage-link__image" src="~assets/bicycle.png" alt="">
          <p class="homepage-link--text">Author Visits</p>
        </li>
        <!-- <li class="homepage-link">
          <img class="homepage-link__image" src="~assets/spyglass.png" alt="">
          <p class="homepage-link--text">News/Media</p>
        </li>
        <li class="homepage-link">
          <img class="homepage-link__image" src="~assets/robin.png" alt="">
          <p class="homepage-link--text">Contact</p>
        </li>
        <li class="homepage-link">
          <img class="homepage-link__image" src="~assets/lantern.png" alt="">
          <p class="homepage-link--text">For Educators</p>
        </li>
        <li class="homepage-link">
          <img class="homepage-link__image" src="~assets/umbrella.png" alt="">
          <p class="homepage-link--text">Blog</p>
        </li>
        <li class="homepage-link">
          <img class="homepage-link__image" src="~assets/bee.png" alt="">
          <p class="homepage-link--text">Events</p>
        </li>
        <li class="homepage-link">
          <img class="homepage-link__image" src="~assets/pinwheel.png" alt="">
          <p class="homepage-link--text">For Readers</p>
        </li> -->
      </ul>
    </nav>
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
.homepage {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.homepage-nav {
  display: flex;
  flex-wrap: wrap;
  max-width: 1000px;
}

.homepage-link__image {
  width: 100px;
}

.test{
  cursor: pointer;
}

.homepage-link__image--sunflower {
  width: 200px;
}

.homepage-link--book {
  align-self: flex-end;
  margin: 0 200px;
}

.homepage-link__image--book {
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

