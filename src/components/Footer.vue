<template>
  <footer class="mt-2 bg-teal-800">
    <div class="container flex justify-between py-12 mx-auto text-center">
      <h1>I'm a footer!</h1>
      <p>{{ $static.metadata.siteName }} is going to be so great!</p>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<static-query>
  query {
    metadata {
      siteName
    }
  }
</static-query>

<style>

.active {
  color: #f66;
}

</style>
