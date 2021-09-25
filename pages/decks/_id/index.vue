<template>
  <section>
    <div>
      <div class="container mx-auto mt-16 text-center space-y-8">
        <h3 class="font-semibold text-3xl">
          Deck {{ $route.params.id }}: Learn English
        </h3>
        <div class="space-x-8">
          <button
            type="button"
            class="btn bg-indigo-600 hover:bg-indigo-700 focus:ring-indigo-500"
          >
            Start now
          </button>
          <button
            type="button"
            class="btn bg-yellow-600 hover:bg-yellow-700 focus:ring-yellow-500"
          >
            Create a card
          </button>
        </div>
        <div
          class="
            grid
            sm:grid-cols-1
            md:grid-cols-2
            lg:grid-cols-3
            xl:grid-cols-4
            gap-8
            m-5
          "
        >
          <div
            class="shadow-lg rounded-2xl bg-white w-full m-auto overflow-hidden"
          >
            <img
              src="https://images.unsplash.com/photo-1632459103966-d17456fa22cd?ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw4fHx8ZW58MHx8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60"
              alt="adidas"
              class="h-[250px] w-full object-cover"
            />
            <div class="bg-pink-200 m-3 p-4 rounded-lg">
              <p class="text-white text-xl font-bold">Adidas</p>
              <p class="text-gray-50 text-xs">Live your dream</p>
            </div>
          </div>
          <div
            class="shadow-lg rounded-2xl bg-white w-full m-auto overflow-hidden"
          >
            <img
              src="https://images.unsplash.com/photo-1632459103966-d17456fa22cd?ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw4fHx8ZW58MHx8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60"
              alt="adidas"
              class="h-[250px] w-full object-cover"
            />
            <div class="bg-pink-200 m-3 p-4 rounded-lg">
              <p class="text-white text-xl font-bold">Adidas</p>
              <p class="text-gray-50 text-xs">Live your dream</p>
            </div>
          </div>
          <div
            class="shadow-lg rounded-2xl bg-white w-full m-auto overflow-hidden"
          >
            <img
              src="https://images.unsplash.com/photo-1632459103966-d17456fa22cd?ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw4fHx8ZW58MHx8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60"
              alt="adidas"
              class="h-[250px] w-full object-cover"
            />
            <div class="bg-pink-200 m-3 p-4 rounded-lg">
              <p class="text-white text-xl font-bold">Adidas</p>
              <p class="text-gray-50 text-xs">Live your dream</p>
            </div>
          </div>
          <div
            class="shadow-lg rounded-2xl bg-white w-full m-auto overflow-hidden"
          >
            <img
              src="https://images.unsplash.com/photo-1632459103966-d17456fa22cd?ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw4fHx8ZW58MHx8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60"
              alt="adidas"
              class="h-[250px] w-full object-cover"
            />
            <div class="bg-pink-200 m-3 p-4 rounded-lg">
              <p class="text-white text-xl font-bold">Adidas</p>
              <p class="text-gray-50 text-xs">Live your dream</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  validate({ params }) {
    return /^[0-9]$/.test(params.id)
  },
}
</script>

<style scoped>
.btn {
  @apply py-2 px-4 focus:ring-offset-indigo-200 text-white transition ease-in duration-200 text-center text-base font-semibold shadow-md focus:outline-none focus:ring-2 focus:ring-offset-2  rounded-lg;
}
</style>
