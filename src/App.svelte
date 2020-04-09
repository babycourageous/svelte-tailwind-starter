<script>
  export let name
  export let test = true
</script>

<main class="test-apply flex flex-col items-center">
  <h1 class="font-thin text-6xl uppercase" class:text-orange-500={test}>
    Hello {name}!
  </h1>
  <img class="w-2/3 object-cover" src="/rey.jpg" alt="" />
</main>

<style type="text/postcss">
  .test-apply {
    @apply w-3/5 mx-auto p-4;
  }
</style>
