<template>
  <Layout>
    <section class="container flex-grow mx-auto">
      <g-image
        alt="Hero Image"
        src="~/img/contact-us/hero.jpg"
        class="w-10/12 mx-auto"
      />
      <h1
        class="mt-8 text-3xl font-bold text-center"
      >
        Contact Us
      </h1>
    </section>
    <section class="flex justify-around mt-12 align-top">
      <div>
        <h3>This is going to be a great contact form! Use it!</h3>
      </div>
      <form class="w-full max-w-lg">
        <div class="flex flex-wrap mb-6 -mx-3">
          <div class="w-full px-3 mb-6 md:w-1/2 md:mb-0">
            <label
              class="block mb-2 text-xs font-bold tracking-wide text-gray-700 uppercase"
              for="first-name"
            >
              First Name
            </label>
            <input
              id="first-name"
              class="block w-full px-4 py-3 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
              type="text"
              placeholder="Jane"
              required
            >
          </div>
          <div class="w-full px-3 md:w-1/2">
            <label
              class="block mb-2 text-xs font-bold tracking-wide text-gray-700 uppercase"
              for="last-name"
            >
              Last Name
            </label>
            <input
              id="last-name"
              class="block w-full px-4 py-3 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
              type="text"
              placeholder="Doe"
              required
            >
          </div>
        </div>
        <div class="flex flex-wrap mb-2 -mx-3">
          <div class="w-full px-3 mb-6 md:w-1/3 md:mb-0">
            <label
              class="block mb-2 text-xs font-bold tracking-wide text-gray-700 uppercase"
              for="city"
            >
              City
            </label>
            <input
              id="city"
              class="block w-full px-4 py-3 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
              type="text"
              placeholder="Albuquerque"
              required
            >
          </div>
          <div class="w-full px-3 mb-6 md:w-1/3 md:mb-0">
            <label
              class="block mb-2 text-xs font-bold tracking-wide text-gray-700 uppercase"
              for="state"
            >
              State
            </label>
            <div class="relative">
              <select
                id="state"
                class="block w-full px-4 py-3 pr-8 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
              >
                <option>New Mexico</option>
                <option>Missouri</option>
                <option>Texas</option>
              </select>
              <div class="absolute inset-y-0 right-0 flex items-center px-2 text-gray-700 pointer-events-none">
                <svg
                  class="w-4 h-4 fill-current"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                ><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z" /></svg>
              </div>
            </div>
          </div>
          <div class="w-full px-3 mb-6 md:w-1/3 md:mb-0">
            <label
              class="block mb-2 text-xs font-bold tracking-wide text-gray-700 uppercase"
              for="zip"
            >
              Zip
            </label>
            <input
              id="zip"
              class="block w-full px-4 py-3 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
              type="text"
              placeholder="90210"
              required
            >
          </div>
          <div class="w-full px-3 mt-6 md:w-1/3 md:mb-0">
            <input
              class="px-12 py-2 font-bold text-white bg-teal-500 rounded shadow hover:bg-teal-700 focus:shadow-outline focus:outline-none"
              type="submit"
              value="Submit"
              name="Submit"
            >
          </div>
        </div>
      </form>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Contact Us'
  }
}
</script>
