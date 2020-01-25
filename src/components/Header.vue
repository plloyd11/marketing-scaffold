<template>
  <header class="py-6 mb-6 shadow-md ">
    <div class="container flex justify-between mx-auto">
      <strong>
        <g-link
          class="mr-2 font-semibold hover:underline"
          exact
          to="/"
        >{{ $static.metadata.siteName }}</g-link>
      </strong>
      <nav class="nav">
        <g-link
          class="mr-2 font-semibold hover:underline"
          to="/about/"
        >
          About
        </g-link>
        <g-link
          class="mr-2 font-semibold hover:underline"
          to="/services/"
        >
          Services
        </g-link>
        <g-link
          class="mr-2 font-semibold hover:underline"
          to="/our-work/"
        >
          Our Work
        </g-link>
        <g-link
          class="mr-2 font-semibold hover:underline"
          to="/careers/"
        >
          Careers
        </g-link>
        <g-link
          class="mr-2 font-semibold hover:underline"
          to="/contact-us/"
        >
          Contact Us
        </g-link>
      </nav>
    </div>
  </header>
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
