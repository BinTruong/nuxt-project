<template>
  <div>
    <div class="container mx-auto">
      <h3 class="text-3xl font-semibold my-8">List of your Decks</h3>
      <ul class="space-y-10">
        <li>
          <nuxt-link to="/decks/1">
            <div
              class="
                flex
                max-w-full
                bg-white
                shadow-lg
                rounded-lg
                overflow-hidden
              "
            >
              <div class="w-1/3 bg-cover bg-landscape">
                <img
                  class="w-full h-full object-cover object-center"
                  src="https://images.unsplash.com/photo-1628191011993-69070758764f?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=870&q=80"
                  alt="thumbnail
                "
                />
              </div>
              <div class="w-2/3 p-4">
                <h1 class="text-gray-900 font-bold text-2xl">Title card</h1>
                <p class="mt-2 text-gray-600 text-sm">Description</p>
              </div>
            </div>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/decks/2">
            <div
              class="
                flex
                max-w-full
                bg-white
                shadow-lg
                rounded-lg
                overflow-hidden
              "
            >
              <div class="w-1/3 bg-cover bg-landscape">
                <img
                  class="w-full h-full object-cover object-center"
                  src="https://images.unsplash.com/photo-1628191011993-69070758764f?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=870&q=80"
                  alt="thumbnail
                "
                />
              </div>
              <div class="w-2/3 p-4">
                <h1 class="text-gray-900 font-bold text-2xl">Title card</h1>
                <p class="mt-2 text-gray-600 text-sm">Description</p>
              </div>
            </div>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/decks/3">
            <div
              class="
                flex
                max-w-full
                bg-white
                shadow-lg
                rounded-lg
                overflow-hidden
              "
            >
              <div class="w-1/3 bg-cover bg-landscape">
                <img
                  class="w-full h-full object-cover object-center"
                  src="https://images.unsplash.com/photo-1628191011993-69070758764f?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=870&q=80"
                  alt="thumbnail
                "
                />
              </div>
              <div class="w-2/3 p-4">
                <h1 class="text-gray-900 font-bold text-2xl">Title card</h1>
                <p class="mt-2 text-gray-600 text-sm">Description</p>
              </div>
            </div>
          </nuxt-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    showDeck() {
      this.$router.push(`decks/${this.deckID}`)
    },
  },
}
</script>
