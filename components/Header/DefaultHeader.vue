<template>
  <header class="bg-green-300 h-[60px]">
    <nav class="h-[inherit]">
      <ul class="h-[inherit] space-x-14 flex justify-center items-center">
        <li>
          <nuxt-link class="linkHover" to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link class="linkHover" to="/decks">Decks</nuxt-link>
        </li>
        <li>
          <nuxt-link class="linkHover" to="/profile">Profile</nuxt-link>
        </li>
        <li>
          <nuxt-link class="linkHover" to="/settings">Settings</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
.linkHover {
  @apply hover:text-white;
}

.nuxt-link-exact-active {
  @apply px-4 py-2  text-base rounded-full text-green-600  bg-green-200;
}
</style>
