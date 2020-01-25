<template>
  <div class="max-w-2xl mx-auto p-4">
    <header class="flex justify-between">
      <strong>
        <g-link
          class="font-semibold mr-2 hover:underline"
          to="/"
        >{{ $static.metadata.siteName }}</g-link>
      </strong>
      <nav class="nav">
        <g-link
          class="font-semibold mr-2 hover:underline"
          to="/"
        >
          Home
        </g-link>
        <g-link
          class="font-semibold mr-2 hover:underline"
          to="/about/"
        >
          About
        </g-link>
      </nav>
    </header>
    <main class="mt-8">
      <slot />
    </main>
  </div>
</template>

<static-query>
  query {
    metadata {
      siteName
    }
  }
</static-query>
