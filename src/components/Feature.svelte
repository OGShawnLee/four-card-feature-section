<script lang="ts">
  export let border: string;
  export let icon: string;
  export let title: string;
</script>

<article class="p-8 | bg-white border-top-4 {border} rounded-lg shadow-xl">
  <h3 class="mb-1.5 | text-xl text-neutral-700 font-bold">{title}</h3>
  <p class="mb-8 | text-sm leading-relaxed">
    <slot />
  </p>
  <img class="block ml-auto" src={icon} alt="" height="64" width="64" />
</article>
