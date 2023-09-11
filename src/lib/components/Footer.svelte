<script lang="js">
  import { page } from "$app/stores";
  import TW from "../constants/tailwind";
</script>

{#if $page.url.pathname == '/hook'}
  <div class="w-full py-4 text-center bg-ctp-base">
    &copy; 2023 <a href="https://github.com/slpy-one" target="_blank" class={TW.link}>slpy one team.</a> All Right Reserved.
  </div>
{:else}
  <div class="w-full py-4 fixed bottom-0 text-center bg-ctp-base">
    &copy; 2023 <a href="https://github.com/slpy-one" target="_blank" class={TW.link}>slpy one team.</a> All Right Reserved.
  </div>
{/if}