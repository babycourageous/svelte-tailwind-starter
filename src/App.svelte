<script>
  export let name
</script>

<style type="text/postcss">
  .test-apply {
    @apply w-3/5 mx-auto p-4;
  }
</style>

<main class="test-apply flex flex-col items-center">
  <h1 class="font-thin text-6xl text-orange-500 uppercase">Hello {name}!</h1>
  <img class="w-2/3 object-cover" src="/rey.jpg" alt="" />
</main>
