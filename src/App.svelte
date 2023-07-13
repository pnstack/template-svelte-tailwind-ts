<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<main>
  <div class="w-screen h-screen bg-gray-200 flex items-center justify-center">
    <div class="flex flex-col items-center justify-center">
      <h1 class="text-3xl font-bold">{count}</h1>
      <button class="px-5 py-3 bg-blue-300 rounded-lg" on:click={increment}
        >Inc</button
      >
    </div>
  </div>
</main>

<style>
</style>
