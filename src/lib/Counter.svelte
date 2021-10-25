<script lang="ts">
  let count: number = 0
  const increment = () => {
    count += 1
  }
</script>

<button class="px-8 py-4 w-52 text-red-500 bg-red-200 rounded-full" on:click={increment}>
  Clicks: {count}
</button>