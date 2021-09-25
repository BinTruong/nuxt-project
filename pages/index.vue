<template>
  <div>
    <div class="container mx-auto mt-10">
      <div
        class="h-[200px] w-full object-cover bg-banner bg-center bg-no-repeat"
      ></div>
    </div>
    <div class="text-center mt-10">
      <h3 class="text-3xl font-medium">Popular decks for you</h3>
      <div
        class="
          container
          mx-auto
          grid
          sm:grid-cols-1
          md:grid-cols-2
          lg:grid-cols-3
          xl:grid-cols-3
          p-10
          gap-8
        "
      >
        <div class="rounded-lg shadow-xl overflow-hidden h-52">
          <img
            class="h-full w-full object-cover"
            src="https://images.unsplash.com/photo-1593642702821-c8da6771f0c6?ixid=MnwxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHw1NXx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60"
            alt=""
          />
        </div>

        <div class="rounded-lg shadow-xl overflow-hidden h-52">
          <img
            class="h-full w-full object-cover"
            src="https://images.unsplash.com/photo-1593642702821-c8da6771f0c6?ixid=MnwxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHw1NXx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60"
            alt=""
          />
        </div>

        <div class="rounded-lg shadow-xl overflow-hidden h-52">
          <img
            class="h-full w-full object-cover"
            src="https://images.unsplash.com/photo-1593642702821-c8da6771f0c6?ixid=MnwxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHw1NXx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
