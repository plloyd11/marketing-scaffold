<template>
  <Layout>
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <a href="https://gridsome.org/docs/images">
      <g-image
        alt="Example image"
        src="~/favicon.png"
        width="135"
      />
    </a>

    <h1 class="mt-8 font-bold text-3xl">
      Hello, world!
    </h1>

    <p class="mt-4">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores
    </p>

    <p class="mt-8">
      <a
        href="https://gridsome.org/docs/"
        target="_blank"
        rel="noopener"
        class="font-semibold mr-2 hover:underline"
      >Gridsome Docs</a>
      <a
        href="https://github.com/gridsome/gridsome"
        target="_blank"
        rel="noopener"
        class="font-semibold mr-2 hover:underline"
      >GitHub</a>
    </p>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>
