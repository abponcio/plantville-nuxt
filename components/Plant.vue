<template>
  <article class="column is-4">
    <nuxt-link :to="'plants/' + id">
      <div class="card">
        <div class="card-image">
            <figure class="image is-4by3">
            <img :src="thumbnail" :alt="title">
            </figure>
        </div>
        <div class="card-content">
          <div class="title">{{title}}</div>
          <div class="content">
            <div class="description" v-html="description"></div>
            <br>
            <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
          </div>
        </div>
      </div>
    </nuxt-link>
  </article>
</template>

<script>
export default {
  props: {
    id: Number,
    thumbnail: {
      type: String,
      default: 'https://bulma.io/images/placeholders/1280x960.png'
    },
    title: String,
    description: String,
  }
}
</script>

