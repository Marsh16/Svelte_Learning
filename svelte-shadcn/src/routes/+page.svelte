<script lang="ts">
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Tooltip from "$lib/components/ui/tooltip/index.js";
</script>

<div class="flex items-center justify-center h-screen bg-gray-200">
  <Tooltip.Provider>
    <Tooltip.Root>
      <Tooltip.Trigger>
        <Button>Hover</Button>
      </Tooltip.Trigger>
      <Tooltip.Content>
        <p>Add to library</p>
      </Tooltip.Content>
    </Tooltip.Root>
  </Tooltip.Provider>
</div>
