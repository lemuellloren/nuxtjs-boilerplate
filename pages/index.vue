<template>
  <div class="container">
    <section>
      <h1 class="title">
        {{ name }}
      </h1>
      <h2 class="subtitle">
        Leet Front-end boilerplate using vueJS Framework
      </h2>
    </section>
    <section class="desc">
      <div>
        <p>
          Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
          industry's
          standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to
          make a type specimen book. It has survived not only five centuries, but also the leap into electronic
          typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset
          sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus
          PageMaker
          including versions of Lorem Ipsum
        </p>
      </div>
    </section>
  </div>
</template>


<style lang="scss">
//import global scss
@import '@/assets/scss/main.scss';

.container {
  text-align: center;

  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system,
      BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial,
      sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: $red;
    letter-spacing: 1px;
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

<script>
export default {
  data() {
    return {
      name: 'Hello World'
    }
  }
}
</script>
