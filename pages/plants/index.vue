<template>
  <section class="section">
    <div class="container plant-list">
      <div class="columns is-mobile">
        <Plant 
          :id="1"
          title="Plant 1"
          description="Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Phasellus nec iaculis mauris. <a>@bulmaio</a>.
            <a href='#''>#css</a> <a href='#'>#responsive</a>"/>
      </div>
    </div>
  </section>
</template>

<script>
import Plant from '~/components/Plant.vue'

export default {
  components: {
    Plant
  }
}
</script>
